# Practice

## Вариант 12

### Состав команды
* Кярнонен Никита
* Афанасьев Владимир
* Сарычев Иван

### Обязанности каждого участника в группе
* Кярнонен Никита - описание проекта, построение схемы взаимодействия компонентов системы и поднятие ИС.
* Афанасьев Владимир - Работа с БДУ ФСТЭК, построение модели угроз, построение модели нарушителя ИБ.
* Сарычев Иван - разработка сценариев с матрицей Mitre ATT&CK

### Описание проекта:
#### Структурные элементы проекта:

1. Сервера системного программного обеспечения (СПО):
   * DSpace - это система управления контентом с открытым исходным кодом, предназначенная для создания и управления цифровыми архивами и библиотеками. Он выполняет роль сервера СПО для хранения и управления контентом.
   * Веб-сервер (Apache) - отвечает за обработку запросов и предоставление веб-страниц пользователю.
   * Клиентское приложение Angular - это фреймворк для разработки веб-приложений. Клиентское приложение на Angular предоставляет интерфейс для пользователей цифровой библиотеки.
   * Базы данных (PostgreSQL) - хранят информацию о блоге, пользователях, комментариях и других данных.
  
2. Приложения:
   * Dspace Angular - открытое, кроссплатформенное J2EE приложение, предназначенная для долгосрочного хранения цифровых материалов, используемых в академических исследованиях.

3. СУБД:
   * СУБД (система управления базами данных) используется для хранения метаданных и другой информации, связанной с цифровой библиотекой. DSpace поддерживает различные СУБД, такие как PostgreSQL и Oracle
  
4. Прикладное программное обеспечение (ППО):
   * Прикладное программное обеспечение может включать в себя дополнительные инструменты и библиотеки, необходимые для настройки и расширения функциональности DSpace.
   * Редакторы контента, плагины и темы - позволяют добавлять новые функции и изменять внешний вид блога.
  
#### Взаимодействия структурных элементов:
1) Клиентское приложение Angular взаимодействует с сервером приложений, отправляя запросы и получая данные через HTTP-протокол. Пользователи взаимодействуют с клиентским приложением Angular (выполнять поиск, просматривать и скачивать данные)
2) Сервер приложений обслуживает клиентское приложение Angular и взаимодействует с сервером СПО DSpace для доступа к контенту библиотеки. Он будет принимать запросы от пользователей и направлять их к соответствующему функциональному модулю внутри приложения. 
3) Сервер СПО DSpace управляет хранением и предоставлением контента, а также взаимодействует с базой данных СУБД для хранения метаданных и информации о ресурсах. Клиентское приложение Angular взаимодействует с сервером СПО DSpace, отправляя запросы для получения контента и его представления пользователю.
4) Сервер СПО DSpace обеспечивает доступ к контенту и обрабатывает запросы, выполняя поиск, предоставляя доступ к хранимым научным публикациям и управляя метаданными.
5) СУБД используется сервером СПО DSpace для хранения метаданных и информации о ресурсах, позволяя выполнять поисковые запросы и обеспечивая структурированный доступ к данным.

### Описание условного места установки системы:
Система управления цифровой библиотекой, основанная на DSpace и Angular, будет установлена в медицинском учреждении, например как больница, поликлиника или медицинский центр. Это место установки имеет свои особенности, и обработка информации в таком контексте подразумевает следующие категории:

1. Персональные данные: Медицинские учреждения обрабатывают большое количество персональных данных пациентов, включая их медицинские истории, диагнозы, рецепты и контактные данные. Система цифровой библиотеки может хранить научные и медицинские публикации, связанные с лечением пациентов.
2. Коммерческая тайна: В медицинских учреждениях может храниться коммерческая информация, связанная с финансовыми операциями и разными партнерствами. Это может включать в себя соглашения с поставщиками медицинского оборудования и фармацевтическими компаниями.
3. Общедоступная информация: Некоторая информация, такая как научные исследования и клинические рекомендации, может быть предоставлена обществу в общий доступ для образовательных и исследовательских целей.

* Учитывая вышеперечисленное, система цифровой библиотеки должна быть настроена с сильной системой управления доступом и шифрованием, чтобы обеспечить конфиденциальность персональных данных и коммерческой информации.


  
   
