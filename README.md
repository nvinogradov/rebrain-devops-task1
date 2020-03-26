# Default config file for [Nginx](https://nginx.org) web-server

In this repository you can see the best default config for the best web server 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
You need to install nginx web server for use this config. Use follow commands for different OS:

Debian\Ubuntu
```
sudo apt-get install nginx
```

RHEL\CentOS
```
sudo yum install nginx
```

### Installing

Before install this config, please backup your nginx config
```
sudo cp /etc/nginx/nginx.conf /etc/nginx/nginx.conf_bak
```

Copy this config to nginx config directory

```
sudo cp -f nginx.conf /etc/nginx/nginx.conf
```

## Testing

For test nginx configuration use command:
```
sudo nginx -t
```
If configuration is correct, you will see this output:
```
nginx: the configuration file /etc/nginx/nginx.conf syntax is ok
nginx: configuration file /etc/nginx/nginx.conf test is successful
```

## Contributing
For contributing please create a pull request.

## Versioning
For the versions available, see the [tags on this repository](https://gitlab.rebrainme.com/xskillx_at_gmail_com/rebrain-devops-task1/-/tags). 

## Authors

* **Nikolay Vinogradov** - [gitlab](https://gitlab.rebrainme.com/xskillx_at_gmail_com)

See also the list of [contributors](https://gitlab.rebrainme.com/xskillx_at_gmail_com/rebrain-devops-task1/-/graphs/master) who participated in this project.
