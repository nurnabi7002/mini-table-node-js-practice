# 📊 Multiplication Table Generator (JavaScript)

This simple JavaScript program prints the multiplication table of any given number from 1 to 10 in the console.

---

## 📁 File: `table.js`

This file generates a multiplication table for a number. By default, the number is set to `9`, but you can change it to any other value by editing the `num` variable.

---

## 💻 How to Run

1. Make sure you have **Node.js** installed on your system.

2. Open your terminal or command prompt.

3. Navigate to the folder where `table.js` is located.

4. Run the file using:

```bash
node table.js
```

🧠 Logic Overview
A for loop runs from 1 to 10.

On each iteration, it multiplies the iterator i by the given number num.

It logs the output in a readable format using template literals:

i x num = result

Example:
```
1 x 9 = 9
2 x 9 = 18
...
10 x 9 = 90
```

🌐 Want to Use in Browser?
To use this code in a browser environment with prompt() input, wrap it in a <script> tag and connect it to an HTML file:

let num = parseInt(prompt("Enter a number:"));
for (let i = 1; i <= 10; i++) {
    console.log(`${i} x ${num} = ${i*num}`);
}


✍️ Author
Built with ❤️ by [MD Nur Nabi Khan]


