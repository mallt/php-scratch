[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

## php scratch buffer for emacs
php-scratch is a scratch buffer for emacs to interactively evaluate php code.

<p align="center">
    <img src="https://raw.github.com/mallt/php-scratch/master/php-scratch.gif" alt="php scratch screencast"/>
</p>

## Installation
php-scratch depends on the [Boris PHP REPL](https://github.com/borisrepl/boris).

The `php-scratch-boris-command` variable has to be set to the path of the boris command.

## Usage
- Open the php scratch buffer with the following command: <kbd>M-x</kbd> `php-scratch`

- You can evaluate php code in the scratch buffer by marking a region and pressing <kbd>C-c C-e</kbd>. If there is no active region, the current line will be evaluated. The evaluation result will be shown in the minibuffer.

- To clear the state of the evaluated code (f.ex. variables and function declarations), you can press <kbd>C-c C-c</kbd>.

[badge-license]: https://img.shields.io/badge/license-GPL_3-green.svg
