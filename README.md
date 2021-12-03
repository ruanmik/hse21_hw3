# hse21_hw3

### Финальная таблица со статистикой по образцам:
ID образца | Тип образца | Общее кол-во исходных чтений	 | Процент чтений, которые были успешно откартированы уникально | Процент чтений, которые были успешно откартированы не уникально | Кол-во уникально откартированных чтений | Общее кол-во чтений, которые попали на гены
--- | --- | --- | --- | --- | --- | ---
SRR3414635 | control | 20956475 | 87.94% | 9.39% | 18428317 | 10066884
SRR3414636 | control | 20307147 | 87.78% | 9.51% | 17825380 | 15757580
SRR3414637 | control | 20385570 | 87.54% | 9.82% | 17844858 | 15736978
SRR3414629 | reprogramming | 21106089 | 87.06% | 10.11% | 18375888 | 16049609
SRR3414630 | reprogramming | 15244711 | 86.50% | 10.80% | 13186139 | 11465324
SRR3414631 | reprogramming | 24244069 | 86.33% | 10.80% | 20928945 | 18408851

### Часть №1
[Ноутбук Python](https://colab.research.google.com/drive/1DsS-bfAZErMboi3OT05ytPdzlmlg89IV?usp=sharing)

#### Статистика и графики по каждому образцу FastQC в папке [FastQC](https://github.com/ruanmik/hse21_hw3/blob/main/FastQC/)

#### Cтатистика из файлов multiQC
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/Py_stat1.png)
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/Py_stat2.png)
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/Py_stat3.png)

 
 ### Часть №2
[Ноутбук R](https://colab.research.google.com/drive/1B2a0_tjpvp6IW89W-F2_1RxSedfIV5aI?usp=sharing)
#### Графики из анализа DESeq2
##### MA-plot
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/R_stat2.png)

##### Тепловая карта
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/R_stat3.png)

##### Графики со значениями "Normalized counts" в контрольных и перепрограммированных образцах
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/R_stat4.png)
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/R_stat5.png)
![](https://github.com/ruanmik/hse21_hw3/blob/main/images/R_stat6.png)

