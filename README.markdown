This is a basic sinatra template I use for delploying static sites to Heroku in ~30 seconds.

Simply edit/replace `index.html` within `public`

* Create an acount in seconds at [Heroku](http://heroku.com/signup).
* Install the gem `sudo gem install heroku`.
* If you do not have an SSH key you'll need to [generate one](http://heroku.com/docs/index.html#_setting_up_ssh_public_keys) and [tell Heroku about it](http://heroku.com/docs/index.html#_manage_keys_on_heroku)
* Clone this repo 
* `cd /path/to/project`
* `heroku create [optional-app-name]` (You can rename your app with `heroku rename`)
* `git push heroku master`