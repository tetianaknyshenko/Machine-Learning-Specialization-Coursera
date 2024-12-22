# Machine-Learning-Specialization-Coursera
Gradient Descent grad spusk

Derivative производная 
Convergence - сходимость:
 Факторы, влияющие на сходимость:
Learning Rate (Скорость обучения) — слишком большой шаг может привести к отсутствию сходимости, а слишком маленький — к очень медленной сходимости.
Форма функции потерь (Loss Function) — выпуклость функции помогает гарантировать сходимость.
Шум в данных — сильный шум может препятствовать достижению устойчивого минимума.


tangent line - kasatelmzfy
slope the tangent line - наклон касательной
Gradient descent:
https://towardsdatascience.com/gradient-descent-algorithm-a-deep-dive-cf04e8115f21
https://towardsdatascience.com/gradient-descent-algorithm-and-its-variants-10f652806a3#:~:text=In%20this%20article%2C%20we%E2%80%99ll%20cover%20gradient%20descent%20algorithm,before%20going%20into%20the%20details%20of%20its%20variants.
https://www.geeksforgeeks.org/difference-between-batch-gradient-descent-and-stochastic-gradient-descent/

Матрица представляет собой прямоугольное расположение чисел, символов или выражений в строках и столбцах. Чтобы умножить матрицы, вам нужно умножить элементы (или числа) в строках первой матрицы на элементы в столбцах второй матрицы и сложить полученные значения.Строку умножаем на столбик
2  -3     9  -6        2*9-3*6     2*-6-3*-4         0   0
4  -6    6   -4        4*9-6*6    4*-6-6*-4          0   0

9  -6    2  -3         9*2-6*4   9*-3-6*-6         -6  9
6  -4    4  -6         6*2-4*4   6*-3+24           -4  6
The NumPy dot function is able to use parallel hardware in your computer and this is true whether you're running this on a normal computer, that is on a normal computer CPU or if you are using a GPU, a graphics processor unit, that's often used to accelerate machine learning jobs. The ability of the NumPy dot function to use parallel hardware makes it much more efficient than the for loop or the sequential calculation that we saw previously. Now, this version is much more practical when n is large because you are not typing w0 times x0 plus w1 times x1 plus lots of additional terms like you would have had for the previous version. 
