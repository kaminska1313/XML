# XML
 1. Создать внешний репозиторий c названием XML.
    
          repositories->new->create repository
              
 2. Клонировать репозиторий XML на локальный компьютер.
	        
          $ git clone https://github.com/kaminska1313/XML.git

 3. Внутри локального XML создать файл “new.xml”.
		
	        $ touch new.xml

 4. Добавить файл под гит.
		
	        $ git add .
	        
 5. Закоммитить файл.
		
	        $ git commit -m "created new.xml"

 6. Отправить файл на внешний GitHub репозиторий.
		
	       $ git push
 
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
		
	        $ cat >> new.xml
	        *text here*
	        ctrl+c
	        
 8. Отправить изменения на внешний репозиторий.
		
	        $ git add .
	        $ git commit -m "edited new.xml"
	        $ git push

 9. Создать файл preferences.xml
		
	        $ touch preferences.xml

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
		
	        $ cat >> preferences.xml
	        *text here*
	        ctrl+c

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
		
	        $ touch skills.xml
	        $ cat >> skills.xml
	        *text here*
	        ctrl+c

 12. Сделать коммит в одну строку.
		
	        $ git commit -am "added 2 files"

 13. Отправить сразу 2 файла на внешний репозиторий.
		
	        $ git push

 14. На веб интерфейсе создать файл bug_report.xml.
		
	        add file->create new file

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
		
	        ->commit new file

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
		
	        bug_report.xml->edit this file
	        *text*

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
		
	        ->commit changes

 18. Синхронизировать внешний и локальный репозиторий XML
		
	        $ git pull
		
