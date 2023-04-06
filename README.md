```
sudo docker run -d  --name redis-stack -p 6379:6379 -p 8001:8001 redis/redis-stack:latest
```

```
sudo docker exec -it redis-stack redis-cli
```

- CRUD Product using Redis as Database
