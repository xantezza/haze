<p align="center">
  <a href="https://github.com/nirasu-git/DsharpBot">
    ![image](https://user-images.githubusercontent.com/74206629/118292997-dfc80100-b4e1-11eb-9435-31252ab8514f.png)
  </a>

  <h1 align="center">haze</h3>
  <p align="center">
    Бот для поиска новых знакомств и друзей <br> Discord <br> В активной разработке
    <br>
    <a href="https://github.com/nirasu-git/DsharpBot/issues/new">Баг репорт</a>
    ·
    <a href="https://github.com/nirasu-git/DsharpBot/issues/new">Предложения</a>
  </p>
</p>

***
## Содержание

- [Функции](#Функции)
  - [Функции для серверов](#Функциональность-для-серверов)
  - [Система поиска людей по тегам](#Система-поиска-людей-по-тегам)
  - [Система случайного поиска](#Система-случайного-поиска)
- [Настройка и запуск](#Настройка-и-запуск)
- [Баги и предложения](#Баги-и-предложения)

***
## Функции

**-cmds**

<img src="https://cdn.discordapp.com/attachments/836250799382069268/839987861671247913/unknown.png">

***
## Функции для серверов

Отображение **опыта** участника сервера, сам **опыт** выдается за количество слов в сообщении и за активное нахождение в войс чате.

<img src="https://cdn.discordapp.com/attachments/836898631268827217/838405114036617226/unknown.png">

Например, для использования команды **-takerole** необходимо набрать 1000 опыта

<img src="https://cdn.discordapp.com/attachments/836898631268827217/838407576559419413/unknown.png">

Если команду можно выполнить, то запускается голосование на подверждение

<img src="https://cdn.discordapp.com/attachments/836898631268827217/838408143687647252/unknown.png">

<img src="https://cdn.discordapp.com/attachments/836898631268827217/838407145157427210/unknown.png">


***
## Система поиска людей по тегам

Чтобы создать анкету в первый раз необходимо на сервере с ботом ввести команду **-cf**, после чего бот напишет вам в лс. После создания анкеты и при наличии общего с ботом сервера он инициализирует вас автоматически, то есть дальнейший поиск людей можно проводить полностью в лс с ботом

<img src="https://cdn.discordapp.com/attachments/836250799382069268/838409313131298836/unknown.png">
<img src="https://cdn.discordapp.com/attachments/836250799382069268/838408952093081610/unknown.png">

На данном этапе вы можете лайкнуть или дизлайкнуть пользователя которого вам нашел бот, в обоих случаях анкета с этим ID добавляется в "черный список" и больше вам не попадется. 

<img src="https://cdn.discordapp.com/attachments/836250799382069268/838409765792251945/unknown.png">

В случае положительной оценки бот отправит сообщение человеку создавшему анкету и запустит поиск заново

Человек которого вы оценили получит сообщение подобного характера (в том случае если он до сих пор связан с ботом общим сервером).
Добавляться к вам или нет - его выбор

<img src="https://cdn.discordapp.com/attachments/836244188629827658/838182894798372916/unknown.png">

***
## Система случайного поиска
В случае если по вашим тегам никого не нашлось - можно попытать удачу и найти человека не опираясь на них
<img src="https://cdn.discordapp.com/attachments/836250799382069268/839980292345298954/unknown.png">
## Настройка и запуск

1. Создайте [бота](https://discord.com/developers/docs/intro)
2. Добавьте бота на ваш сервер
2. Вставьте токен бота полученный от дискорда в Example.Token.cs
3. Переименуйте класс TokenExample в Token
4. Скомилируйте и запустите
5. Также вы можете <a href ="https://discord.com/api/oauth2/authorize?client_id=836223850383016006&permissions=8&scope=bot"> добавить бота на свой сервер</a>, или, если вам не нужен серверный функционал и интересны только знакомства - <a href="https://discord.gg/wP8AA5Gk"> просто добавьтесь на мой сервер, напишите -cf и пользуйтесь моим инстансом бота ^^</a>
***

## Баги и предложения

Нашли баг или есть идея? Пожалуйста, сначала поищите открытые или закрытые issues. Если вашей проблемы\идеи нет, то [создайте новый issue](https://github.com/nirasu-git/DsharpBot/issues/new).


## Лицензия

Code and documentation copyright 2021 nirasu. Code released under the [MIT LICENCE](https://github.com/nirasu-git/DsharpBot/blob/master/LICENSE).
