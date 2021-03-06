linter-phpcs
=========================

This linter plugin for [Linter](https://github.com/AtomLinter/Linter) provides an interface to [phpcs](http://pear.php.net/package/PHP_CodeSniffer/). It will be used with files that have the “PHP” and “HTML” syntax.

## Installation
Linter package must be installed in order to use this plugin. If Linter is not installed, please follow the instructions [here](https://github.com/AtomLinter/Linter).

### phpcs installation
Before using this plugin, you must ensure that `phpcs` is installed on your system. To install `phpcs`, do the following:

1. Install [php](http://php.net).

2. Install [pear](http://pear.php.net).

3. Install `phpcs` by typing the following in a terminal:
   ```
   pear install PHP_CodeSniffer
   ```

Now you can proceed to install the linter-phpcs plugin.

### Plugin installation
```
$ apm install linter-phpcs
```

## Settings
You can configure linter-phpcs by editing ~/.atom/config.cson (choose Open Your Config in Atom menu):
```
'linter-phpcs':
  'phpcsExecutablePath': null #phpcs path. run 'which phpcs' to find the path
  'standard': 'PSR2' #phpcs standard
```

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. welcome to the club

Please note that modications should follow these coding guidelines:

- Indent is 2 spaces.
- Code should pass coffeelint linter.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
