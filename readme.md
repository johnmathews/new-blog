# John Mathews' Blog

This is a static site rendered from markdown using the [hugo](https://gohugo.io/) static site
generator.

## Commands

### Generate blog

`hugo server -D` will build the blog pages and launch a local server at
http://localhost:1313/ . It will watch for changes and reload automatically. The
`-D` flag includes drafts

### CSS

`npm run build` will run `npx tailwindcss -i ./themes/time/static/css/main.css -o
./themes/time/static/css/style.css`. (See `/package.json`)

To watch for changes and automatically rebuild the CSS when the them is updated,
run `chokidar "themes/" -c "npm run build"` from the project root.

