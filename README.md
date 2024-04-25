    Создание образа Docker:
        docker-compose build
   
    Применение миграции:
        docker-compose exec app python manage.py migrate
    
    Запуск контейнеров:
        docker-compose up --build
