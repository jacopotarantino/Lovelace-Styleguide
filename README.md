# Lovelace-Styleguide

> Generates a complete styleguide for your UI components.

[![Code Climate](https://codeclimate.com/github/jacopotarantino/Lovelace-Styleguide/badges/gpa.svg)](https://codeclimate.com/github/jacopotarantino/Lovelace-Styleguide)
[ ![Codeship Status for jacopotarantino/Lovelace-Styleguide](https://codeship.com/projects/bd464170-156f-0133-c2a5-662e297fd73a/status?branch=master)](https://codeship.com/projects/79270)
## Getting Started
This plugin requires Grunt `~0.4.5`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install lovelace-styleguide --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('lovelace-styleguide');
```

## The "Lovelace_Styleguide" task

### Overview
In your project's Gruntfile, add a section named `lovelace-styleguide` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  'lovelace-styleguide': {
    options: {
      // Task-specific options go here.
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    }
  }
});
```

### Options

### Usage Examples

#### Default Options
In this example, the source and destination folders are specified. Everything else happens automagically :).

```js
grunt.initConfig({
  Lovelace_Styleguide: {
    options: {},
    app: {
      src: 'path/to/ui-components-folder',
      dest: 'path/to/output-folder'
    }
  }
});
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

### Testing

Run `npm install` and `npm test`. All tests are maintained in the `/test` folder.

## License

[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/legalcode)

### You are free to:

* Share — copy and redistribute the material in any medium or format
* Adapt — remix, transform, and build upon the material for any purpose, even commercially.

You're allowed these freedoms as long as you follow the below license terms.

### But you must follow these rules:

* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
