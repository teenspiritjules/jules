# Page Management #

## Setup ##

Install dependencies:

    bundler install

## Usage ##

### Start Local Server ###

Start Jekyll locally:

    bundle exec jekyll serve --drafts

Access the page at [http://localhost:4000](http://localhost:4000).

### Commit and Push Changes to GitHub ###

    git status

    git diff

    # Prepare for commit
    git add --all .
    git add [path/to/file]

    # Commit
    git commit -m "[describe your commits]"

    # Push to GitHub (publish)
    git push

## References ##

- [Basics](https://help.github.com/categories/github-pages-basics)
- [Features](https://help.github.com/categories/github-pages-features)
- [Troubleshooting](https://help.github.com/categories/github-pages-troubleshooting)
- [Configuring builds](http://jekyllrb.com/docs/continuous-integration/)
- [Template Filters](http://jekyllrb.com/docs/templates/)
- [Blog Post Schema](http://schema.org/BlogPosting)
- [Blog Post Schema Example](https://gist.github.com/gregrickaby/5917114)
