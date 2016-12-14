# eva

A web framework base on tornado.

## Install:

```
pip3 install pyeva
```

## Example

Run example api server:

```
$ cd eva/example/first_api_server/
$ python3 server.py --port=8889
[I 161214 08:18:34 server:63] api server is running at 8889
```

Test example api:

```
$ curl http://127.0.0.1:8889/hello/say 
{"Hello": "World!"}
```
