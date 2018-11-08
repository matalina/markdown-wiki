# Markdown Wiki

An SPA wiki with markdown formatting and yaml front matter meta data.

After making any changes to the wiki folder `php artisan wiki:index` must be run.

## Convention over configuration for files 
* All file and directory names should be lower case and only contain `a-z 0-9 - _`
* All files should have  `.md` extension
* You must include a `home.md` file

## YAML Front Matter
```yaml
title: Title of the Article
index: comma separated string of words that will link to this page
category: 
    - category 1
    - category 2
tags: 
    - tag 1
    - tag 2
```

# To Do List
- [ ] Create a git pull hook to run artisan indexing command

# Notes

Vue path for pages via location
```javascript
var re = pathToRegexp('/:foo/(.*)')
// keys = [{ name: 'foo', ... }, { name: 0, ... }]
```

