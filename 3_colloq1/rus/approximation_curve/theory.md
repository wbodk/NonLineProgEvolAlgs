# Кривая подгонки

Кривая подгонки или аппроксимации - это математическая модель или функция, которая приближенно описывает закономерности или зависимости в наборе данных. Процесс аппроксимации используется для нахождения наилучшего соответствия между математической моделью и реальными данными.  

Основная цель кривой подгонки состоит в том, чтобы создать простую, но достаточно точную функцию, которая может быть использована для предсказания значений вне известных точек данных. Это особенно полезно, когда есть необходимость анализа или предсказания трендов, а также при работе с экспериментальными данными.  

Процесс создания кривой подгонки включает в себя выбор подходящей математической формулы или модели, которая наилучшим образом соответствует данным. Обычно это может быть линейная или полиномиальная функция, экспоненциальная или логарифмическая кривая, или другие типы функций в зависимости от характера данных.  

Методы подгонки, такие как метод наименьших квадратов, используются для определения параметров модели так, чтобы минимизировать разницу между предсказанными значениями и реальными данными. Полученная кривая подгонки может затем использоваться для анализа трендов, прогнозирования будущих значений или визуализации зависимостей в данных.  


Конкретные примеры кривых подгонки могут включать следующие случаи:  

1. **Линейная регрессия:**
   - *Модель:* \(y = mx + b\)  
   - *Применение:* Подгонка прямой линии к данным, где предполагается линейная зависимость между переменными.  
 
2. **Полиномиальная аппроксимация:**
   - *Модель:* \(y = a_nx^n + a_{n-1}x^{n-1} + \ldots + a_1x + a_0\)  
   - *Применение:* Аппроксимация кривой полиномом для более гибкого учета сложных зависимостей.  

3. **Экспоненциальная кривая:** 
   - *Модель:* \(y = ae^{bx}\)  
   - *Применение:* Подгонка экспоненциальной кривой к данным с экспоненциальным ростом или затуханием.  

4. **Логарифмическая кривая:**
   - *Модель:* \(y = a \ln(x) + b\)  
   - *Применение:* Аппроксимация кривой логарифмической функцией, когда наблюдается логарифмическая зависимость.  

5. **Парабола:**
   - *Модель:* \(y = ax^2 + bx + c\)  
   - *Применение:* Подгонка параболы к данным с квадратичной зависимостью.  

6. **Кривая мощности (степенная функция):**
   - *Модель:* \(y = ax^b\)  
   - *Применение:* Подгонка степенной функции к данным с асимптотическими свойствами.  

Эти примеры демонстрируют различные формы математических моделей, которые могут быть использованы для аппроксимации разнообразных данных. Выбор конкретной модели зависит от природы данных и требований конкретной задачи.  


# ЗАДАЧА 1
Написать функцию, которая аппроксимирует заданный набор экспериментальных результатов полиномом первой степени. Входными параметрами функции являются векторы точек x, в которых производились измерения, и вектор, содержащий измеренные значения y. Выходным параметром функции является аппроксимационный полином P. Построить график экспериментальных данных и данных, полученных аппроксимацией.

# ЗАДАЧА 2
Написать функцию, которая аппроксимирует заданный набор экспериментальных результатов полиномами третьей и четвертой степени. Входными параметрами функции являются векторы точек x, в которых производились измерения, и вектор, содержащий измеренные значения y. Выходным параметром функции является аппроксимационный полином с меньшей средней абсолютной ошибкой. В функции нужно проверить, имеют ли x и y одинаковую длину.

# ЗАДАЧА 3
Написать функцию, которая аппроксимирует заданный набор экспериментальных результатов полиномами пятой и шестой степени. Входными параметрами функции являются векторы точек x, в которых производились измерения, и вектор, содержащий измеренные значения y. Выходными параметрами функции являются аппроксимационные полиномы P5 и P6. В функции нужно проверить, имеют ли x и y одинаковую длину.

# ЗАДАЧА 4
Написать функцию, которая аппроксимирует заданный набор экспериментальных результатов полиномом произвольной степени так, чтобы максимальная относительная ошибка аппроксимации не превышала 1%. Входными параметрами функции являются векторы точек x, в которых производились измерения, и вектор, содержащий измеренные значения y. В функции нужно проверить, имеют ли векторы x и y одинаковую длину. Выходными параметрами функции являются коэффициенты и степень полинома.