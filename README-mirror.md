### How I created this hastily made mirror:

```
git clone --mirror git://anonscm.debian.org/collab-maint/nginx.git
cd nginx.git
# Create a repo for it on GitHub called nginx-debian
git push --mirror git@github.com:evertrue/nginx-debian
```

### Important Git-flow information

Then, a branch called `evertrue/dev` (the one you're looking at now!) was created starting from the `debian/1.4.6-1` tag because that was the current release in use on Ubuntu 14.04 (Trusty Tahr).
