# final-project-yandex
Описание проекта  Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
Проект: Телеком

Оператор предоставляет два основных типа услуг:

Стационарную телефонную связь. Возможно подключение телефонного аппарата к нескольким линиям одновременно.
Интернет. Подключение может быть двух типов: через телефонную линию (DSL, от англ. digital subscriber line, «цифровая абонентская линия») или оптоволоконный кабель (Fiber optic).
Также доступны такие услуги:

Интернет-безопасность: антивирус (DeviceProtection) и блокировка небезопасных сайтов (OnlineSecurity);
Выделенная линия технической поддержки (TechSupport);
Облачное хранилище файлов для резервного копирования данных (OnlineBackup);
Стриминговое телевидение (StreamingTV) и каталог фильмов (StreamingMovies).
Стриминговое телевидение (StreamingTV) и каталог фильмов (StreamingMovies).

Цель

Необходимо научиться прогнозировать отток клиентов.

Для успешного достижения цели, необходимо выполнить следующие задачи:

Загрузить и осмотреть данные;
Подготовить данные;
Исследовать модели разны алгоритмов;
Выбрать и протестировать одну лучшую модель;
Подготовить отчёт для заказчика.
Описание данных:

Данные состоят из файлов, полученных из разных источников:

/datasets/contract_new.csv — информация о договоре;
/datasets/personal_new.csv — персональные данные клиента;
/datasets/internet_new.csv — информация об интернет-услугах;
/datasets/phone_new.csv — информация об услугах телефонии.

Во всех файлах столбец customerID содержит код клиента.
Информация о договорах актуальна на 1 февраля 2020.

Признаки:

BeginDate – дата начала пользования услугами;
EndDate – дата окончания пользования услугами;
Type – тип оплаты: ежемесячный, годовой и т.д.;
PaperlessBilling – электронный платёжный документ;
PaymentMethod – способ оплаты;
MonthlyCharges – ежемесячные траты на услуги по договору;
TotalCharges – всего потрачено денег на услуги;
Dependents – наличие иждивенцев;
Senior Citizen – наличие пенсионного статуса по возрасту;
Partner – наличие супруга(и);
MultipleLines – наличие возможности ведения параллельных линий во время звонка.
Целевой признак:

Необходимо сформировать самостоятельно с помощью EndDate.
Используемые библиотеки:

Pandas
NumPy
Matplotlib
os
Datetime
phik
SciPy
Sklearn
LightGBM
CatBoost
