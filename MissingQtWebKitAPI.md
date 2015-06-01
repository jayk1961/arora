  1. ~~Reload without cache~~
    * https://bugs.webkit.org/show_bug.cgi?id=26968
    * http://trac.webkit.org/changeset/45992
  1. ~~Get the original request from QWebFrame/QWebPage~~
    * https://bugs.webkit.org/show_bug.cgi?id=25867
    * http://trac.webkit.org/changeset/46364
  1. ~~Get the WebKit version~~
    * https://bugs.webkit.org/show_bug.cgi?id=27158
    * http://trac.webkit.org/changeset/46485
  1. ~~Plugin database API~~
    * Get a list of installed plugins
    * Allow to disable particular plugins
    * When there are two plugins that support the same MIME type, allow to specify which should be used
    * https://bugs.webkit.org/show_bug.cgi?id=27651
    * http://trac.webkit.org/changeset/46762
  1. QWebPage `*`QWebPage::inspect(QPoint &point); (i.e. get a pointer to the QWebView containing the inspector to do what safari does and embed the inspector inside the browser)
  1. Better icon database
  1. A working offline storage database api
  1. Event listener on QWebElement
  1. A way to modify the QNetworkRequest before it is sent to QNetworkAccessManager (Maybe via QWebPage extensions?).  Today you can do it via a QNetworkAccessManagerProxy, but that is very much a hack.