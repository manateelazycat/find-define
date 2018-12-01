# What is find-define.el ?
Jump to the definition of a function or variable.

`find-define' supports the following programming languages:

| Language   | Backend   |
| :--------: | :----     |
| Elisp      | elisp-def |
| Python     | jedi-core |
| Golang     | go-mode   |
| JavaScript | tide      |
| Other      | dumb-jump |

## Installation
Clone or download this repository (path of the folder is the `<path-to-find-define>` used below).

In your `~/.emacs`, add the following two lines:
```Elisp
(add-to-list 'load-path "<path-to-find-define>") ; add find-define to your load-path
(require 'find-define)
```

## Usage
Bind your favorite key to functions:

| Function         | Description                       |
| :--------        | :----                             |
| find-define      | Find definition in current window |
| C-x find-define  | Find definition in other window   |
| find-define-back | Back to position before jump      |
|                  |                                   |

## Contribute
Wecome to contribute more language backend with [PR](https://github.com/manateelazycat/find-define/pulls)
