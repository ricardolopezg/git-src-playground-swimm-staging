---
title: Doc for nesting
---
Nest the doc in a folder.

<SwmSnippet path="/my_builtin/add.c" line="464">

---

&nbsp;

```c
		if (add_file_to_index(&the_index, dir->entries[i]->name, flags)) {
			if (!ignore_add_errors)
				die(_("adding files failed"));
			exit_status = 1;
		} else {
			check_embedded_repo(dir->entries[i]->name);
```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBZ2l0LXNyYy1wbGF5Z3JvdW5kJTNBJTNBT21lclJvc2VuYmF1bQ==" repo-name="git-src-playground"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
