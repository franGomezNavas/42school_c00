# 🏊 C Piscine — C 00

> *Módulo introductorio de la C Piscine de 42. ¡Bienvenido al mundo de C!* 🎉

---

## 📋 Información general

| Campo | Detalle |
|---|---|
| 📦 Módulo | C 00 |
| 🔖 Versión | 8 |
| ⚙️ Compilación | `cc -Wall -Wextra -Werror` |
| 📏 Norma | `norminette -R CheckForbiddenSourceHeader` |

---

## ⚠️ Normas importantes

- ✅ Todos los archivos `.c` deben incluir el **header estándar de 42**
- ✅ El código debe cumplir la **Norma de 42**
- ✅ Las funciones **no deben terminar inesperadamente** (segfault, bus error, double free)
- ✅ Solo entregar los archivos indicados en cada ejercicio
- ✅ Usar `norminette -R CheckForbiddenSourceHeader` para verificar

---

## 📚 Ejercicios

### ✏️ Ejercicio 00 — `ft_putchar`

| | |
|---|---|
| 📁 Directorio | `ex00/` |
| 📄 Archivo | `ft_putchar.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Escribe una función que muestre el carácter pasado como parámetro.

```c
void ft_putchar(char c);
```

> 💡 Debes usar: `write(1, &c, 1);`

---

### ✏️ Ejercicio 01 — `ft_print_alphabet`

| | |
|---|---|
| 📁 Directorio | `ex01/` |
| 📄 Archivo | `ft_print_alphabet.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra el alfabeto en minúsculas en una sola línea, en orden creciente, empezando por `'a'`.

```c
void ft_print_alphabet(void);
```

---

### ✏️ Ejercicio 02 — `ft_print_reverse_alphabet`

| | |
|---|---|
| 📁 Directorio | `ex02/` |
| 📄 Archivo | `ft_print_reverse_alphabet.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra el alfabeto en minúsculas en una sola línea, en orden **decreciente**, empezando por `'z'`.

```c
void ft_print_reverse_alphabet(void);
```

---

### ✏️ Ejercicio 03 — `ft_print_numbers`

| | |
|---|---|
| 📁 Directorio | `ex03/` |
| 📄 Archivo | `ft_print_numbers.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra todos los dígitos del `0` al `9` en una sola línea y en orden creciente.

```c
void ft_print_numbers(void);
```

---

### ✏️ Ejercicio 04 — `ft_is_negative`

| | |
|---|---|
| 📁 Directorio | `ex04/` |
| 📄 Archivo | `ft_is_negative.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra `'N'` si el entero es negativo, o `'P'` si es positivo o cero.

```c
void ft_is_negative(int n);
```

> 🏁 **Milestone:** ¡Con este ejercicio tienes el mínimo para validar el proyecto! Puedes continuar con los opcionales o pasar al siguiente módulo.

---

### ✏️ Ejercicio 05 — `ft_print_comb`

| | |
|---|---|
| 📁 Directorio | `ex05/` |
| 📄 Archivo | `ft_print_comb.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra, en orden creciente, todas las combinaciones posibles de **tres dígitos distintos** en orden creciente.

```c
void ft_print_comb(void);
```

**Ejemplo de salida:**
```
012, 013, 014, ..., 789
```

> 🔎 `987` no aparece porque `789` ya existe. `999` no aparece porque los dígitos no son distintos.

---

### ✏️ Ejercicio 06 — `ft_print_comb2`

| | |
|---|---|
| 📁 Directorio | `ex06/` |
| 📄 Archivo | `ft_print_comb2.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra todas las combinaciones posibles de **dos números** (00 a 99) en orden creciente.

```c
void ft_print_comb2(void);
```

**Ejemplo de salida:**
```
00 01, 00 02, ..., 00 99, 01 02, ..., 98 99
```

---

### ✏️ Ejercicio 07 — `ft_putnbr`

| | |
|---|---|
| 📁 Directorio | `ex07/` |
| 📄 Archivo | `ft_putnbr.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra el número pasado como parámetro. Debe funcionar con **todos los valores posibles de `int`**.

```c
void ft_putnbr(int nb);
```

> 💡 Ejemplo: `ft_putnbr(42)` muestra `"42"`.

---

### ✏️ Ejercicio 08 — `ft_print_combn`

| | |
|---|---|
| 📁 Directorio | `ex08/` |
| 📄 Archivo | `ft_print_combn.c` |
| 🔧 Funciones autorizadas | `write` |

**Objetivo:** Muestra todas las combinaciones de `n` dígitos en orden creciente, con `0 < n < 10`.

```c
void ft_print_combn(int n);
```

**Ejemplo con n=2:**
```
01, 02, 03, ..., 09, 12, ..., 79, 89
```

---

## 📦 Entrega

Entrega tu proyecto en tu **repositorio Git**. Solo se evaluará el trabajo del repositorio. Verifica los nombres de los archivos antes de hacer push. 🚀
