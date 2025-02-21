# ...array

# Методҳои массив дар JavaScript

Массивҳо дар JavaScript як намуди маълумоти муҳим ҳастанд, ки имкон медиҳанд якчанд арзишро дар як тағйирёбанда нигоҳ дорем. Онҳо дорои якчанд методҳои муфид мебошанд, ки бо онҳо коркарди маълумот осон мешавад. Дар инҷо мо танҳо се усули муҳимро дида мебароем: **Destructuring, Spread ва Rest**.

## 1. **Destructuring (Шикастани массив)**

Методи **Destructuring** имкон медиҳад, ки арзишҳои массив ба тағйирёбандаҳои алоҳида тақсим карда шаванд.

```js
let [a, b, ...rest] = [10, 20, 30, 40, 50];
console.log(a); // 10
console.log(b); // 20
console.log(rest); // [30, 40, 50]
```

📌 *Бо истифода аз `...rest`, мо боқимондаи элементҳои массивро дар як тағйирёбанда нигоҳ медорем.*

## 2. **Spread (Тақсим ва нусхабардории массив)**

Методи **Spread** (`...`) барои нусха бардоштан ва тақсим кардани элементҳои массив истифода мешавад.

```js
const arr1 = [1, 2, 3];
const arr2 = [...arr1];
arr2.push(4);

console.log(arr1); // [1, 2, 3]
console.log(arr2); // [1, 2, 3, 4]
```

📌 *Методи `spread` массивро бе тағйир додани асли он нусхабардорӣ мекунад.*

## 3. **Rest (Гирифтани боқимондаи элементҳо дар функсия)**

Методи **Rest** (`...`) барои нигоҳ доштани якчанд аргумент дар массив истифода мешавад.

```js
function myFun(a, b, ...manyMoreArgs) {
  console.log(a);
  console.log(b);
  console.log(manyMoreArgs);
}

myFun("як", "ду", "се", "чор", "панҷ");
```

📌 *Методи `rest` имконият медиҳад, ки миқдори номаълум элементҳоро дар як массив нигоҳ дорем.*

---

📌 **Хулоса:**
Методҳои `Destructuring`, `Spread` ва `Rest` ба мо имкон медиҳанд, ки бо массивҳо ба таври қулай кор кунем. Ин усулҳо истифодаи динамикӣ ва осони массивҳоро дар код имкон медиҳанд. 🚀

📚 *Барои маълумоти бештар, бо маводи расмии MDN шинос шавед!*



![image](https://github.com/user-attachments/assets/cf46b7fe-883a-4f8f-843c-2a2f7a851722)
![image](https://github.com/user-attachments/assets/12253889-8777-46c6-a824-a41697bbea3c)

