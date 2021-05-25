;; $Id: .emacs_dwchin,v 1.2 2002/05/08 23:24:39 dwchin Exp $
;; And also 21.1.1  2002-05-08  :)
;; Now works with emacs 20.4.1 -- 29 Oct 1999
;;
;; Ver 2.01 1999
;; 
;; $Id: .emacs_dwchin,v 1.2 2002/05/08 23:24:39 dwchin Exp $
;;
;; This configuration file is used to configure emacs so that it
;; behaves like wordstar
;;
;; Ver 2.00 1998
;;
;; by D. Chin, University of Michigan
;;
;; Hacked to work for Emacs 19.34.  Will also work with Emacs 20.2,
;; but not thoroughly tested.
;; 
;; Ver 1.00 1990 
;;
;; by C.Y. Tan, Cornell University

;; However we still have lots of PROBLEMS!!

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Contrary to popular belief,  .emacs starts up LAST relative to the
;; system manager files like startup.el etc
;; However due to some oversight by the system manager,  the
;; compile.el and the compile.elc are NOT the same this means that
;; issuing the find next error command does not work unless compile.el
;; is loaded!!
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Mods by David Chin
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; BEGIN OBSOLETE SECTION
;;
;; The following requires and [f]makunbounds should be in .emacs rather
;; than .emacs_dwchin since these have to be done before any loading.
;; Actually, things seem to work without these; in particular cc-mode.
;;

