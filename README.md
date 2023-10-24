# Scream

This is a very simple CloudFoundry app to allow people to scream into a void.

## Deployment

To deploy with CloudFoundry's `staticfile` buildpack,

```shell
$ cf create-app scream
$ cf push scream
```

## Development

The single HTML file displayed is in [`public/index.html`](public/index.html).
