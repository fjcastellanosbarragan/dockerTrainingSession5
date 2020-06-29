Commands:

```powershell
docker build -f "D:\development\fjbc_docker_training\code\assessment5\dockertraining_fernado_castellanos\Dockerfile" --force-rm -t dockertraining/fernando_castellanos "D:\development\fjbc_docker_training\code\assessment5"

```

```powershell
docker run -d --name Site1 -p 8085:80 dockertraining/fernando_castellanos
```

```powershell
docker run -d --name Site2 -p 8086:80 -e AppSettings:storename=Plano dockertraining/fernando_castellanos
```

```powershell
docker pull dockertraining/fernando_castellanos
```

