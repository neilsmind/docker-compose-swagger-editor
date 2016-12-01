# docker-compose-swagger-editor
Run swagger editor in docker using swagger.dev (instead of localhost)

Leveraging the [nginx-proxy approach](http://neilsmind.com/2016/11/21/docker-config-on-new-macbook.html) to pow-like 
DNS name resolution, this simple docker-compose file will mount the swagger-editor app at http://swagger.dev instead
of hijacking localhost

## Usage
~~~
git clone git@github.com:neilsmind/docker-compose-swagger-editor.git swagger
cd swagger
docker-compose up
~~~
