# Perpicaz Blog Stuff

This is the [Perpicaz's](https://perspicazsite.wordpress.com) official repository. Some posts are missing from here because I use WordPress' editor sometimes for very simple and short posts.

I use [Org2Blog](https://github.com/punchagan/org2blog) to make posts on WordPress and my current configuration is:

```lisp
(setq org2blog/wp-blog-alist
      '(
        ("perspicaz"
         :url "https://perspicazsite.wordpress.com/xmlrpc.php"
         :username "perspicazsite"
         :default-title nil
         :default-categories nil
         :tags-as-categories t)))
(setq org2blog/wp-buffer-template
"#+DATE: %s
#+TITLE: %s
#+DESCRIPTION:
#+PERMALINK:
#+PARENT:
#+TAGS:\n")
(setq org2blog/wp-show-post-in-browser nil)
```





