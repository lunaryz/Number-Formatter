# Formatter (Godot)

## 🇷🇺 Русский

### Описание
Простой аддон для форматирования чисел с разделителями тысяч.

Пример:
1000000 → 1,000,000

---

### Установка
1. Скачайте аддон    

---

### Использование
```gdscript
extends Node

var number = 1000000
var form = Formatter.new()

func _ready():
    print(form.format(number)) # 1,000,000
```


## 🇬🇧 English

## Description
A simple addon for formatting numbers with thousand separators.

Example:
1000000 → 1,000,000

---

## Installation
1. Download the addon

---

## Usage
```gdscript
extends Node

var number = 1000000
var form = Formatter.new()

func _ready():
    print(form.format(number)) # 1,000,000
```
