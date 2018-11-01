## HAProxy


### Directory Structure

```markdown
  | /etc/haproxy
  |- - - - |haproxy.cfg
  |- - - - |backend1
  |- - - - |backend2
  |- - - - |errors
  |        | - - - -401
  |        | - - - -404
  |        | - - - -503
  |- - - - |maps
  |        | - - - -http.map
  |        | - - - -https.map
```

Configure the backend routes using [this](https://www.haproxy.com/blog/using-haproxy-as-an-api-gateway-part-1/) extraordinary tutorial.

```markdown
    #some useful commands


    #Tail logs for HAProxy, this should be run as root
    less +F /var/log/haproxy.log



```
