Вспоминаю Fiddler.
Обновляем актуальную версию c официального сайта https://www.telerik.com/fiddler/fiddler-classic. Запускаем. Обнаруживаем перечень запросов.

<img src="https://github.com/francehunter/Fiddler-learning/blob/main/perfwats.png" width="200" height="100">

Видим, что десктоп регулярно спамит репорты. Открываем таск менеджер, находим perfwatson и открываем путь к приложению. Оказываемся в VisualStudio. Оказывается, что в среде по умолчанию стоит галочка в стиле "отправлять отчет о производительности". Отключаем. Старт студии с HDD ускорятся на 10 секунд.
