# Jekyll Tutorial Demo

This follows the step by step tutorial to setting up Jekyll found here: https://jekyllrb.com/docs/step-by-step/10-deployment/

To run the site after installing jekyll:
`bundle exec jekyll serve`

To run the site with live reloading:
`bundle exec jekyll serve --livereload`

To use environments (e.g. dev vs prod) use environment variables:
`JEKYLL_ENV=production bundle exec jekyll build`
Default JEKYLL_ENV is development and is available in liquid using `jekyll.environment`.

To deploy for production:
`JEKYLL_ENV=production bundle exec jekyll build`
and then copy the contents of _site to the server.

# GitHub Page

This website is deployed on the GitHub Pages and can be found here: https://wleung85.github.io/jekyll-demo/
Changes made to successfully deploy on the platform can be seen on the branch: https://github.com/wleung85/jekyll-demo/tree/gh-pages