clojure-web-app
===============

- Clojure web application using compojure, enlive, datomic, clojurescript.
- Single project and one nrepl server for both clojure and clojure-script.
- Interactive development for both clojure and clojure-script using emacs-live-clojure-workflow. 


About application and emacs lib
-------------------------------
- Datomic for database
- Compojure for web routing
- Enlive for template
- Clojure script for dynamic UI update.
- Interactive development using emacs-live-clojure-workflow.


Start server from emacs-live
-----------------------------
- Add emacs-live module: https://github.com/Mamun/emacs-live-clojure-workflow
- Run nrepl, press F9 to start app server. press c+F9 to stop app server.
- Go http://localhost:8080/user
- Login user name and password- admin, admin


Clojure-Script repl
-------------------
- From emacs-live press F11 to open clojure script repl.
- From browser run repl.cljs() for connection. 
- For close or back to clojure repl press c+F11.



