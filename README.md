# Swift Academy Homeworks

Настоящото **repository** е предназначено да се използва като _споделен проект_ за качване на решенията от домашните и контролните към курса по **Front-End Програмиране** на _Swift Academy_.

## Принципи на работа

### 1. Fork & Clone

 За да може да ми изпраща домашните си, всеки курсист трябва да _копира_ поекта в своя **GitHub** акаунт (**fork**), да го _изтегли_ на персоналния си компютър/лаптоп (**clone**) и да създаде в него свое _разклонение_ (**branch**).

_Копирането_ на проекта става чрез функцията **Fork** на _GitHub уебсайта_, а _изтеглянето_ му - чрез функцията **clone** на програмата _GitHub desktop_.  

_Копието_ на проекта в уебсайта на GitHub, се нарича **remote repository** или _отдалечено копие_, а това на личния компютър/лаптоп - **local repository** или _локално/работно копие_

Създаването на _разклонение_ става в програмата _GitHub desktop_, чрез менюто `Branch` - > `New Branch`.

Разклонението трябва да бъде именувано в следния формат: `ImeFamilia`. Т.е. _собствено_ и _фамилно_ име,  _на латиница_ и _без интервал_.  
_Например: `EvgeniaManolova`._

Подробна инструкция за инсталирането и _setup_-ването на програмата _GitHub desktop_ има ето [тук](https://swift-academy.zenlabs.pro/misc/GitHubTutorial.pdf)

### 2. Интеграция с Brackets и файлова организация

Всяко копие на проекта, първоначално ще бъде празно (с изклчение на файловете `README.md` и `.gitignore`). 

Необходимо е да се създаде _работна папка_, именувана по същия начин както е именуван съответният _branch_.

За да може да работи само в _своята_ папка, всеки курсист трябва да я зададе като работен проект в **Brackets** (Избира се `File` -> `Open folder`, след което намира/създава своята _рабтна папка_ в папката на клонираното репозитори (**sa-homeworks-08**))

#### При работа по домашни/упражнения/проекти, курсиста трябва да се съобразява със следните правила за именуване:

1. Всички задачи към даден _урок_ се поставят в папка, именувана спрямо номера на съответния урок: `lesson1`, `lesson2` и т.н.
1. Всяка отделна задача за _упражнение_, се решава в отделен _подпроект_ (папка), именуван: `task1`, `task2` и т.н. , а всяка такава папка се поставя в папката на съответния _урок_ (`lesson1`, `lesson2`, ...)
1. Всяка отделна задача за _домашно_, се решава в отделен _подпроект_ (папка), именуван: `hw1`, `hw2` и т.н. , а всяка такава папка се поставя в папката на съответния _урок_
1. Папките на задачите от _контролните_ се именуват: `test1`, `test2` и т.н.
1. Папката на финалния проект се именува: `project`.

_ВАЖНО: Работи се единствено в собствената папка!_

#### Пример

Когато работя по дадена _задача за упражнение_, напр. _Задача 1_ от _урок 3_, променям файловете в папката `EvgeniaManolova` -> `lesson3` -> `task1`.

Когато работя по дадена _задача за домашно_, напр. _Задача 2_ от _домашно 3_, променям файловете в папката `EvgeniaManolova` -> `lesson3` -> `hw2`.

Когато работя по дадена _задача от контролно_, напр. _Задача 1_ от _контролно 2_, променям файловете в папката `EvgeniaManolova` -> `test2` -> `task1`.


### 3. Change & commit

Всяка промяна, която направя в *Brackets*, се отразява в секцията **Changes** на *Github Desktop* програмата. Тези _промени_, са текущи (наричат се още _локални промени_) и ако преценя, че искам да ги запазя, трябва да направя **commit*.

_Commit_ на промените се прави тогава, когато е постигнат някакъв етап от решението на задачата, който си заслужава да бъде запазен, защото ще се използва като основа за по-нататъшното решение.

_Revert_ на промените се прави тогава, когато текущото решение на задачата е неправилно и единствения начин да продължим е като се върнем назад към състоянието на проекта от последния _commit_.

### 4. Pull / Fetch

Когато има _remote update_ (промени по файловете, направени от _някой друг_) в бранч-а, в който работим, трябва да използваме функцията **Pull** на програмата _GitHub desktop_, за да _изтеглим_ тези промени в нашето _работно копие_.

За да разбере дали има такива _remote промени_, програмата _GitHub desktop_ използва командата **Fetch**.

### 4. Push & Pull request

Когато дадено домашно или задача са готови за предаване, те трябва да бъдат _качени_ в _отдалеченото копие_ и да се направи _заявка за внедравяне_ (_pull request_) към _базовия проект_ или т.нар. **origin** (`zzeni/sa-homeworks-08`)

За целта първо трябва да са **cmmit**-нати всички _локални промени_ и _нови файлове_ в _локалното копие_ на проекта.

Качването на _локалните промени_ в _отдалеченото копие_ (това, което е на сайта на GitHub), става посредством функцията **Push** на програмата _GitHub desktop_.

След като бъде изпълнен **push** , всички нови файлове и промени се отразяват в _отдалеченото копие_ на съответният курсист.

Последната стъпка е да бъдат _внедрени_ тези промени в _базовото repository_ или т.нар. **origin** (`zzeni/sa-homeworks-08`).

За целта трябва да се направи **Pull request** или от уебсайта или от програмата _GitHub desktop_.