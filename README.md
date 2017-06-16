# SYNOPSIS

Run [6blog](https://github.com/szabgab/6blog) in docker container.

# USAGE

    $ git clone https://github.com/melezhik/6blog-docker-sparrowdo.git

    $ cd 6blog-docker-sparrowdo

    $ docker build  -t 6blog .

    $ docker run -d -p 3001:3000 6blog

    $ curl 127.0.0.1:3000 # so on, follow 6blog documentation for the blog6 API


# Author

Alexey Melezhik

# See also

[alpine-perl6](https://github.com/JJ/alpine-perl6) - base docker image 
