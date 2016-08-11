Repo for customized files on kmattimo.me dokku instance
The repo lives on /
That may or not be a good idea but it seems to work well so far.... 

git init .


git remote add -t \* -f origin <repository-url>


git pull /whatever



Dokku Notes 
==========

Updated nginx to support HTTP2 

Stop first app from appearing on all subdomains: 
`ln -s /etc/nginx/sites-available/default /etc/nginx/sites-enabled/`

fix wonkiness after dokku/ubuntu upgrade:
`dokku ps:rebuildall`
