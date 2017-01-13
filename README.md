# schema-theme

Docu for tables, columns, etc.; see a live demo @
[`schemadoc.github.io/schema-theme`](https://schemadoc.github.io/schema-theme)


## Usage

### Step 1:  Add your database schemata and configure your site settings

Replace the `database.json` sample in the `_data` folder with your own and
change the `site.title` settings in `_config.yml` to
match your own e.g.:

```
title: 'Your Database Schema'
```

### Step 2: Let Jekyll (or GitHub Pages) do the rest

Let Jekyll (or GitHub Pages) auto-generate your static site, that is, database schema docu:

- For "classic" Jekyll => Run the build command e.g. `$ jekyll build`.

- For GitHub Pages => Commit your changes to get your docu automagically re-generated.



## License

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The schema scripts and templates are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.
