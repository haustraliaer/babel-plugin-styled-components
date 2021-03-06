# `babel-plugin-styled-components`

This plugin is a highly recommended supplement to the base styled-components library, offering some useful features:

* consistently hashed component classNames between environments (a must for server-side rendering)
* automatic library usage tweaks that allow for some bytes to be dropped from your bundle
* better debugging through automatic annotation of your styled components based on their context in the file system, etc.
* various types of minification for styles and the tagged template literals styled-components uses

## Quick start

Install the plugin first:

```
npm install --save-dev babel-plugin-styled-components
```

Then add it to your babel configuration:

```JSON
{
  "plugins": ["babel-plugin-styled-components"]
}
```

## styled-components v4 beta

If you are using the styled-components v4 beta, you'll also need to use the beta version of this plugin:

```
npm install --save-dev babel-plugin-styled-components@beta
```

Older versions should technically work, but some of the bundle size reduction benefits are only realized with the newer code!

## Documentation

**The documentation for this plugin lives on [the styled-components website](https://www.styled-components.com/docs/tooling#babel-plugin)!**

* [Usage](https://www.styled-components.com/docs/tooling#usage)
* [Better debugging](https://www.styled-components.com/docs/tooling#better-debugging)
* [Minification](https://www.styled-components.com/docs/tooling#minification)

## License

Licensed under the MIT License, Copyright © 2016-present Vladimir Danchenkov and Maximilian Stoiber.

See [LICENSE.md](./LICENSE.md) for more information.
