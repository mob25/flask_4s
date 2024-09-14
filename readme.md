# Контроль версий углублённо

Работа с изменениями

1. Просмотрите историю коммитов в своём проекте и выберите три случайных коммита. Просмотрите изменения, которые были в них сделаны.

![](https://github.com/mob25/flask_4s/blob/main/img/1.jpg)


![](https://github.com/mob25/flask_4s/blob/main/img/2.jpg)

2. Верните эти изменения командой git revert последовательно, чтобы в итоге получилось тоже три коммита.

![](https://github.com/mob25/flask_4s/blob/main/img/3.jpg)

3. Попробуйте отменить эти три коммита:
* последний — командами git reset --soft и git restore;

![](https://github.com/mob25/flask_4s/blob/main/img/4.jpg)


* предпоследний — командой git reset --mixed и git restore;

![](https://github.com/mob25/flask_4s/blob/main/img/5.jpg)

* первый — командой git reset --hard.

![](https://github.com/mob25/flask_4s/blob/main/img/6.jpg)




