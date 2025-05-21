```
docker compose up --build
```

### Работа в php-cli
Заходим в контейнер с php-cli:
>docker compose exec php-cli bash

Обновляем конфиг после его изменения:
```
php artisan config:clear
```

Создаем модель:
```
php artisan make:model Employee
```

Создаем файл миграции:
```
php artisan make:migration create_employees_table

php artisan make:migration employees_add_first_name
```

Выполнение миграций:
```
php artisan migrate
```

![img1](https://github.com/user-attachments/assets/f767ab33-b5fd-42d6-9f87-6e04cff647e7)

![img2](https://github.com/user-attachments/assets/15e4f42d-7b2c-4acc-b18c-75e33a13a953)

![img3](https://github.com/user-attachments/assets/e7cd8eab-22e1-4cdb-877d-8c5030254189)
