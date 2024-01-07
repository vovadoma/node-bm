Node Business Models (constant, dictionary, enumeration, document (form), list (data view), registers, reports, processing, business process and OLAP).

### Constant (константа)
Зберігається в таблиці констант як назва, тег, тип та значення, наприклад:

Дата заснування підприємства: 2024-01-01  
Основна валюта: USD

```
constant.foundationData.get() type Date
constant.baseCurrency.get()   type Dictionary 
```

Може бути переодична, тобно мати різні значення на різну дату. Зберігається в додатковій таблиці як дата, тип та значення.

Адреса команії: 2024-01-01 Florida, 2024-11-01 Miami 
Керівник, відсоток податку, інше що може змінюватись.

```
constant.address.get() на поточну дату
constant.foundationData.getOn(2024-01-01) на дату
```

### Dictionary (довідник)

### Enumeration (перахування)
