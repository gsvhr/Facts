# План реализация проекта "Только факты"

**Внимание!** *Данный план является предварительным, потому что список задач, которые предстоит решить в процессе создания новой версии приложения может подвергнуться существенной переработки. По мере создания функциональности план будет пересмотрен.*

* [x] Регистрация репозитория github.com
* [x] Создание проекта и его подготовка к разработке
    * [x] Настройка логирования в log-файл
    * [x] Реализация "вход/выход" на сайте
* [x] Настройка добавления учетной записи при создании новой базы (SEED)
* [ ] Создание сущностей (классов) и конфигрурирование сущностей через fluent API (EntityTypeConfiguration)
    * [ ] Fact
    * [ ] Tag
    * [ ] Message
* [ ] Создание EF-миграции и базы данных
* [ ] Перенос данных из старой БД в новую базу данных
* [ ] Создание ViewModels для сущностей и настройка маппинга
* [ ] Шаблоны ASP.NET MVC (_Layout) и управление ими
* [ ] Страницы сайта для посетителя
    * [ ] Обновление разметки главной страницы
    * [ ] Страница "О сайте"
    * [ ] Страница "Обратная связь" (Message)
    * [ ] Реализация постраничного просмотра списка фактов на главной странице
    * [ ] Страница детального просмотра выбранного факта
* [ ] Страницы сайта для администратора
    * [ ] Страница "панель управления" (навигатор управления)
    * [ ] Реализация постраничного просмотра списка сообщений (message)
    * [ ] Страница "добавление факта"
    * [ ] Страница "редактирования факта"
    * [ ] Страница "удаления факта"
    * [ ] Страница "отправки почтового сообщения"
* [ ] BackgroundWorker по отправки почтовых писем из таблицы Messages
* [ ] Отправка почты на примере Yandex Domain EMail. Реализация IEmailService

# Дополнительно
* [ASP.NET Core MVC "Только факты" (NET5.0)](https://github.com/Calabonga/Facts/wiki)
* [О приложении](https://github.com/Calabonga/Facts/wiki/%D0%9E-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B8)
* [Цели и задачи проекта](https://github.com/Calabonga/Facts/wiki/%D0%A6%D0%B5%D0%BB%D0%B8-%D0%B8-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)
* [Затронутые аспекты](https://github.com/Calabonga/Facts/wiki/%D0%97%D0%B0%D1%82%D1%80%D0%BE%D0%BD%D1%83%D1%82%D1%8B%D0%B5-%D0%B0%D1%81%D0%BF%D0%B5%D0%BA%D1%82%D1%8B)
* [Основные функциональные возможности](https://github.com/Calabonga/Facts/wiki/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D0%B2%D0%BE%D0%B7%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
* [Пользователи сайта могут](https://github.com/Calabonga/Facts/wiki/%D0%92%D0%BE%D0%B7%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)
* [Администратор сайта может](https://github.com/Calabonga/Facts/wiki/%D0%92%D0%BE%D0%B7%D0%BC%D0%BE%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%B0%D0%B4%D0%BC%D0%B8%D0%BD%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%B0)
* [Видео материалы](https://github.com/Calabonga/Facts/wiki/%D0%92%D0%B8%D0%B4%D0%B5%D0%BE-%D0%BC%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B)
