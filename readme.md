## Тестовое задание на вакансию HTML - Верстальщик / Frontend - Разработчик ##

В данном репозитории представлены файлы, необходимые для выполнения тестового задания. Информация про тестовое задание представлена здесь

https://docs.google.com/document/d/1jROWZ4wahCxiyTja65kM6-eUUTUN-2Hpp6dm7-NtJsc/edit?usp=sharing

Чтобы получить данные по api необходимо делать get запрос на адрес

https://raw.githubusercontent.com/obvu/frontend-testcase/master/apidata.json


В `apidata.json` расположен "ответ" от api сервера для отображение информации с подключением к backend api

Все файлы в этом ответе формируются по принципу `baseApiFilesUrl + $src`, где `$src` - путь, начинающийся с `files`.

Приветствуется создание хелпера чтобы не городить копипасту


### Описание структуры ответа от API ###

`slidesInfo` - информация для слайдов на первом экране

`infoBlock` - блок информации под слайдером

`sliderBlock` - блок информации для второго слайдера
