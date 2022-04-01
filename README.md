# Spaceship-Titanic-challange

Выполнение соревнования по машинному обучению на классификацию.

## Формулировка задачи

Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

Variable	Definition			Key
survival	Survival			0 = No, 1 = Yes
pclass		Ticket class			1 = 1st, 2 = 2nd, 3 = 3rd
sex		Sex	
Age		Age in years	
sibsp		# of siblings / spouses aboard the Titanic	
parch		# of parents / children aboard the Titanic	
ticket		Ticket number	
fare		Passenger fare	
cabin		Cabin number	
embarked	Port of Embarkation		C = Cherbourg, Q = Queenstown, S = Southampton

Variable Notes
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

Используется python и датасет `train.csv`.

## Установка зависимостей

Предполагается, что на вашей машине установлен [python v3](https://www.python.org/downloads/) и [git](https://git-scm.com/downloads). 

Требуется установить дополнительные пакеты python:

```
pip install jupyterlab pandas sklearn xgboost
```

## Клонирование репозитория

Клонировать репозиторий командой:

```
git clone https://github.com/mihaluck/ml-Titanic-challange.git
```

## Запуск проекта

В папке проеката выполнить команду: 

```
jupyter lab
```

В открывшенся окне jupyterlab внутри браузера выбрать файл `ML spaceship Titanic task` и запустить его.

