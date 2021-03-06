# Простой тест, есть у вас CI или нет

> СЛАЙД 11

И снова у нас пруфы. На этот раз автор [Jez Humble с сайта continuousdelivery.com](https://continuousdelivery.com/foundations/continuous-integration/).

И так, вот эти три вопроса:
1. Все ли инженеры помещают свой код в основную (а не в функциональные ветки) ежедневно?
2. Запускает ли каждый коммит выполнение модульных тестов?
3. Если сборка не работает, обычно она исправляется в течение 10 минут?

Если посмотреть на последний вопрос, то могу сказать точно, в половине компаний России есть CI, вот только по статистике это 1%. Парадокс ))).

Ну а вообще я попробую подвести итоги:
* Continuous Integration - это не Jenkins, Gitlab и другие инструменты
* Прежде всего голова и практика, подходы и методология, а далее хоть молотком, хоть микроскопом
* Это нужно чтобы избежать конфликтов слияния, ценой небольшой проблемы каждый день, вместо большой в конце
* Это для коммуникации внутри команды. Да, да, да. Это помогает обмениваться кодом.

И поверьте, оно того стоит. Вы ведь не хотите услышать от вашего босса вопросы вроде:
* вот вы этот ваш Git, Jenkins и т.д. внедрили?
* вот вы тут оборудование там новое прикупили?
* так какого... теперь новая версия выходить стала дольше?

От себя. Меня как то спрашивали, как часто надо коммитить и как часто надо выполнять слияние в основную ветку (для нас это develop). Мой ответ:
* коммитить надо тогда, когда твой код что-то уже делает
* мерджить надо тогда, когда твой код ничего не ломает

Утрировано, но суть отражает.

## Почему "Цена вопроса - вся жизнь"

Помните начало? Маленькая компания, постоянная работа... так вот. В большой компании изменения - это выделить средства, нанять людей, дать им административный ресурс и устранить барьеры. В маленьких же компаниях все иначе. Ресурсы - это мы, люди - тоже мы. У нас нет барьеров, у нас есть понимание - неделя на улучшение работы = неделя за счет самого себя.

Всегда стоит вопрос: "а кто займется?". Как правило надо сначала, чтобы команда поняла и приняла изменения, прежде чем они реально начнутся. У каждого есть свои заботы и просто "неудобный момент" для изменений. Так что, всегда начинается с того, что кто-то один, поднимает руку и говорит "так больше не будет". И в этот раз "этот кто-то" был я. К тому же это изменение для меня - это не просто другая практика работы и инструменты. Это другая идеология компании, а значит другой вектор развития и движения.

Так вот, к чему я это все. Не бойтесь поднять руку и встать у руля. Поверьте, не все так сложно. В интернете полно информации, на Youtube роликов, на Infostart курсов. Этого хватит, чтобы в вашей голове было много информации. А система - она уляжется, структурируется и начнет приносить плоды.

> СЛАЙД 12

> СЛАЙД 13

<hr>

* [на главную страницу](../README.md)