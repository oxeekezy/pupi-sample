#Подготовка проекта к загрузке на PYPI

##Установка необходимых зависимостей

1.Выполните установку setuptools:

``pip install setuptools``

2.Выполните команду установки wheel:

``pip install wheel``

3.Выполните команду установки twine:

``pip install twine``


##Заполнение информации
1. Заполните файл лицензии ``LICENSE`` - укажите год и автора. 
2. Заполните файл ``requirements`` библиотеками, необходимыми для данного пакета.
3. Удалите все содержимое ``README`` и заполните его в соответствии со своим проектом
4. Заполните информацию в файле ``setup.py``


##Подготовка дистрибутивов

1.Выполните команду создания дистрибутивов

``python setup.py sdist bdist_wheel``

2.Загрузите дистрибутив на PYPI:
``twine upload dist/*``

Далее будет предложено ввести данные учетной записи и процесс загрузки начнется!


После удачного выполнения всех шагов вы загрузите свою первую библиотеку на PYPI.

