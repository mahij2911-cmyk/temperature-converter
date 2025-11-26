

# 🌡️ Temperature Converter in C

A simple and beginner-friendly C program that converts temperature between
Celsius, Fahrenheit, and Kelvin.

---
 📘 About This Project

This project helps convert temperature between different units using simple
mathematical formulas. It is designed for beginners who are learning C
programming and need a small practical project for college work.

The program supports:
- Celsius to Fahrenheit
- Fahrenheit to Celsius
- Celsius to Kelvin

---

 🧮 Conversion Formulas Used

| Conversion | Formula |
|------------|---------|
| Celsius → Fahrenheit | F = (C × 9/5) + 32 |
| Fahrenheit → Celsius | C = (F − 32) × 5/9 |
| Celsius → Kelvin | K = C + 273.15 |

---
⭐ Features

- Simple and easy to use
- Beginner-level program
- Uses switch-case
- Clear inputgcc temperature_converter.c -o temp and output
- Clean code structure


Program Flow
+---------------------------+
          |     START PROGRAM         |
          +-------------+-------------+
                        |
                        v
         +--------------+--------------+
         |   Show Menu to the User     |
         +--------------+--------------+
                        |
                        v
            +-----------+----------+
            | Take User Choice     |
            +-----------+----------+
                        |
       +----------------+----------------+
       |                |                |
       v                v                v
 C to F block     F to C block      C to K block
       |                |                |
       v                v                v
 Calculate         Calculate         Calculate
       |                |                |
       +----------------+----------------+
                        |
                        v
               Display Result
                        |
                        v
                  Program End

● Code structure 

temperature_converter.c
│
├── Display menu
├── Take user input
├── Switch-case
│     ├── Celsius to Fahrenheit
│     ├── Fahrenheit to Celsius
│     └── Celsius to Kelvin
└── Print converted value


● Sample output 

---- Temperature Converter ----
1. Celsius to Fahrenheit
2. Fahrenheit to Celsius
3. Celsius to Kelvin
Enter your choice: 1
Enter temperature in Celsius: 37
Temperature in Fahrenheit: 98.60


● How to Run 
   

 1• Compile

      gcc temperature_converter.c -o temp 
    
     
2. Run 
    
    ./temp



 ✅ Conclusion

This project is helpful for understanding the basics of programming using C.
It demonstrates how input, calculation, and output work together in a program.
It is suitable for college practical and beginner practice.

Author: Mahi Jaiswal 
