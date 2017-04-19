# 1533329-Abril-19


**Este es el ejercicio numero 1**
~~~
export var1=$((ps -A | wc -l)) | echo $((var1 - 1))
~~~

**EJERCICIO 2**
~~~
export TOTAL=$(( 2 ** 4 ));echo ${TOTAL}
~~~

**EJERCICIO 3 (correccion del ejercicio 1)**
~~~
ps -A | tail -n +2 | wc -l
~~~


