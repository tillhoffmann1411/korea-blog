# korea-blog
This is a blog for my semester abroad in south korea.

# Building your site locally
1. Open Terminal.
2. Navigate to the publishing source for your site. For more information about publishing sources, see "About GitHub Pages."
3. Run `bundle install`.
4. Run your Jekyll site locally.
```
  $ bundle exec jekyll serve
  > Configuration file: /Users/octocat/my-site/_config.yml
  >            Source: /Users/octocat/my-site
  >       Destination: /Users/octocat/my-site/_site
  > Incremental build: disabled. Enable with --incremental
  >      Generating...
  >                    done in 0.309 seconds.
  > Auto-regeneration: enabled for '/Users/octocat/my-site'
  > Configuration file: /Users/octocat/my-site/_config.yml
  >    Server address: http://127.0.0.1:4000/
  >  Server running... press ctrl-c to stop.
5. For production build use `JEKYLL_ENV=production bundle exec jekyll build`
```
To preview your site, in your web browser, navigate to `http://localhost:4000`.