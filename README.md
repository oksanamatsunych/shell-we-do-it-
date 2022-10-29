
### Files
> підказки по роботі з файлами і структурою папок
#### 1) Зберігай файли в директоріях
#### 2) Використовуй абсолютні або відносні шляхи для підключення файлів
```html
<!-- ❌ BAD system path -->
<img src="/Users/geo_mac/Desktop/SHELL/2020-Audi-S4.jpg" alt="">

<!-- ✅ GOOD relative-->
<img src="/2020-Audi-S4.jpg" alt="">
<img src="./2020-Audi-S4.jpg" alt="">

<!-- ✅ GOOD absolute-->
<img src="https://our.site/images/2020-Audi-S4.jpg" alt="">
```

### Git
> підказки по роботі з системами версіювання
1) Перевір чи всі файли завантажились в remote репозиторій