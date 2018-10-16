# OFN-install questions

## Add env vars

Make it available for unicorn by adding the env var to
roles/webserver/templates/unicorn.service.j2 so that next time it will pick it
up.

Then, you might need to make the env var available for all processes in the
server. To do that, add it in roles/unicorn_user/templates/defaults.j2.


## Secrets.yml!

* What's it for?
* How it works
* -e argument
