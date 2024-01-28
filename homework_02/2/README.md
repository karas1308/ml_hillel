# Homework

## Інсталяція залежностей

```bash
pip install -r requirements.txt
```

## Завдання 1

1. Допишіть в файлі `kfold.py` функції `kfold_cross_validation` та `evaluate_accuracy` для того щоб порахувати точність
   роботи K nearest neighbors класифікатора.

2. Порахуйте для різних `k` в `KNN` точність на **тестовому** датасеті і запишіть в `README.md`, `k` беріть з таблички
   нижче

 k | Accuracy
---|----------
 3 | ???
 4 | ???
 5 | ???
 6 | ???
 7 | ???
 9 | ???
10 | ???
15 | ???
20 | ???
21 | ???
40 | ???
41 | ???

__________________________
Training data: (1000, 784) (1000,)
Test data: (400, 784) (400,)
KNN with k = 3
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.88
Fold accuracy: 0.88
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.85
Predicted 200/200 samples
Accuracy: 0.85
Fold accuracy: 0.85
Average Cross-Validation Accuracy: 0.85
Sum of accuracies 4.26
======================================
KNN with k = 4
Predicted 200/200 samples
Accuracy: 0.87
Fold accuracy: 0.87
Average Cross-Validation Accuracy: 0.87
Predicted 200/200 samples
Accuracy: 0.89
Fold accuracy: 0.89
Average Cross-Validation Accuracy: 0.88
Predicted 200/200 samples
Accuracy: 0.85
Fold accuracy: 0.85
Average Cross-Validation Accuracy: 0.87
Predicted 200/200 samples
Accuracy: 0.85
Fold accuracy: 0.85
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Sum of accuracies 4.325
======================================
KNN with k = 5
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.85
Fold accuracy: 0.85
Average Cross-Validation Accuracy: 0.85
Predicted 200/200 samples
Accuracy: 0.85
Fold accuracy: 0.85
Average Cross-Validation Accuracy: 0.85
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Sum of accuracies 4.275
======================================
KNN with k = 6
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.88
Fold accuracy: 0.88
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.86
Sum of accuracies 4.3
======================================
KNN with k = 7
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.85
Predicted 200/200 samples
Accuracy: 0.87
Fold accuracy: 0.87
Average Cross-Validation Accuracy: 0.86
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.85
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.85
Sum of accuracies 4.255
======================================
KNN with k = 9
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.85
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Sum of accuracies 4.215
======================================
KNN with k = 10
Predicted 200/200 samples
Accuracy: 0.81
Fold accuracy: 0.81
Average Cross-Validation Accuracy: 0.81
Predicted 200/200 samples
Accuracy: 0.86
Fold accuracy: 0.86
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.84
Sum of accuracies 4.199999999999999
======================================
KNN with k = 15
Predicted 200/200 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.8
Predicted 200/200 samples
Accuracy: 0.84
Fold accuracy: 0.84
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Sum of accuracies 4.095
======================================
KNN with k = 20
Predicted 200/200 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.8
Predicted 200/200 samples
Accuracy: 0.81
Fold accuracy: 0.81
Average Cross-Validation Accuracy: 0.8
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.81
Predicted 200/200 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.81
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.81
Sum of accuracies 4.05
======================================
KNN with k = 21
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 200/200 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.81
Predicted 200/200 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.81
Sum of accuracies 4.04
======================================
KNN with k = 40
Predicted 200/200 samples
Accuracy: 0.76
Fold accuracy: 0.76
Average Cross-Validation Accuracy: 0.76
Predicted 200/200 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.78
Predicted 200/200 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.78
Predicted 200/200 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.78
Predicted 200/200 samples
Accuracy: 0.76
Fold accuracy: 0.76
Average Cross-Validation Accuracy: 0.78
Sum of accuracies 3.89
======================================
KNN with k = 41
Predicted 200/200 samples
Accuracy: 0.76
Fold accuracy: 0.76
Average Cross-Validation Accuracy: 0.76
Predicted 200/200 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.77
Predicted 200/200 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.78
Predicted 200/200 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.78
Predicted 200/200 samples
Accuracy: 0.77
Fold accuracy: 0.77
Average Cross-Validation Accuracy: 0.78
Sum of accuracies 3.875
======================================

Які можна зробити висновки про вибір `k`?

Результати на "k" = 3, 4, 5, 6, 7 дуже схожі, але найкращі показники при "k" = 4.
При збільшенні "k" точність зменшується.

3. Знайшовши найкращий `k` змініть `num_folds` (в `main()`) та подивіться чи в середньому точність на валідаційних
   датасетах схожа з точністю на тестовому датасеті.

Точність на тестових даних нижча, але при збільшенні num_folds точність зростає, час обчислення в таком випадку теж
зростає

Test data: (400, 784) (400,)
KNN with k = 4
num_folds = 2
Predicted 200/200 samples
Accuracy: 0.76
Fold accuracy: 0.76
Average Cross-Validation Accuracy: 0.76
Predicted 200/200 samples
Accuracy: 0.72
Fold accuracy: 0.72
Average Cross-Validation Accuracy: 0.74
Sum of accuracies 1.475
======================================

Training data: (1000, 784) (1000,)
Test data: (400, 784) (400,)
KNN with k = 4
num_folds = 10
Predicted 40/40 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 40/40 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.82
Predicted 40/40 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.81
Predicted 40/40 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.81
Predicted 40/40 samples
Accuracy: 0.8
Fold accuracy: 0.8
Average Cross-Validation Accuracy: 0.81
Predicted 40/40 samples
Accuracy: 0.72
Fold accuracy: 0.72
Average Cross-Validation Accuracy: 0.8
Predicted 40/40 samples
Accuracy: 0.9
Fold accuracy: 0.9
Average Cross-Validation Accuracy: 0.81
Predicted 40/40 samples
Accuracy: 0.72
Fold accuracy: 0.72
Average Cross-Validation Accuracy: 0.8
Predicted 40/40 samples
Accuracy: 0.78
Fold accuracy: 0.78
Average Cross-Validation Accuracy: 0.8
Predicted 40/40 samples
Accuracy: 0.82
Fold accuracy: 0.82
Average Cross-Validation Accuracy: 0.8
Sum of accuracies 8.0
======================================