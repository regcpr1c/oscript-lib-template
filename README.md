# oscript-lib-template
Шаблон-заготовка для библиотеки на OneScript

## Требования к хорошей библиотеке на OneScript

+ библиотека общедоступна на гитхабе
+ есть `readme.md`
+ задан краткий заголовок на гитхабе
+ есть файл лицензии `LICENSE`
+ есть файл packagedef
+ есть автоматическое тестирование
  + автоматические тесты для пакета 1testrunner
  + фичи проверки поведения для пакета 1bdd
+ есть файлы для автоматического выполнения CI
  + или `Jenkinsfile`
  + или `travis.yml`, если не используется 1С
  + или `ppveyor.yml`, если не используется 1С
+ изменения принимаются через issue или pull-request
+ используются публичные релизы в разделе релизов гитхаба
