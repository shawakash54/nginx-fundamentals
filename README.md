### Nginx

#### Linux
    To install nginx from its repository

    Add the following lines to 

    ```
    javascript vim /etc/yum.repos.d/nginx.repo
    ```

    ```
    [Nginx]
    name=”Nginx Repository”
    baseurl=”http://nginx.org/packages/centos/7/$basearc”
    gpgcheck=0
    enabled=1
    ```
    basearc specifies if our system is 32 or 64 bit.

    yum -y install nginx


#### MacOS:
	```
    brew install nginx
    ```

    To start nginx:
        ```
        sudo nginx 
        ````
    Config directory:
        ```
        /usr/local/etc/nginx/nginx.conf
        ```
    To stop nginx:
        ```
        sudo nginx -s stop
        ```
