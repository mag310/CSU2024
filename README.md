# Учебный проект для ЧелГУ 

Перед началом работы из дома с нормальным интернетом выполните команды ниже:

```bash
# Клонирование и переход в директорию
> git clone https://github.com/mag310/CSU2024 CSU2025
> cd CSU2025

# Сборка и запуск
> docker-compose build
> docker-compose up -d

# Проверка
> curl http://localhost:8080

# Удаление оригинального git и инициализация нового
> rm -rf ./.git
> git init

# Изменяем README, вписывая в него свою группу
> nano README.md

# Добавление файлов и коммит
> git add .
> git commit -m "Init commit"

# Добавление remote (замените URL на ваш новый репозиторий)
> git remote add origin https://github.com/yourusername/your-new-repo.git
> git branch -M main
> git push -u origin main
```
