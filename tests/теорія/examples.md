# Приклади

## Змінні
```javascript
let age = 16;
Умови
if (age >= 18) {
  alert("Повнолітній");
}
Цикли
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
Функції
function greet(name) {
  alert("Привіт, " + name);
}
2. Арифметичні операції
let a = 5;
let b = 3;
let sum = a + b;
alert(sum);
3. Умовні оператори
let age = 16;

if (age >= 18) {
  alert("Повнолітній");
} else {
  alert("Неповнолітній");
}
4. Вкладені умови
let score = 85;

if (score >= 90) {
  alert("Відмінно");
} else if (score >= 70) {
  alert("Добре");
} else {
  alert("Потрібно попрацювати");
}
5. Цикл for
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
6. Цикл while
let i = 1;

while (i <= 5) {
  console.log(i);
  i++;
}
7. Функції
function sum(a, b) {
  return a + b;
}

alert(sum(2, 3));
8. Події (кнопка)
<button onclick="sayHello()">Натисни</button>

<script>
function sayHello() {
  alert("Привіт!");
}
</script>
9. Робота з DOM
<p id="text">Старий текст</p>
<button onclick="changeText()">Змінити</button>

<script>
function changeText() {
  document.getElementById("text").innerHTML = "Новий текст";
}
</script>
10. Введення даних користувачем
let name = prompt("Як тебе звати?");
alert("Привіт, " + name);
11. Простий калькулятор
let a = Number(prompt("Введи число 1"));
let b = Number(prompt("Введи число 2"));

alert("Сума: " + (a + b));
12. Генерація випадкового числа
let randomNumber = Math.floor(Math.random() * 10);
alert(randomNumber);
13. Гра "Вгадай число"
let secret = 5;
let guess = Number(prompt("Вгадай число від 1 до 10"));

if (guess === secret) {
  alert("Вгадав!");
} else {
  alert("Спробуй ще!");
