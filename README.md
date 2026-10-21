# Ro'yxatlarni kesish (slicing)

## Slicing_list01

`numbers` ro'yxati berilgan. Juft indeksdagi (0, 2, 4, ...) elementlarni qaytaring.

**Misol 1:**

```Python
Kirish: numbers=[8000, 12000, 10000, 9500, 11000, 7000, 13000]
Chiqarish: [8000, 10000, 11000, 13000]
```

---

## Slicing_list02

Ro'yxat berilgan. Uni teskari tartibda qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Python", "Matematika", "Ingliz tili", "Fizika"]
Chiqarish: ["Fizika", "Ingliz tili", "Matematika", "Python"]
```

---

## Slicing_list03

Ro'yxat berilgan. Uni o'zining teskari tartibdagi nusxasi bilan birlashtirib qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[26, 178, 74]
Chiqarish: [26, 178, 74, 74, 178, 26]
```

---

## Slicing_list04

Allamurodning bir haftalik qadamlari ro'yxati berilgan (dushanbadan yakshanbagacha). Dastlabki uch kunlik qadamlarni qaytaring.

**Misol 1:**

```Python
Kirish: qadamlar=[8000, 12000, 10000, 9500, 11000, 7000, 13000]
Chiqarish: [8000, 12000, 10000]
```

---

## Slicing_list05

Ro'yxat, n va k berilgan. n-indeksdan k-indeksgacha (k kirmaydi) bo'lgan elementlarni qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=2, k=5
Chiqarish: [10000, 9500, 11000]
```

---

## Slicing_list06

Ro'yxat berilgan. Boshidan boshlab har uchinchi elementni qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000]
Chiqarish: [8000, 9500, 13000]
```

---

## Slicing_list07

Ro'yxat va n berilgan. Boshidan boshlab n qadam bilan barcha elementlarni qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=2
Chiqarish: [8000, 10000, 11000, 13000]
```

**Misol 2:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=4
Chiqarish: [8000, 11000]
```

---

## Slicing_list08

Ro'yxat va n berilgan. Oxiridan boshlab n qadam bilan barcha elementlarni qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=2
Chiqarish: [13000, 11000, 10000, 8000]
```

**Misol 2:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=3
Chiqarish: [13000, 9500, 8000]
```

---

## Slicing_list09

Ro'yxat va n berilgan. Dastlabki n ta elementdan tashqari hammasini qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Python", "Matematika", "Ingliz tili", "Fizika"], n=2
Chiqarish: ["Ingliz tili", "Fizika"]
```

---

## Slicing_list10

Ro'yxat va n berilgan. Dastlabki n ta elementdan tashqari hammasini teskari tartibda qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Python", "Matematika", "Ingliz tili", "Fizika"], n=1
Chiqarish: ["Fizika", "Ingliz tili", "Matematika"]
```

---

## Slicing_list11

Allamurodning bir haftalik qadamlari ro'yxati berilgan (dushanbadan yakshanbagacha). Oxirgi uch kunlik qadamlarni qaytaring.

**Misol 1:**

```Python
Kirish: qadamlar=[8000, 12000, 10000, 9500, 11000, 7000, 13000]
Chiqarish: [11000, 7000, 13000]
```

---

## Slicing_list12

Ro'yxat berilgan. Birinchi va oxirgi elementlarsiz qolgan qismini qaytaring.

**Misol 1:**

```Python
Kirish: royxat=["Python", "Matematika", "Ingliz tili", "Fizika"]
Chiqarish: ["Matematika", "Ingliz tili"]
```

---

## Slicing_list13

Allamurodning bir haftalik qadamlari ro'yxati berilgan (dushanbadan yakshanbagacha). Ish kunlari (dastlabki 5 kun) va dam olish kunlari (oxirgi 2 kun) qadamlari yig'indisini `[ish_kunlari, dam_olish]` ro'yxati ko'rinishida qaytaring. Kesish va `sum()` dan foydalaning.

**Misol 1:**

```Python
Kirish: qadamlar=[8000, 12000, 10000, 9500, 11000, 7000, 13000]
Chiqarish: [50500, 20000]
```

---

## Slicing_list14

Allamurodning 6 oylik daromadi ro'yxati berilgan. Birinchi va ikkinchi yarim (3 oydan) daromadlari yig'indilari farqini (ikkinchi − birinchi) qaytaring.

**Misol 1:**

```Python
Kirish: daromad=[6500000, 6500000, 6800000, 7000000, 7200000, 7200000]
Chiqarish: 1600000
```

---

## Slicing_list15

Juft uzunlikdagi ro'yxat berilgan. Uning ikki yarmini o'rnini almashtirib qaytaring. `len()` va kesishdan foydalaning.

**Misol 1:**

```Python
Kirish: royxat=["Python", "Matematika", "Ingliz tili", "Fizika"]
Chiqarish: ["Ingliz tili", "Fizika", "Python", "Matematika"]
```

---

## Slicing_list16

Ro'yxat berilgan. Agar u teskari tartibda ham bir xil bo'lsa `True`, aks holda `False` qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[2, 0, 0, 2]
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: royxat=[2, 0, 2, 6]
Chiqarish: False
```

---

## Slicing_list17

Allamurodning fanlar ro'yxati va indeks n berilgan. Kesish yordamida n-indeksdagi fanni olib tashlab, yangi ro'yxatni qaytaring.

**Misol 1:**

```Python
Kirish: fanlar=["Python", "Matematika", "Ingliz tili", "Fizika"], n=1
Chiqarish: ["Python", "Ingliz tili", "Fizika"]
```

---

## Slicing_list18

Allamurodning fanlar ro'yxati, indeks i va yangi fan berilgan. Kesish yordamida yangi fanni i-o'ringa qo'shib, ro'yxatni qaytaring.

**Misol 1:**

```Python
Kirish: fanlar=["Python", "Matematika", "Ingliz tili", "Fizika"], i=2, fan="Algoritmlar"
Chiqarish: ["Python", "Matematika", "Algoritmlar", "Ingliz tili", "Fizika"]
```

---

## Slicing_list19

Sonlar ro'yxati berilgan. Juft indekslardagi elementlar yig'indisidan toq indekslardagi elementlar yig'indisini ayirib qaytaring.

**Misol 1:**

```Python
Kirish: royxat=[8000, 12000, 10000, 9500, 11000, 7000, 13000]
Chiqarish: 13500
```

**Misol 2:**

```Python
Kirish: royxat=[1, 2, 3, 4]
Chiqarish: -2
```

---

## Slicing_list20

Allamurodning bir haftalik qadamlari ro'yxati berilgan (dushanbadan yakshanbagacha). Son n berilgan. Oxirgi n kunlik qadamlar yig'indisi dastlabki n kunlik qadamlar yig'indisidan qanchaga ko'p (yoki kam) ekanini qaytaring.

**Misol 1:**

```Python
Kirish: qadamlar=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=3
Chiqarish: 1000
```

**Misol 2:**

```Python
Kirish: qadamlar=[8000, 12000, 10000, 9500, 11000, 7000, 13000], n=2
Chiqarish: 0
```

