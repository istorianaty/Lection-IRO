# Lection-IRO · методическая лаборатория «История на Ты»

В репозитории сохраняется шестичасовая программа «Преподавание сложных тем». Для новой четырёхчасовой лекции подготовлена отдельная Git-ветвь:

**`methodical-lab-4h` — «Современный урок истории и обществоведения»**.

Ветка создаётся от `main` и содержит полный сайт: исходную шестичасовую программу, обновлённую ссылку в основном меню и отдельную страницу `lecture/` с материалами четырёхчасовой лекции-практикума.

## Состав ветки

- `index.html` — основная шестичасовая программа; исходная логика интерактивов и рефлексии сохранена, добавлена ссылка «Лекция · 4 ч».
- `lecture/index.html` — самостоятельная страница четырёхчасовой методической лаборатории.
- `.nojekyll` — служебный файл GitHub Pages.
- `README.md` — описание ветки и публикации.
- `CHECKLIST.txt` — проверка после публикации.
- `CHANGELOG.md` — список изменений.

## Публикация ветки

1. Создать ветку `methodical-lab-4h` от актуальной `main`.
2. Добавить в неё файлы и папку из этой выгрузки, сохранив структуру.
3. Проверить diff: основная шестичасовая программа не должна потерять разделы, задания, мобильное меню и рефлексию.
4. Если нужно опубликовать новую версию сайта по прежнему адресу, открыть **Settings → Pages** и выбрать **Deploy from a branch → `methodical-lab-4h` → `/ (root)`**.
5. После публикации проверить `https://istorianaty.github.io/Lection-IRO/` и `https://istorianaty.github.io/Lection-IRO/lecture/`.

Переключение источника GitHub Pages меняет публикуемую версию сайта, но не удаляет и не перезаписывает ветку `main`. Если пока нужна только отдельная Git-ветка для проверки, настройки Pages менять не требуется.

## Материалы четырёхчасовой лекции

- Обновлённая презентация лекции (PPTX): https://drive.google.com/file/d/14ie_q9IJDUT10lqwNYzB53tFiiok9g3C/view?usp=drivesdk
- Рабочий лист участника (DOCX): https://docs.google.com/document/d/1TZg4veDGA0DHOgNYHM3e9rILhLlAEKJp/edit
- Презентация по А. А. Корзюку (PPTX): https://docs.google.com/presentation/d/1AIluJ40KAVmeQh5fga6eAFodmq1Dlgm1/edit
- Конструктор приёмов А. А. Гина (PDF): https://drive.google.com/file/d/10dzkDG5XTy3upwQiF6lr6XFtckKJ2GCJ/view
- Методический конструктор Свентуховской и Юзвук (PDF): https://drive.google.com/file/d/1FwgDKfPcW-nn512h3Ww7cDhZWqHuLXpX/view
- Функциональный урок истории и обществоведения (PDF): https://drive.google.com/file/d/1a5lIkKFTdkgGykvJiZRzIAje-pb7tf9u/view
- Технологическая карта функционального урока (PDF): https://drive.google.com/file/d/1Q1078XxY1C9Ji0X8eduzDrEuL0SK83_c/view
- Памятки анализа и самоанализа урока (PDF): https://drive.google.com/file/d/14r4Nj54MeASxCBXEwClzPbEJXXQu0ngU/view
- Папка всех материалов: https://drive.google.com/drive/folders/1SfieBLQ4-m4u7o4XaB6UvmYNEwFx25LM

Кейсы страницы используют исходный конспект открытого урока по обществоведению и материалы по истории Гомеля. Сами документы открываются по ссылкам внутри `lecture/index.html`.

## Сохранность исходного курса

- Существующий шестичасовой курс сохранён.
- Google Apps Script и схема отправки рефлексии не изменялись.
- Данные рефлексии по-прежнему не требуют ФИО и email.
- Все крупные учебные материалы остаются в Google Drive; в GitHub размещается только сайт и ссылки.
