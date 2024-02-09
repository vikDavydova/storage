## Начало работы с React приложением

Для выполнения на вашем устройстве должны присутствовать следующие зависимости:
- Node.js версии v16.20.1 , можно новее, но во время разработки я использовал именно её (https://nodejs.org/en).

После утсановки Node.js копируем репозиторий.
Далее в командной строке пишем команду 'npm install', которая установит все необходимые пакеты и библиотеки.

После этого идёт подготовка бэка, переходим в директорию /server и опять запускаем 'npm install'.
Собирать и Запускать приложение.

## Доступные скрипты

Основные использующееся скрыпты, которые вам нужны для запуска:

### `npm run build`

Создает приложение для производства в build папку.
Он правильно объединяет React и оптимизирует сборку для достижения наилучшей производительности.

Сборка минимизирована, а имена файлов включают хэши.
Ваше приложение готово к развертыванию!

При совершении изменений в коде, нужно опять пересобрать приложение и запустить скриптом ниже.

### `npm start`

Запускает приложение в режиме разработки.
Откройте http://localhost:3000 , чтобы просмотреть его в браузере.
В случае занятого порта в консоли будет выведена другая ссылка на сайт.

Эту же команду запускаем в директории /server, чтобы запустить и его, он работает только на локальной машине.