# my_devops_course

1. Склонувати репозиторій на локальний ПК. Новостворений репозиторій повинен містити файл README.md . У даному файлі потрібно розписати яку команду використовували при копіюванні ропозиторію (використовуйте MarkDown формат).

$ git clone https://github.com/viktoriiacherevan/my_devops_course.git

3. Визначити під яким хешем був здійснений даний коміт (перегляньте логи). Запишіть команду та хеш поперднього коміту у файл README.md та закомітьте його. Перевірте зміни у Вашому репозиторію через Web версію GitHub. Переконайтесь що внесені Вами зміни коректно відображаються на головній сторінці репозиторію. Перейдіть на вкладку commit та перевірте як виглядають Ваші зміни. Не забувайте про вигляд повідомлення коміту, яке повинно містити номер лабораторної роботи.

$ git log

commit 1ac87570a714ab60921a1d1653852ee5e6d520a1 
commit caa1f97e3e04a7fda26618d2281a965cc947b4c5

4. Створіть відгалуження/гілку (branch) та перейдіть з поточної master на новостворену. Будучи на новій гілці внесіть зміни у файл README.md та вкажіть які команди викоритовувались для створення та переключення між гілками. Зробіть коміт з новими змінами.

$ git branch vitka
$ git checkout vitka



