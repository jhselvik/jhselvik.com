## jhselvik.com

[jhselvik.com](www.jhselvik.com), built with Hugo.

# Usage

Clone this repo:

    git clone https://github.com/jhselvik/jhselvik.com.git
    cd jhselvik.com

Start the Hugo server:

    ./bin/hugo-server

Open http://localhost:1313/

# Other tools

To publish static files:

    ./bin/hugo-publish
    
Files are generated into `/public`

To minify CSS/HTML/JS files in `/public` (after publish):

    ./bin/minify
    
To run an nginx container from files in `/public` (after publish):

    ./bin/nginx

## Credit

* anirbanmu's [hugo-sustain-vitae](https://github.com/anirbanmu/hugo-sustain-vitae) fork.
* jtreminio's [Setting Up a Static Site with Hugo and Push to Deploy](https://jtreminio.com/blog/setting-up-a-static-site-with-hugo-and-push-to-deploy/) post