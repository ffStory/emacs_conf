1把下面代码拷贝到init.el 中

;;; init.el --- Initialization file for Emacs
;;; Commentary:
;;; Code:
(add-to-list 'load-path "~/.emacs.d/emacs-conf/")
(setq custom-file "~/.emacs.d/emacs-conf/custom-auto.el")
(load custom-file)
(load "packages")
(load "funcs")
(load "custom-manual")
(load "keybindings")

;;; init.el ends here

2ln -s 软连接snippets. 路径写绝对路径。
