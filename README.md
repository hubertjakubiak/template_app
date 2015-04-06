This is a template application for starting a Ruby on Rails project

Some items included:
- Bootstrap-sass
- A default pages controller with home action which is root with a jumbotron
- Gem's grouped by dev and prod, ready for deploy to heroku
- Navigation, footer partials
- Messages partial to enable flash display
- Gitignore file updated to exclude cloud env specific files along with db files

To use:
- Clone the repo to your local dev env
- Remove link to current origin by issuing git remote rm origin
- Bundle install --without production (to avoid installing prod gems locally)
- Rake db:migrate
- Run rails server to ensure everything's working
- Ctrl-c to shutdown server 
- Create your own github repo
- Set origin to your own repo and push up code to repo
