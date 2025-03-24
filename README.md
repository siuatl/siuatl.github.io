# Easy GitHub Blog

Create a free blog hosted by GitHub without having to dig into all the configuration details.

## Easy Setup

1. Click [here](https://github.com/gringasalpastor/easy-github-blog/generate) to generate your own GitHub repository from this template. Name the repository **`github_username.github.io`** where `github_username` is **your** GitHub username.

2. In your new repository, edit the file `_config.yml`, and modify the fields with your personal information (title, email, author, description, intro, GitHub username, etc) - you can delete any field that you don't want to use or share.

3. Open your new blog - the URL should look like this - [https://gringasalpastor.github.io](https://gringasalpastor.github.io), but using **your** GitHub username instead of mine.

## Adding a New Blog Post
Just add a new markdown file in the `_posts` folder. The file name should look like `yyyy-mm-dd-title.md`. See the existing examples files.

## Local Viewing on Your Computer (Optional)
This is completely optional, but if you want to preview you blog on you local computer, you can do the following:

### One Time Setup 
1. Follow the Jekyll [installation guide](https://jekyllrb.com/docs/installation/)
2. Clone your `username.github.io` repo, and `cd` into that folder
3. `bundle install` (use `bundle update` to update)

### Render Your Blog
1. `bundle exec jekyll serve`
2. Open http://localhost:4000/

## Additional Resources (Optional)
- [Jekyll Docs](https://jekyllrb.com/docs/)
- [GitHub Pages With Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

