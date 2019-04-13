# Repositories

## Table of Contents

1. [Structure](#structure)
1. [README](#readme)
   1. [Header](#header)

## Structure

```markdown
.
|   .gitattributes
|   .gitignore
|   LICENSE
|   README.md
|   {name}.sln
|
+---build
+---docs
|   \---assets
|           project-title.png
|
+---lib
+---samples
+---src
\---tests
```

- `build` - Any scripts related to building the project, this is **NOT** an output
- `docs` - Any documentation files and assets
- `lib` - Any dependencies that must be local, and cannot be instaleld from an online package manager
- `samples` - Any projects used to provide an example or demonstration
- `src` - Any projects related to the source code
- `tests` - Any projects related to testing

## Header

```markdown
![#project-title](#path-to-project-title)
![#project-badge](#link-to-project-badge)

---

#project-description
```
The `#project-title` is required to be a relative path to an project banner, based on the template provided in the Assets repository. This should be stored in the 'docs\assets\\' as 'project-title.png'. Avoid external links.


The `#project-badge` is optional. When used these should be listed one after another. 

A `#separator` must sit between the header section and the description.

A short discription about the project will follow the separator
