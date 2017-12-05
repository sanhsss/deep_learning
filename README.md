# Лабораторная работа №1

Выполнил:
 - Рой Виктор
 - ННГУ, ф-т ИТММ, каф. МО ЭВМ, группа 381603м4

## Задание
 - Изучить метод обратного распространения ошибки;
 - Вывести математические формулы для вычисления градиентов функции ошибки по параметрам
нейронной сети и формул коррекции весов;
 - Спроектировать и разработать программную реализацию;
 - Подготовить отчет по проделанной работе. 
 
## Запуск решения
 - Установить python3 c библиотекой Numpy;
 - Запустить файл main.py с аргументами 
 	- '-h' помощь 
 	- '-n' количество тренировочных изображений
 	- '-t' количество тестовых изображений
 	- '-s' количество скрытых слоев
 	- '-l' скорость обучения

Пример запуска: python main.py -n 10000 -t 1000 -s 200 -l 0.005

## Метод обратноого распространения ошибки
$$E=-\sum_{j=1}^{N_o}t_jlog(y_j) = -\sum_{j=1}^{N_o}t_jlog(f(\sum_{s=1}^{N_s}w_s_jf(\sum_{i=1}^{N_i}w_i_sx_i)))$$
![img](http://latex.codecogs.com/svg.latex?%24%24E%3D-%5Csum_%7Bj%3D1%7D%5E%7BN_o%7Dt_jlog%28y_j%29+%3D+-%5Csum_%7Bj%3D1%7D%5E%7BN_o%7Dt_jlog%28f%28%5Csum_%7Bs%3D1%7D%5E%7BN_s%7Dw_s_jf%28%5Csum_%7Bi%3D1%7D%5E%7BN_i%7Dw_i_sx_i%29%29%29%24%24)
![equation](http://latex.codecogs.com/gif.latex?O_t%3D%5Ctext%20%7B%20Onset%20event%20at%20time%20bin%20%7D%20t)
![img](http://latex.codecogs.com/gif.latex?O_t%3D%5Ctext%20%7B%20Onset%20event%20at%20time%20bin%20%7D%20t)
### Прямой проход
1. Инициализируем веса 
2.	
3.

### Обратный проход
1.
2.
3.


