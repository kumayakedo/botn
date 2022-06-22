discordbot: python discordbot.py
git add .
git commit -m "Procfile"
git push heroku master
...
-----> Procfile declares process types: web, worker
       Compiled slug size is 10.4MB
-----> Launching... done
       http://strong-stone-297.herokuapp.com deployed to Heroku

To git@heroku.com:strong-stone-297.git
 * [new branch]      master -> master
heroku ps
=== web: `bundle exec rails server -p $PORT`
web.1: up for 2m

heroku logs
2011-04-26T01:24:20-07:00 heroku[slugc]: Slug compilation finished
2011-04-26T01:24:22+00:00 heroku[web.1]: Running process with command: `bundle exec rails server mongrel -p 46999`
2011-04-25T18:24:22-07:00 heroku[web.1]: State changed from created to starting
2011-04-25T18:24:29-07:00 heroku[web.1]: State changed from starting to up
2011-04-26T01:24:29+00:00 app[web.1]: => Booting Mongrel
2011-04-26T01:24:29+00:00 app[web.1]: => Rails 3.0.5 application starting in production on http://0.0.0.0:46999
2011-04-26T01:24:29+00:00 app[web.1]: => Call with -d to detach
2011-04-26T01:24:29+00:00 app[web.1]: => Ctrl-C to shutdown server
