https://devcenter.heroku.com/articles/static-sites-ruby

First, install locally.  From within your project root:

    bundle install

Then, to test locally, from within your ``site`` directory, run:

    rackup

... and open the URL in your browser.  Some changes may require that you stop and restart the server &mdash; just use ``Ctrl-C`` and then ``rackup`` again to do that.

Once things look good locally, commit and push to Heroku:

    git commit -am "Did something awesome"
    git push heroku master

Yay!