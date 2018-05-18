# Service Worker Demo

This is a very basic Service Worker Demo based on https://developers.google.com/web/fundamentals/primers/service-workers/

* To run up the http server run the following command `docker build  -t sw . && docker run -p 80:80 -i sw`
* To see that the service work is registered go to: chrome://inspect/#service-workers

If you run up the Docker container and navigate to http://localhost you should be able to `ctrl-c` the Docker container and the links will still work.