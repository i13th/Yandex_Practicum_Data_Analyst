# Проект дашборда на основе данных о конференциях TED

# Описание проекта.

Проект по исследованию данных о конференциях TED выполнен в рамках курса "Аналитик данных плюс" от Яндекс Практикум.

Задача – построение Дашбордов в Tableau pubic:

* История выступлений;
* Тематики выступлений;
* Авторы выступлений;
* Дашборд на свободную тему;
* Презентация дашборда.

# Исходные данные.

* tableau_project_data_1.csv
* tableau_project_data_2.csv
* tableau_project_data_3.csv
* tableau_project_event_dict.csv
* tableau_project_speakers_dict.csv

Файлы tableau_project_data_1.csv, tableau_project_data_2.csv, tableau_project_data_3.csv хранят данные выступлений.

У них одинаковая структура:

* talk_id — идентификатор выступления;
* url — ссылка на запись выступления;
* title — название выступления;
* description — краткое описание;
* film_date — дата записи выступления;
* duration — длительность в секундах;
* views — количество просмотров;
* main_tag — основная категория, к которой относится выступление;
* speaker_id — уникальный идентификатор автора выступления;
* laughter_count — количество раз, когда аудитория смеялась в ходе выступления;
* applause_count — количество раз, когда аудитория аплодировала в ходе выступления;
* language — язык, на котором велось выступление;
* event_id — уникальный идентификатор конференции.

Файл tableau_project_event_dict.csv — справочник конференций. Описание таблицы:

* conf_id — уникальный идентификатор конференции;
* event — название конференции;
* country — страна проведения конференции.

Файл tableau_project_speakers_dict.csv — справочник авторов выступления. Описание таблицы:

* author_id — уникальный идентификатор автора выступления;
* speaker_name — имя автора;
* speaker_occupation — профессиональная область автора;
* speaker_description — описание профессиональной деятельности автора.

# Ссылка на проект.

[Проект дашборда на основе данных о конференциях TED](https://github.com/i13th/Yandex_Practicum_Data_Analyst/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82_Tableau_12%3A%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%D0%B0%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%BE%20%D0%BA%D0%BE%D0%BD%D1%84%D0%B5%D1%80%D0%B5%D0%BD%D1%86%D0%B8%D1%8F%D1%85%20TED/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%D0%B0%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%BE%20%D0%BA%D0%BE%D0%BD%D1%84%D0%B5%D1%80%D0%B5%D0%BD%D1%86%D0%B8%D1%8F%D1%85%20TED.ipynb)

[Дашборд](https://public.tableau.com/app/profile/roman.ivashov/viz/TED_tableau/sheet22?publish=yes)
