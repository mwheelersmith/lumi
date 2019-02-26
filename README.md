# lumi
A base Statamic theme built on Tailwind CSS and Laravel Mix

## Install
1. Place the **lumi theme** into your **site/themes** directory
2. Go to the **site/themes/lumi** directory in your **terminal**
3. Run **npm install** or yarn install
4. You can now run any of the npm scripts such as **npm run dev**

## Addons
The 'Statamic Mix' addon by [Ben Furfie](https://github.com/benfurfie) is required to support the Laravel Mix manifest for file versioning.
1. Download the **Statamic Mix** addon
(https://statamic.com/marketplace/addons/statamic-mix)
2. Place **Mix** into your **site/addons** directory

## NPM Scripts
All of the npm scripts are provided by Laravel Mix, so feel free to check out the documentation for that here:
https://laravel.com/docs/5.7/mix#running-mix

``` bash
// Run all Mix tasks...
$ npm run dev

// Run all Mix tasks and minify output...
$ npm run production

// Watch assets...
$ npm run watch
```

# License
[MIT](http://opensource.org/licenses/MIT)