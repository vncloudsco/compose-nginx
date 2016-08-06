# Nginx letsencrypt

This is an opinionated improvisation to get a self-encrypting load balancer in front of Docker containers.

```
git clone https://github.com/indiehosters/nginx
cd nginx
docker-compose up
```

And profit \o/ `docker run -e VIRTUAL_HOST=example.org nginx`

## License

Licensed by [almereyda](https://almereyda.de/) under the GNU General Public License 3.0. See the LICENSE for its terms.