;(require 'tex-site)

;(fmakunbound 'c-mode)
;(fmakunbound 'cc-mode)
;(makunbound 'c-mode-map)
;(makunbound 'cc-mode-map)
;(fmakunbound 'c++-mode)
;(makunbound 'c++-mode-map)
;(makunbound 'c-style-alist)
;
;(fmakunbound 'c-mode)
;(makunbound 'c-mode-map)
;(fmakunbound 'c++-mode)
;(makunbound 'c++-mode-map)
;(makunbound 'c-style-alist)
;
;(fmakunbound 'lisp-mode)
;(makunbound 'shared-lisp-mode-map)
;(makunbound 'emacs-lisp-mode-map)
;(makunbound 'lisp-mode-map)
;(makunbound 'lisp-interaction-mode-map)
;(makunbound 'lisp-style-alist)


;(load-file "/usr/users/dwchin/Library/Emacs/fortran.el")
;(load-file "/usr/users/dwchin/Library/Emacs/ps-print.el")
;(load-file "/usr/users/dwchin/Library/Emacs/lisp-mode.elc")
;(load-file "/usr/users/dwchin/Library/Emacs/man.elc")
;(load-file "/usr/users/dwchin/Library/Emacs/context.elc")
;(load-file "/usr/users/dwchin/Library/Emacs/tex-mode.elc")
;(load-file "/usr/users/dwchin/Library/Emacs/timezone.elc")
;(load-file "/usr/users/dwchin/Library/Emacs/ediff.elc")

;;
;; Add ccpy-mode.el (Python C style)
;;
;(add-hook 'c-mode-common-hook '(lambda () (require 'python-style)))

;;
;;
;; END OBSOLETE SECTION
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;


;;
;; Turn off scroll bar
;;
;(scroll-bar-mode -1)

;;
;; Font list for Xemacs.
;;
;(setq
; x-fixed-font-alist
;; ("Font Menu"
;  ("Fonts"
;   ("6x12" "-misc-fixed-medium-r-semicondensed--12-110-75-75-c-60-;-1")
;   ("6x13" "-misc-fixed-medium-r-semicondensed--13-120-75-75-c-60-;-1")
;   ("lucida 13" "-b&h-lucidatypewriter-medium-r-normal-sans-0-0-0-0-m-0-;-1")
;   ("7x13" "-misc-fixed-medium-r-normal--13-120-75-75-c-70-;-1")
;   ("7x14" "-misc-fixed-medium-r-normal--14-130-75-75-c-70-;-1")
;   ("9x15" "-misc-fixed-medium-r-normal--15-140-;-;-c-;-;-1")
;   ("")
;   ("clean 8x8" "-schumacher-clean-medium-r-normal--;-80-;-;-c-;-;-1")
;   ("clean 8x14" "-schumacher-clean-medium-r-normal--;-140-;-;-c-;-;-1")
;   ("clean 8x10" "-schumacher-clean-medium-r-normal--;-100-;-;-c-;-;-1")
;   ("clean 8x16" "-schumacher-clean-medium-r-normal--;-160-;-;-c-;-;-1")
;   ("")
;   ("sony 8x16" "-sony-fixed-medium-r-normal--16-120-100-100-c-80-;-1")
;   ("")
;   ("-- Courier --")
;   ("Courier 10" "-adobe-courier-medium-r-normal--;-100-;-;-m-;-;-1")
;   ("Courier 12" "-adobe-courier-medium-r-normal--;-120-;-;-m-;-;-1")
;   ("Courier 14" "-adobe-courier-medium-r-normal--;-140-;-;-m-;-;-1")
;   ("Courier 18" "-adobe-courier-medium-r-normal--;-180-;-;-m-;-;-1")
;   ("Courier 18-b" "-adobe-courier-bold-r-normal--;-180-;-;-m-;-;-1")
;   )))

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Unset all irritating Emacs keys
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

;(global-unset-key "\M-c")
;(global-unset-key "\M-v")
;(global-unset-key "\C-c")
;(global-unset-key "\C-g")
;(global-unset-key "\C-n")
;(global-unset-key "\C-p")
;(global-unset-key "\C-]")
;(global-unset-key "\C-x")
;(global-unset-key [delete])     ; The DELete key
;(global-unset-key [backspace])  ; The Backspace key


;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; We need to define a few functions
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(defvar oldbeg)            ; these variables hold
(defvar oldend)            ; the previous marked positions

(defun copy-this(beg end)
    "Mark the region and copy it into the buffer"
    (interactive "*r")
    (exchange-point-and-mark)
    (setq oldbeg beg)        ; update the marked positions
    (setq oldend end)
    (copy-region-as-kill beg end))

(defun move-this(beg end)
  "Kill the previously marked region then yank the region to current position"
    (interactive ";r")
    (kill-region oldbeg oldend)
    (yank)
    (setq oldbeg beg)        ; save position so we
    (setq oldend end))        ; know where to delete    

(defun save-and-quit()
  "Save the current file and quit"
    (interactive)
    (write-file "")
    (kill-emacs))

(defun auto-indent()
  "Indent automatically after each new line"
  (interactive)        
  (newline)
;  (indent-relative-maybe)
  (indent-according-to-mode))   ; no maybes about it

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Window functions
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(defun scroll-up-other-window()
"Scrolls up the next or previous window"
   (interactive)    
   (scroll-other-window (- 0 (window-height(next-window)))))
   
(defun goto-next-window()
"Goto next window"
   (interactive)
   (select-window (next-window)))
   
(defun goto-previous-window()
"Goto previous window"
   (interactive)
   (select-window (previous-window)))
   
(defun delete-current-window()
"Kill the window cursor is on"
   (interactive)
   (defvar count (window-height(selected-window)))
   (delete-window)
   (select-window(previous-window)))
   
; (defun open-another-window(filename)
; "Open another window"
;     (split-window)   
;     (interactive "Find file: ")
;     (switch-to-buffer (find-file-noselect filename)))

;;
;; Here's a function from the Emacs FAQ to see raw chars.
;;
(defun see-chars () 
"Display events received, terminated by a 3-second timeout."
    (interactive)
    (let (chars
          (inhibit-quit t))
      (message "Enter characters or other events, terminated by a 3-second timeout.")
      (while (not (sit-for 3))
        (setq chars (nconc chars (list (read-event)))
              quit-flag nil)        ; quit-flag might be set by C-g.
        (if (not (input-pending-p))
            (message "Events received until now: %s..."
                     (key-description chars))))
      (message "Events received: %s" (key-description chars))))


;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Compile commands
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(defun read-errors()
"Read all the errors from the compiler again"
   (interactive)
   (next-error t))
   
; (defun goto-next-error()
;    (interactive)
;    (find-next-error t))

   
; (defun goto-previous-error()
;     (interactive)
;     (find-next-error nil))


;;
;; There might be problems with the following find-next-error function.
;; Probably parenthesized badly.
;;

; (defun find-next-error(&optional argp)

; "This function supersedes that supplied by IBM.  It enables the error list
; to be traversed forward and backwards by setting its argument to t or null.
; If t then find next error. If null find previous error"

;    (interactive "P")
;    (if (eq compilation-error-list t)
;        (progn (compilation-forget-errors)
;           (setq compilation-parsing-end 1)))
;    (if compilation-error-list
;        nil
;       (save-excursion
;         (switch-to-buffer "*compilation*")
;     (set-buffer-modified-p nil)
;     (compilation-parse-errors)))

;     (let (if (eq (argp)) (find-next-error(car compilation-error-list)))
; ;    (if  (eq argp t)) (message "here I am"))

;          ;(find-next-error (car (nreverse previous-error-list)))))

;           (if (null find-next-error)
;           (error (concat compilation-error-message
;                      (if (and compilation-process
;                       (eq (process-status compilation-process)
;                           'run))
;                  " yet" ""))))

;           (append previous-error-list (car compilation-error-list))
;           (setq compilation-error-list (cdr compilation-error-list))
;           (if (null(car (cdr find-next-error)))
;           nil
;          (switch-to-buffer(marker-buffer (car (cdr find-next-error))))
;          (goto-char (car (cdr find-next-error)))
;          (set-marker (car (cdr find-next-error)) nil))
;       (let* ((pop-up-windows t)
;          (w (display-buffer (marker-buffer (car find-next-error)))))
;         (set-window-point w (car find-next-error))
;         (set-window-start w (car find-next-error)))
;       (set-marker (car find-next-error) nil)))

;;
;; Here's a keymap for VT220 emulator at home.
;;
(define-key function-key-map '[kp-f4] 'help)
;(define-key function-key-map "\033" 'help)

;;
;; Globally define all WordStar key mappings.
;;
(defun ws-map()
   ;;
   ;; First, unset a bunch of keys
   ;; Hmm. Do I also need to do this above?
   ;;
   (global-unset-key "\C-d")
   (global-unset-key "\C-x")
   (global-unset-key "\C-p")  ;this replaces C-c
   (global-unset-key "\C-l")
   (global-unset-key "\M-c")
   (global-unset-key "\M-v")

;   (global-unset-key "\M-c")
;   (global-unset-key "\M-v")
;   (global-unset-key "\C-x")
;   (global-unset-key "\C-p")

   (global-unset-key "\C-c")
   (global-unset-key "\C-g")
   (global-unset-key "\C-n")
   (global-unset-key "\C-]")
   (global-unset-key [delete])     ; The DELete key
   (global-unset-key [backspace])  ; The Backspace key

;   ;;
;   ;; Fix Delete and BackSpace key.  From:
;   ;;
;   ;; @@@@@@ @@@ @@@@@@ @    @    Ehud Karni                Simon  & Wiesel
;   ;;     @    @      @  @@  @    Senior System Support     Insurance agency
;   ;;     @    @ @    @ @  @@     Tel: +972-3-6212-757  Fax: +972-3-6292-544
;   ;;     @    @ @    @ @    @        Better     Safe     Than     Sorry
;   ;; http://www.simonwiesel.co.il        mailto:ehud@unix.simonwiesel.co.il 
;   ;;
;   ;; Modified by me, of course.  Make keys explicit, rather than
;   ;; relying on function-key-map which changes between ASCII terminals
;   ;; and X.
;   ;;
;;   (define-key function-key-map '[delete]  nil)
;;              ; delete [delete] from function key map so it stays [delete]
;;   (define-key function-key-map '[kp-delete]  [delete])
;;              ; add grey delete to be same as delete key
;;   (define-key function-key-map '[backspace]  nil)
;;              ; delete [backspace] from function key map 
;;              ; so it stays [backspace]
;;   (define-key global-map  '[delete]  'delete-char)
;;              ; whatever you want for delete key to do
;;   (define-key global-map  '[backspace]  'backward-delete-char-untabify)
;;              ; whatever you want for backspace key to do
;;   (define-key global-map  "\177"     'delete-char)
;;              ; whatever you want for DEL to do 
;;              ; (backspace is set to DEL by function-key-map)

;;   (define-key function-key-map '[return]   nil)
;;   (define-key function-key-map '[return]   "\n")
;;   (define-key function-key-map '[return]   "\n")     ; remap to LFD
;;   (define-key function-key-map '[return]   "\012")
;;   (define-key global-map       "\C-m"      "\n")
;;   (global-set-key              "\C-m"      "\n")

   (define-key function-key-map '[delete]    nil)
   (define-key function-key-map '[backspace] nil)
   (define-key function-key-map '[kp-delete] [delete])
   (define-key function-key-map '[kp-enter]  nil)

   ;(define-key function-key-map '[delete]    "\177")  ; map [delete] to DEL
   (define-key function-key-map '[delete]    "\C-h")  ; map [delete] to DEL
   ;(define-key function-key-map '[backspace] "\C-h")  ; map [backspace] to C-h
   (define-key function-key-map '[kp-enter]  "\n")    ; map [kp-enter] to LFD
   
   (global-set-key '[home] 'beginning-of-buffer)
   (global-set-key '[end]  'end-of-buffer)

   ;;
   ;; A bunch of global keys
   ;;
   (global-set-key "\C-h"      'backward-delete-char-untabify)  ; \010 == \C-h
   (global-set-key '[backspace] 'backward-delete-char-untabify)
   ;(global-set-key "\177"    'delete-char)            ; \C-\? == \177 == DEL
   ;(global-set-key "\177"    'delete-char)            ; \C-\? == \177 == DEL
   ;(define-key global-map "\177" 'delete-char)
   (global-set-key "\177"    'backward-delete-char-untabify)
   (define-key global-map "\177" 'backward-delete-char-untabify)
   (global-set-key "\M-\010" 'backward-kill-word)
   (global-set-key '[C-backspace] 'backward-kill-word)
   (global-set-key "\M-\177" 'kill-word)
   (global-set-key '[C-delete] 'kill-word)


   (global-set-key "\C-o" 'delete-char)

   (global-set-key "\C-y" 'kill-line)
   (global-set-key "\M-y" 'kill-sentence)

   (global-set-key "\C-t" 'kill-word)

   (global-set-key "\240" '\ )

   (global-set-key "\C-s" 'backward-char)
   (global-set-key "\C-a" 'backward-word)
   (global-set-key "\C-d" 'forward-char)
   (global-set-key "\C-f" 'forward-word)
   (global-set-key "\C-x" 'next-line)
   (global-set-key "\C-e" 'previous-line)

   (global-set-key "\C-c" 'scroll-up)
   (global-set-key "\C-r" 'scroll-down)

   (global-set-key "\C-v" 'overwrite-mode)
   (global-set-key "\C-n" 'open-line)
   (global-set-key "\C-u" 'advertised-undo)
   (global-set-key "\C-l" 'previous-complex-command)
   (global-set-key "\C-m" 'auto-indent)
;   (global-set-key "\C-m" 'newline-and-indent)  ; not very useful 
                                                 ; doesn't give continuation
   (global-set-key "\C-b" 'fill-paragraph)
;   (global-set-key "\011" 'indent-according-to-mode)
   (global-set-key "\C-i" 'indent-according-to-mode)
;   (global-set-key "\C-i" 'indent-relative)
   (global-set-key "\C-\\" 'transpose-chars)
   (global-set-key "\M-\\" 'transpose-words)

   (global-set-key "\C-_" 'universal-argument)
   
   (global-set-key "\M-c" 'compile)
   (global-set-key "\M-p" 'goto-previous-error)
   (global-set-key "\M-n" 'next-error)
   (global-set-key "\M-f" 'read-errors)
   (global-set-key "\M-v" 'quoted-insert)
   
   ;;
   ;; Control-K sequences
   ;;
   (define-key global-map "\C-k" 'K-prefix)
   (setq K-map (make-keymap))
       (fset 'K-prefix K-map)
       (define-key K-map "\C-s" 'save-buffer)
       (define-key K-map "s"    'save-buffer)
       (define-key K-map "\C-l" 'kill-buffer)
       (define-key K-map "l"    'kill-buffer)
       (define-key K-map "\C-q" 'kill-emacs)
       (define-key K-map "q"    'kill-emacs)
       (define-key K-map "\C-d" 'save-and-quit)
       (define-key K-map "d"    'save-and-quit)
       (define-key K-map "\C-r" 'insert-file)
       (define-key K-map "r"    'insert-file)
       (define-key K-map "\C-g" 'switch-to-buffer)
       (define-key K-map "g"    'switch-to-buffer)
;      (define-key K-map "\C-t" 'kill-word)    
;      (define-key K-map "t"    'kill-word)
       (define-key K-map "\C-b" 'set-mark-command)
       (define-key K-map "b"    'set-mark-command)
       (define-key K-map "\C-k" 'copy-this)
       (define-key K-map "k"    'copy-this)
       (define-key K-map "\C-v" 'move-this)
       (define-key K-map "v"    'move-this)
       (define-key K-map "\C-f" 'find-file)
       (define-key K-map "f"    'find-file)
       (define-key K-map "\C-w" 'write-file)
       (define-key K-map "w"    'write-file)
       (define-key K-map "\C-y" 'kill-region)
       (define-key K-map "y"    'kill-region)
       (define-key K-map "\C-c" 'yank)
       (define-key K-map "c"    'yank)

   ;;
   ;; Control-Q sequences
   ;;
   (define-key global-map "\C-q" 'Q-prefix)
   (setq Q-map (make-keymap))
       (fset 'Q-prefix Q-map)
       (define-key Q-map "\C-s" 'beginning-of-line)
       (define-key Q-map "s"    'beginning-of-line)
       (define-key Q-map "\C-d" 'end-of-line)
       (define-key Q-map "d"    'end-of-line)
       (define-key Q-map "\C-r" 'beginning-of-buffer)
       (define-key Q-map "r"    'beginning-of-buffer)
       (define-key Q-map "\C-c" 'end-of-buffer)
       (define-key Q-map "c"    'end-of-buffer)
       (define-key Q-map "\C-i" 'indent-c-exp)
       (define-key Q-map "i"    'indent-c-exp)
       (define-key Q-map "\C-f" 'search-forward)
       (define-key Q-map "f"    'search-forward)
;      (define-key Q-map "\C-g" 'nonincremental-repeat-search-forward)
;      (define-key Q-map "g"    'nonincremental-repeat-search-forward)
       (define-key Q-map "\C-x" 'posix-search-forward)
       (define-key Q-map "x"    'posix-search-forward)
       (define-key Q-map "\C-b" 'search-backward)
       (define-key Q-map "b"    'search-backward)
       (define-key Q-map "\C-n" 'next-error)
       (define-key Q-map "n"    'next-error)
       (define-key Q-map "\C-p" 'previous-error)
       (define-key Q-map "p"    'previous-error)
       (define-key Q-map "\C-a" 'replace-string)
       (define-key Q-map "a"    'replace-string)
       (define-key Q-map "\C-e" 'replace-regexp)
       (define-key Q-map "e"    'replace-regexp)
       (define-key Q-map "\C-l" 'goto-line)
       (define-key Q-map "l"    'goto-line)

   ;;
   ;; Control-W sequences
   ;;
   (define-key global-map "\C-w" 'window-prefix)
   (setq window-map (make-keymap))
       (fset 'window-prefix window-map)
       (define-key window-map "\C-x" 'goto-next-window) 
       (define-key window-map "\C-e" 'goto-previous-window)
       (define-key window-map "\C-c" 'scroll-other-window)
       (define-key window-map "\C-r" 'scroll-up-other-window)
       (define-key window-map "\C-w" 'open-another-window)
       (define-key window-map "\C-n" 'enlarge-window)
       (define-key window-map "\C-y" 'shrink-window)
       (define-key window-map "\C-f" 'make-frame)
       (define-key window-map "\C-g" 'delete-frame)
   
       (define-key window-map "\C-k\C-g" 'switch-to-buffer-other-window)    
       (define-key window-map "\C-k\C-f" 'find-file-other-window)    
       (define-key window-map "\C-k\C-y" 'delete-current-window)

       (define-key window-map "\C-k\C-w" 'find-file-other-frame)    

   ;;
   ;; Miscellaneous
   ;;
   (define-key global-map "\C-p" 'misc-prefix)
   (setq misc-map (make-keymap))
      (fset 'misc-prefix misc-map)
      ;; mappings for BEopen's oo-browser
      ;(define-key misc-map "\C-o" 'oo-browser)
      ;(define-key misc-map "^" 'br-add-class-file)
      ;(define-key misc-map "\C-v" 'br-to-from-viewer)
)

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;;   This is where all the modes arise from
;;   ws-mode is the fundamental mode. All other modes set themselves to
;;   the minor modes then call this mode which remaps all the keys and etc
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(defun ws-mode()
"WordStar mode for PC users familiar with the Borland family
 and of course WORDSTAR"
 (interactive)
 (setq tab-stop-list '(4 8 12 16 20 24 28 32 36 40 44 48 52 56 60 64 68 72 76 80 84 88 92 96 100 104 108 112 116 120))
 (kill-all-local-variables)
; (auto-fill-mode 1)   ; This seems to be useless, too
 (setq major-mode 'ws-mode)
 (setq default-major-mode 'ws-mode)
 (setq ws-mode t)  ; flag to say that ws-mode is on
 (ws-map)
 (run-hooks 'ws-mode-hook))

 
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Check to see if keys have been remapped, and rename modes
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(defun ws-text-mode()
  (if (not (eq major-mode 'ws-mode))        ; check if keys already remapped
     (ws-mode))
  (text-mode)   
  (setq mode-name "WS-Text"))               ; rename mode

(defun ws-latex-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (latex-mode)   
  (setq mode-name "WS-LaTeX"))

;(defun ws-tex-mode()
;  (if (not (eq major-mode 'ws-mode))
;     (ws-mode))
;  (tex-mode)   
;  (setq mode-name "WS-TeX"))

;;(defun ws-c-mode()
;;    (if (not (eq major-mode 'ws-mode))
;;     (ws-mode))
;;     (setq c-tab-always-indent nil)    
;;     (c-mode)
;;  (setq mode-name "WS-C"))

(defun ws-c-mode()
    (if (not (eq major-mode 'ws-mode))
     (ws-mode))
     (setq c-tab-always-indent nil)    
     (c-mode)
  (setq mode-name "WS-C"))

(defun ws-c++-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (setq c-tab-always-indent nil)
  (c++-mode)
  (setq mode-name "WS-C++"))

(defun ws-objc-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (setq c-tab-always-indent nil)
  (objc-mode)
  (setq mode-name "WS-ObjC"))

(defun ws-java-mode()
    (if (not (eq major-mode 'ws-mode))
     (ws-mode))
     (java-mode)
  (setq mode-name "WS-Java"))

(defun ws-sh-mode()
    (if (not (eq major-mode 'ws-mode))
     (ws-mode))
     (sh-mode)
  (setq mode-name "WS-Shell-script"))
  
(defun ws-html-helper-mode()
    (if (not (eq major-mode 'ws-mode))
     (ws-mode))
     (html-helper-mode)
  (setq mode-name "WS-HTML"))

(defun ws-tcl-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (tcl-mode)   
  (setq mode-name "WS-TCL"))

(defun ws-scheme-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (scheme-mode)   
  (setq mode-name "WS-Scheme"))
  
(defun ws-lisp-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (lisp-mode)   
  (setq mode-name "WS-Lisp"))
  
(defun ws-fortran-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (fortran)
  (setq mode-name "WS-Fortran"))
  
; (defun ws-scribe-mode()
;   (if (not (eq major-mode 'ws-mode))
;      (ws-mode))
;   (scribe-mode)   
;   (setq mode-name "WS-Scribe"))

(defun ws-idlwave-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (idlwave-mode)
  (setq mode-name "WS-IDLWAVE"))

(defun ws-matlab-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (matlab-mode)
  (setq mode-name "WS-Matlab"))
  
(defun ws-prolog-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (prolog-mode)   
  (setq mode-name "WS-Prolog"))
  
; (defun ws-textinfo-mode()
;   (if (not (eq major-mode 'ws-mode))
;      (ws-mode))
;   (text-info-mode)   
;   (setq mode-name "WS-TextInfo"))
  
(defun ws-emacs-lisp-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (emacs-lisp-mode)   
  (setq mode-name "WS-Emacs-Lisp"))

(defun ws-perl-mode()
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (perl-mode)
  (setq mode-name "WS-Perl"))

(defun ws-python-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (python-mode)
  (setq mode-name "WS-Python"))
  
; (defun ws-kumac-mode()
;   (if (not (eq major-mode 'ws-mode))
;       (ws-mode))
;   (kumac-mode)
;   (setq mode-name "WS-KUMAC"))
  
(defun ws-makefile-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (makefile-mode)
  (setq mode-name "WS-Makefile"))

; (defun ws-gnuplot-mode()
;   (if (not (eq major-mode 'ws-mode))
;       (ws-mode))
;   (gnuplot-mode)
;   (setq mode-name "WS-GnuPlot"))

(defun ws-css-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (css-mode)
  (setq mode-name "WS-CSS"))
  
(defun ws-m4-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (m4-mode)
  (setq mode-name "WS-M4"))

(defun ws-mortran-mode()
  (if (not (eq major-mode 'ws-mode))
      (ws-mode))
  (mortran-mode)
  (setq mode-name "WS-Mortran"))
  
(defun ws-fundamental-mode()
  (fundamental-mode)
  (if (not (eq major-mode 'ws-mode))
     (ws-mode))
  (setq mode-name "WS-Fundamental"))

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;;   Now we have to map all the default file extensions to that of
;;   our functions
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(setq auto-mode-alist(mapcar 'purecopy                    
                 '(("\\.txt$"   . ws-text-mode)
                   ("\\.c$"         . ws-c-mode)
                   ("\\.h$"         . ws-c-mode)
                   ("\\.y$"         . ws-c-mode)
                   ("\\.hh$"        . ws-c++-mode)
                   ("\\.cc$"        . ws-c++-mode)
                   ("\\.cxx$"       . ws-c++-mode)
                   ("\\.C$"         . ws-c++-mode)
                   ("\\.cpp$"       . ws-c++-mode)                   
                   ("\\.java$"      . ws-java-mode)
                   ("\\.scm$"       . ws-scheme-mode)
                   ("\\.el$"        . ws-emacs-lisp-mode)
                   ("\\.emacs.*"    . ws-emacs-lisp-mode)
                   ("[]>:/]\\..;emacs"  . ws-emacs-lisp-mode)
                   ("\\.f$"        . ws-fortran-mode)
                   ("\\.F$"        . ws-fortran-mode)
                   ("\\.inc$"    . ws-fortran-mode)
                   ("\\.INC$"    . ws-fortran-mode)
                   ("\\.sh$"    . ws-sh-mode)
                   ("\\.mss$"    . ws-scribe-mode)
                   ("\\.m4$"     . ws-m4-mode)
                   ("\\.tex$"    . ws-latex-mode)
;;                   ("\\.tex$"    . ws-tex-mode)
;;                   ("\\.TeX$"    . ws-tex-mode)
                   ("\\.sty$"    . ws-latex-mode)
                   ("\\.bbl$"    . ws-latex-mode)
                   ("\\.sty$"    . ws-latex-mode)
                   ("\\.bbl$"    . ws-latex-mode)
                   ("\\.bib$"    . ws-text-mode)
                   ("\\.bst$"    . bibtex-style-mode)
                   ("\\.article$"    . ws-text-mode)
                   ("\\.letter$"    . ws-text-mode)
                   ("\\.texinfo$"    . ws-texinfo-mode)
                   ("\\.lsp$"       . ws-lisp-mode)
                   ("\\.lisp$"      . ws-lisp-mode)
                   ("\\.cl$"        . ws-lisp-mode)
                   ("\\.ml$"        . ws-lisp-mode)
                   ("\\.htm$"       . ws-html-helper-mode)
                   ("\\.html$"      . ws-html-helper-mode)
                   ("\\.html$"      . ws-kumac-mode)
                   ("[mM]akefile$"  . ws-makefile-mode)
                   ("[mM]akefile.am$" . ws-makefile-mode)
;;                   ("\\.m$"        . ws-matlab-mode)
                   ("\\.m$"        . ws-objc-mode)
                   ("\\.pro$"    . ws-idlwave-mode)
                   ("\\.prolog$"     . ws-prolog-mode)
                   ("\\.pr$"    . ws-prolog-mode)
                   ("\\.pl$"        . ws-perl-mode)
                   ("\\.py$"        . ws-python-mode)
                   ("\\.tcl$"       . ws-tcl-mode)
                   ("\\.gp$"        . ws-gnuplot-mode)
                   ("\\.css$"       . ws-css-mode)
                   ("^/tmp/Re"      . ws-text-mode)
                   ("^/tmp/fol/"     . ws-text-mode)
                   ("/Message[0-9];$"   . ws-text-mode)
                   ("\\.scm.[0-9];$"    . ws-scheme-mode)
                   ("\\.mortran$"       . ws-mortran-mode)
                   ("\\.macros$"        . ws-mortran-mode)
                   ("^"                 . ws-fundamental-mode))))
                   
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Interpreter list (to match the #! line in scripts)
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

;(setq interpreter-mode-alist(mapcar 'purecopy
;                  '(("" . ws-python-mode)
;                    ("^.*perl"   . ws-perl-mode))))

(setq interpreter-mode-alist
        (cons '("python" . ws-python-mode) 
        interpreter-mode-alist))


;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;; Set up autoloads -- should be OK even without these, but had trouble
;;   with html-helper and the /usr/local/share/..../site-lisp version
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

;;
;; LISP mode
;;
(autoload 'lisp-mode "~/Library/Emacs/progmodes/lisp-mode.elc" 
  "Mode for editing Lisp files." t)

;;
;; IDLwave mode
;;
(autoload 'idlwave-mode "idlwave" "IDLWAVE mode." t)
(autoload 'idlwave-shell "idlwave-shell" "Interactive IDLWAVE mode." t)

;;
;; Matlab mode -- get it from  ftp.mathworks.com
;;
(autoload 'matlab-mode "matlab" "Enter Matlab mode." t)
;(setq auto-mode-alist (cons '("\\.m\\'" . matlab-mode) auto-mode-alist))
(autoload 'matlab-shell "matlab" "Interactive Matlab mode." t)


;;
;; Python mode -- get it form http://www.python.org/emacs/
;;
(autoload 'python-mode "~/Library/Emacs/progmodes/python.elc" 
               "Mode for editing Python files." t)

;;
;; Perl mode
;;
(autoload 'perl-mode "~/Library/Emacs/progmodes/perl-mode.elc" 
                "Mode for editing Perl files." t)

;;
;; CC-mode
;;
(autoload 'cc-mode "~/Library/Emacs/progmodes/cc-mode-5.27/cc-mode.el"
              "Mode for editing C files." t)

;;
;; Fortran mode
;;
(autoload 'fortran "~/Library/Emacs/progmodes/fortran.elc" 
              "Mode for editing FORTRAN files." t)

;; Mortran
(autoload 'mortran-mode "~/Library/Emacs/progmodes/mortran.elc"
  "Mode for editing Mortran files." t)

;;
;; HTML helper mode -- get it from http://www.santafe.edu/~nelson/tools/
;;
(autoload 'html-helper-mode "~/Library/Emacs/progmodes/html-helper-mode.elc" 
           "Yay HTML major mode" t)

;;
;; CSS mode
;;
(autoload 'css-mode "~/Library/Emacs/progmodes/css-mode.elc"
  "Mode for editing CSS files." t)

;;
;; KUMAC mode -- get it from http://uther1.phy.ornl.gov/~morrison/
;;
;(autoload 'kumac-mode "kumac-mode" "Mode for editing KUMAC files." t)

;;
;;
;; End autoloads
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;

;;
;; HTML 
;;
(setq html-helper-do-write-file-hooks t)
(setq html-helper-build-new-buffer t)

;;
;; HTML -- Remember to put your own name here:
;;
(setq html-helper-address-string
      "<a href=\"http://www-personal.umich.edu/~dwchin\">David Chin</a>,
           <a href=\"mailto:dwchin@umich.edu\">dwchin@umich.edu</a>")

;;
;; HTML -- Possibly change the template for new HTML buffers.
;;
(load "set-html-buffer-template" t)  ; t = Don't complain if not in load-path

                   
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;;   Here is the start-up code that overides the startup.el supplied
;;   by the system manager
;;   Remember startup.el and etc starts up first therefore we have problems
;;   convincing emacs that it should remap all its keys into WordStar mode
;;   The problem lies in the x-mouse.el file because the
;;   mouse needs "\C-c\C-m" which WordStar takes over thus disabling the
;;   mouse in WS modes.
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(setq major-mode 'ws-mode)              ; first we give it the normal
(setq default-major-mode 'ws-mode)        ; defaults
                                        ; we need a kluge

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;
;;   The kluge starts here:
;;   To get into WordStar mode, you MUST press RETURN whenever no files 
;;   are specified on the command line
;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

(defun ws-kluge()
"Wordstar Kluge"
   (interactive) 
   (global-unset-key "\C-M")
   (ws-fundamental-mode))

(global-unset-key "\C-M")
(global-set-key "\C-M" 'ws-kluge)                          
(message "Press RET to continue")


;;
;; CC-MODE customizations
;; New cc-mode defines styles.
;; These should be in the mode-hook
;;
;(setq c-hungry-delete-key t)
;(setq c-auto-newline t)

;;
;; FORTRAN MODE customizations
;;
(setq fortran-continuation-string "&")
(setq fortran-comment-indent-style nil)

;;
;; Load a bunch of files
;;
(read-abbrev-file "~/.emacs_abbrevs")

;;
;; Start up auto-fill-mode when using text-mode, cc-mode, fortran-mode
;;
(setq-default auto-fill-hook 'do-auto-fill) ; supposed to turn on
                                            ; auto-fill for all major
                                            ; modes, but doesn't
(add-hook 'ws-mode-hook
  '(lambda ()
           (message "WS-MODE IS ON")
           (auto-fill-mode t)
           (setq column-number-mode t)
           (font-lock-fontify-buffer)
           (load-file "~/Library/Emacs/vc.elc")
           (load-file "~/Library/Emacs/vc-hooks.elc")  ; Do this since I have 
                                             ; re-mapped keys, and vc-hooks
                                             ; gets loaded from system defaults
))

;; Set RCS as VC default back-end
(setq vc-default-back-end 'rcs)


;;
;; Mode hooks here
;;
(add-hook 'diary-hook 'appt-make-list)

;(add-hook 'c-mode-common-hook 'my-c-mode-common-hook)

(add-hook 'c++-mode-common-hook
          '(lambda ()
             (c-set-style "stroustrup")))

;; QUESTION: why does using the lambda expression work, 
;; while predefining a mode-hook function doesn't?
(add-hook 'c-mode-common-hook
    '(lambda () 
             (c-toggle-auto-hungry-state 1)
             ;(c-set-style "whitesmith")
             ;(c-set-style "gnu")
             ;(c-set-style "cc-mode")
             (auto-fill-mode t) 
             (hide-ifdef-mode t)
             (abbrev-mode t)
             (show-paren-mode t)
             (setq column-number-mode t)
             (setq tab-width 4)
             (load "~/Library/Emacs/cvs-format.elc")
; ; hacked cc-mode (cc-langs.el) to do this right.
; ;             (define-key function-key-map '[backspace] 'c-electric-backspace)
; ;             (global-set-key "\C-h" 'c-electric-backspace)
; ;             (define-key function-key-map '[delete] 'delete-char)
; ;             (global-set-key "\177" 'c-electric-delete)
             ;(setq delete-key-deletes-forward t)
; I suppose I don't really like electric delete; I don't know what I was
; thinking
;             (define-key c-mode-base-map "\177" 'c-electric-delete)
             (define-key c-mode-base-map "\177" 'backward-delete-char-untabify)
             (define-key c-mode-base-map "\C-m" 'newline-and-indent)))

; Also hacked fortran.el to define "\C-;" if window-system is not nil
(add-hook 'fortran-mode-hook 
    '(lambda () 
             (fortran-auto-fill-mode 1) 
             (setq column-number-mode t)
             (abbrev-mode t)))

(add-hook 'mortran-mode-hook
          '(lambda ()
             (auto-fill-mode t)
             (setq column-number-mode t)
             (abbrev-mode t)
             (hs-minor-mode)
             (font-lock-fontify-buffer)))

(add-hook 'perl-mode-hook 
    '(lambda () 
             (auto-fill-mode t) 
             (setq column-number-mode t)
             (abbrev-mode t)))

(add-hook 'python-mode-hook 
    '(lambda () 
             (auto-fill-mode t) 
             (setq column-number-mode t)
             (abbrev-mode t)))

(add-hook 'idlwave-mode-hook
    '(lambda ()
         (idlwave-auto-fill-mode t)
         (abbrev-mode t)
         (setq idlwave-main-block-indent 4)
         (show-paren-mode t)
         ;; Pad with with 1 space (if -n is used then make the
         ;; padding a minimum of n spaces.)  The defaults use -1
         ;; instead of 1.
         (idlwave-action-and-binding "=" '(idlwave-expand-equal 1 1))
         (idlwave-action-and-binding "<" '(idlwave-surround 1 1))
         (idlwave-action-and-binding ">" '(idlwave-surround 1 1 '(?-)))
         (idlwave-action-and-binding "&" '(idlwave-surround 1 1))
         ;; Only pad after comma and with exactly 1 space
         (idlwave-action-and-binding "," '(idlwave-surround nil 1))
         ;; Create a newline, indenting the original and new line.
         ;; A similar function that does _not_ reindent the original
         ;; line is on "\C-j" (The default for emacs programming modes).
         ;(local-set-key "\n" 'idlwave-newline)
         ;(local-set-key "\C-j" 'idlwave-newline) ; My preference.
         (local-set-key "\C-m" 'idlwave-newline)
         (local-set-key "\011" 'idlwave-indent-line)
         ))

(add-hook 'lisp-mode-hook
    '(lambda ()
         (local-unset-key "\C-c")
         (local-unset-key "\C-x")
         (define-key lisp-mode-map "\C-p\C-z" 'run-lisp)))

(add-hook 'latex-mode-hook
          '(lambda ()
             (setq show-paren-mode t)
             (setq auto-fill-mode t)
             (setq font-lock-mode t)))

(add-hook 'makefile-mode-hook
    '(lambda ()
             (setq indent-tabs-mode t)
             (define-key makefile-mode-map "\C-i" 'indent-relative)
))

;;
;; MH
;; Set up mh instead of rmail for mail.
;;
;(setq mh-progs '"/bin/")
;(setq mh-lib '"/usr/lib/mh/")
;(define-key ctl-x-map "m" 'mh-rmail)
;(setq mh-clean-message-header t)
;(setq mh-invisible-headers
;      "^Received:\\|^Message-Id:\\|^Return-Path:\\|^Via:\\|^In-Reply-To:\\|\
;^Status:\\|^Mail-from:\\|Mail-System-Version:\\|^Resent-\\|^Remailed-")


;;
;; AUC-TeX
;; 
(setq TeX-auto-save t)
(setq TeX-parse-self t)
(setq-default TeX-master nil)

;;
;; Compile command -- use GNU make
;;
(setq compile-command (concat "make -k " buffer-file-name))

;;
;; Set the fill column
;;
(setq fill-column 78)

;(setq menu-bar-mode t)


(show-paren-mode t)
(auto-fill-mode t)
(font-lock-mode t)
(font-lock-fontify-buffer)

