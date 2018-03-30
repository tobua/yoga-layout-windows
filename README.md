# yoga-layout

> Prebuilt for Windows

Prebuilt JS version of the yoga layout flexbox engine.

## Usage with `@react-pdf/core`

`package.json`

```
{
  "dependencies": {
    "yoga-layout": "github:naminho/yoga-layout-windows",
    "@react-pdf/core": "latest"
  }
}
```

This will override the `yoga-layout` dependency of `react-pdf` and so it can
be installed on Windows as well.

See these issues for the current status [react-pdf](https://github.com/diegomura/react-pdf/issues/151) and [yoga](https://github.com/facebook/yoga/issues/411).
