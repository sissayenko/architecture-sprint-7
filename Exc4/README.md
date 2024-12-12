# architecture-sprint-7-Exc4

## Последовательность комманд

Создание неймспейсов
```
namespaces.cmd
```

Создание пользователей
```
users.cmd
```

Создание ролей
```
kubectl create -f .\roles.yaml
```

Привязка ролей к пользователям
```
kubectl create -f .\rolesBindings.yaml
```
