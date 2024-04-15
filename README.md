# Go Simple Main

![alt text](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*HtCjHzGwf6iWNqXu5Cndsg.png)
this project is focusing on gitlab CI, You could also use it as <br > a template to initiate your projects

## Requirements

* docker
    * docker-compose

## Dependencies

* Gin-Gonic

## Usage

```bash
docker build --tag go_simple_main:1.0.0 .
docker run -p 8080:8080 go_simple_main:1.0.0
OR
docker-compose up -d
```

## You could also test it by doing:

```bash
curl -X GET http://127.0.0.1:8080/ping
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.