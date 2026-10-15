# Nouam — AWS DevOps & Cloud Engineer

A responsive static portfolio site built with HTML, CSS, and vanilla JavaScript. It is designed to be served by Nginx on an AWS EC2 Linux instance.

## Preview locally

Open `index.html` in a browser, or serve the folder with any local static-file server.

## Deploy to EC2 with Nginx

1. Launch a Linux EC2 instance and allow HTTP traffic on port 80 in its security group.
2. Install and start Nginx on the instance.
3. Copy `index.html`, `styles.css`, and `script.js` into the Nginx web root (commonly `/usr/share/nginx/html/` or `/var/www/html/`, depending on the Linux distribution).
4. Visit the instance's public DNS name or IP address in a browser.

The site uses Google Fonts when a network connection is available and falls back to system fonts otherwise.

## noumankhan.bscysec@gmail.com

                    `
