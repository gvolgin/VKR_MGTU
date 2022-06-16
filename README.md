# Тема: Прогнозирование конечных свойств новых материалов (композиционных материалов)

## Цель исследования:
Прогностическое моделирование физических и механических свойств композитов с учетом предикторов, характеризующих свойства фаз и их распределение. 

В работе реализовано приложение для прогнозирования целевой переменной с интерфейсом командной строки. 
В процессе работы приложение существует возможность выбрать переменную для прогнозирования, входные параметры, модель машинного обучения. Последние представлены линейной регрессией, k - ближайших соседей, SVM, нейронная сеть.
Запуск приложения производится из командной строки. Код приложения и данные расположены на локальной машине по адресу: C:\Users\Георгий\VKR\MGTU.  
Определение каталога происходит при помощи команды cd. В командной строке это будет выглядеть как:
cd C:\Users\Георгий\VKR\MGTU
Выполняем запуск приложения apps_VRK.py
После старта приложения появляется предложение ввести путь до файла. 
Выполняем: C:\Users\Георгий\VKR\MGTU\data_join.xlsx
После загрузки библиотек предлагается выбрать переменную для прогнозирования.
Выбираем «Соотношение матрица - наполнитель». После чего появляется запрос на исключение переменных. 
Исключаем «Модуль упругости при растяжении, МПа», «Поверхностную плотность, г/м2». 
Завершаем нажатием клавиши N. После выбираем прогнозную модель. Подтверждаем выбор прогнозной модели (GradientBoostingRegressor), получаем расчет.
