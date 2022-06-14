# Git_TXT
TXT

 1. Создать внешний репозиторий c названием TXT.

Git_TXT

 2. Клонировать репозиторий TXT на локальный компьютер.
git clone https://github.com/svetylka/Git_TXT.git
 3. Внутри локального TXT создать файл “new.txt”.
Touch new.txt
 4. Добавить файл под гит.
git add new.txt
 5. Закоммитить файл.
git commit -m "add first file"
 6. Отправить файл на внешний GitHub репозиторий.
git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
cat >> new.txt
Full name: Tyrchina Svetlna
Age: 30
Number of pets : 2
Future desired salary: 100000
 8. Отправить изменения на внешний репозиторий.
 git add .
 git status
git commit -m "changes txt file"
git push
 9. Создать файл preferences.txt
touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
cat >> preferences.txt
favorite movie: "Призрак
favourite TV show: "Ангелы и демоны
favourite time of year: "Лето
 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
cat >> skills.txt
Linux
Bash
Git
GitHub
API
HTTP/HTTPS
Web testing
Mobile testing
Proxy
VPN
SQL
JMeter
 12. Сделать коммит в одну строку.
git status 
git add .
git add . ; git commit -m "add skills and preferences"
 13. Отправить сразу 2 файла на внешний репозиторий.
git push
 14. На веб интерфейсе создать файл bug_report.txt.
Создали файл в GitHab bug_report.txt
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Файл bug_report.txt закомитили GitHab
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Модифицировали в GitHab файл bug_report.txt
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сделали коммит bug_report.txt
 18. Синхронизировать внешний и локальный репозиторий TXT
git fetch
git pull
