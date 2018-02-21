# url-magic

These are some changes to the [README](https://github.com/simontaite/url-magic/blob/master/README.md) file

The pull request for these changes can be found at https://github.com/simontaite/url-magic/pull/1

If we change the url by adding `.diff` to the end we get the diff of the changes

Similarly, we change the url by adding `.patch` to the end we get a patch of the changes which can be applied as usual via `git apply`

You can test a pull request locally by `curl`ing the file, making sure to follow redirects

```sh
$ curl -L https://github.com/simontaite/url-magic/pull/1.patch | git apply -v
```

### Sample diff
```
diff --git a/README.md b/README.md
index 7c4517f..eb5b074 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,47 @@
-# url-magic
\ No newline at end of file
+# url-magic
+
+These are some changes to the [README](https://github.com/simontaite/url-magic/blob/master/README.md) file
+
+The pull request for these changes can be found at https://github.com/simontaite/url-magic/pull/1
+
+If we change the url by adding `.diff` to the end we get the diff of the changes
+
+Similarly, we change the url by adding `.patch` to the end we get a patch of the changes which can be applied as usual via `git apply`
+
+You can test a pull request locally by `curl`ing the file, making sure to follow redirects
+
+```sh
+$ curl -L https://github.com/simontaite/url-magic/pull/1.patch | git apply -v
+```
+
+### Sample diff
+```
+ {recursion, noun. See 'recursion.' In order to understand recursion, you must first understand recursion. }}
+```

```
