# GitHub_HW_2
1. На локальном репозитории сделать ветки для:
- Postman
`git checkout -b Postman`
или 
`git branch Postman`
- Jmeter
`git checkout -b Jmeter`
или
`git branch Jmeter`
- CheckLists
`git checkout -b CheckLists`
или
`git branch CheckLists`
- Bag Reports
`git checkout -b Bug_Reports`
или 
`git branch Bug_Reports`
- SQL
`git checkout -b SQL`
или 
`git branch SQL`
- Charles
`git checkout -b Charles`
или 
`git branch Charles`
- Mobile testing
`git checkout -b Mobile_testing`
или 
`git branch Mobile_testing`

=====

2. Запушить все ветки на внешний репозиторий
`git push -u origin --all`
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
Переходим в ветку Bug_Reports:
`git checkout Bug_Reports `
Создаем текстовый файл:
`touch Bag_Report_Structure.txt`  
`vi Bag_Report_Structure.txt`
Нажать "i" для ввода данных.
Ввести данные.
Нажать "Esc" и ввести для выхода из редактора
`:wq`
4. Запушить структуру багрепорта на внешний репозиторий
`git add .; git commit -m 'add structure of bug report' ; git push`
5. Вмержить ветку Bag Reports в Main
`git checkout main; git merge Bug_Reports`
6. Запушить main на внешний репозиторий.
`git push`
7. В ветке CheckLists набросать структуру чек листа.
Переход в ветку CheckLists
`git branch -m CheckLists`
Создать текстовый файл 
`touch CheckListStructure.txt`
`vi CheckListStructure.txt`
Нажать "i" для ввода данных.
Ввести данные.
Нажать "Esc" и ввести для выхода из редактора
`:wq`
8. Запушить структуру на внешний репозиторий
`git add .; git commit -m 'add structure of Check ListS' ; git push`
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Зайти во внешний репозиторий CheckLists.
Нажать появившуюся кнопку "Compare & pull request" -- Ввести сообщение с произведенными изменениями -- 
Нажать кнопку "Create pull request"  -- На открывшейся странице Нажать "Merge pull request"
11. Синхронизировать Внешнюю и Локальную ветки Main
`git pull`
