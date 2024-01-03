# sly-overlay

This library is an extension for [Sly][sly] that enables the overlay of Common
Lisp evaluation results directly into the buffer in the spirit of [CIDER][cider]
(Clojure) and [Eros][eros] (Emacs Lisp).

The primary function to call is `sly-overlay-eval-defun`, which can be bound to
whatever is usually bound to `sly-eval-defun`.

There is otherwise no other setup necessary for using the library.

[sly]: https://github.com/joaotavora/sly
[cider]: https://github.com/clojure-emacs/cider
[eros]: https://github.com/xiongtx/eros
