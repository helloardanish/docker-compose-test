# Docker compose yaml file to run single mongodb with mongo-express

Here two services are running using docker compose.

-- compose1.yaml and compose2.yaml not working

```
To run:

docker-compose up

to run in detached mode:

docker-compose up


To down:

docker-compose down

it will not only stop but also remove the service
```

![running_command](media/001.png)

### Accessing on local

Step 1:
Enter the credentials:

By default it is admin:pass
![credentials](media/003.png)

which can be seen while starting services:
![basic_auth](media/004.png)

Step 2:
Now you have access to db:

![db](media/002.png)

a-r collection is created manully from UI.

#### Happy coding,
## A R