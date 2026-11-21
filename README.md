# 🍕 Pizza Order System - WinForms App

A user-friendly, interactive desktop application built with **C#** and **Windows Forms (.NET)** that simulates a point-of-sale (POS) and ordering system for a pizza restaurant. The application dynamically calculates the total price and updates the order summary in real-time based on the user's selections.

---

## ✨ Features

* **Size Selection:** Choose between Small, Medium, and Large pizzas.
* **Crust Type:** Select from Thin Crust or Thick Crust options.
* **Multiple Toppings:** Customize the pizza with up to 6 different toppings (Extra Cheese, Mushrooms, Tomatoes, Onion, Olives, Green Peppers).
* **Dining Preference:** Choose between *Eat In* or *Take Out*.
* **Real-Time Order Summary:** Automatically updates the selected options and recalculates the total price instantly upon any change.
* **Order Confirmation & Reset:** 
  * Locks the form upon confirming the order to prevent accidental changes.
  * Easily reset the entire form to default settings to start a new order.

---

## 🛠️ Technologies & Concepts Used

* **Language:** C#
* **Framework:** .NET Framework / Windows Forms (WinForms)
* **IDE:** Visual Studio
* **Key Programming Concepts:**
  * Event-Driven Programming (`CheckedChanged`, `Click` events).
  * UI Controls manipulation (`RadioButton`, `CheckBox`, `GroupBox`, `Label`, `Button`, `MessageBox`).
  * Clean and modular code structure (separating calculation logic from UI update logic).
  * Utilizing the `Tag` property in WinForms controls for dynamic price calculation.

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/moaazhijazi38-rgb/Pizza-Order.git
   ```
2. Open the solution file (`.sln`) in **Visual Studio**.
3. Press `F5` or click the **Start** button to build and run the application.

---

## 📸 Screenshots

<img width="955" height="569" alt="Screenshot 2026-11-21 103655" src="https://github.com/user-attachments/assets/f8c63de8-a08b-4c11-a853-b2b45cd504f0" />
<img width="943" height="523" alt="Screenshot 2026-11-21 103634" src="https://github.com/user-attachments/assets/22b176c2-1b02-4839-88e0-b59c05f98a45" />



---
---

# 🍕 نظام طلب البيتزا (نسخة العربية)

تطبيق سطح مكتب تفاعلي وسهل الاستخدام تم تطويره باستخدام لغة **C#** وتقنية **Windows Forms (.NET)**. يحاكي التطبيق نظام نقاط البيع (POS) وطلبات المطاعم، حيث يتيح للمستخدم تخصيص طلب البيتزا الخاص به مع حساب السعر الإجمالي وتحديث ملخص الطلب بشكل فوري وتلقائي.

---

## ✨ المميزات

* **اختيار الحجم:** إمكانية الاختيار بين الحجم الصغير (Small)، الوسط (Medium)، والكبير (Large).
* **نوع العجينة:** الاختيار بين العجينة الرقيقة (Thin Crust) أو السميكة (Thick Crust).
* **إضافات متعددة (Toppings):** إمكانية تحديد أكثر من إضافة في نفس الوقت (جبنة إضافية، فطر، طماطم، بصل، زيتون، فلفل أخضر).
* **مكان تناول الطعام:** تحديد ما إذا كان الطلب محلي (Eat In) أو سفري (Take Out).
* **تحديث فوري لملخص الطلب:** يتغير السعر الإجمالي وتتحدث قائمة الملخص تلقائياً بمجرد النقر على أي خيار.
* **تأكيد الطلب وإعادة التعيين:** 
  * قفل التعديلات بعد تأكيد الطلب (Order Pizza) لمنع التغيير بالخطأ.
  * زر إعادة تعيين (Reset Form) لإرجاع الواجهة إلى حالتها الافتراضية لبدء طلب جديد.

---

## 🛠️ التقنيات والمفاهيم البرمجية المستخدمة

* **لغة البرمجة:** C#
* **إطار العمل:** .NET / Windows Forms (WinForms)
* **بيئة التطوير:** Visual Studio
* **أهم المفاهيم المطبقة:**
  * البرمجة المعتمدة على الأحداث (Event-Driven Programming).
  * التعامل مع عناصر الواجهة الرسومية (`GroupBox`, `RadioButton`, `CheckBox`, `MessageBox`).
  * استخدام خاصية `Tag` لتخزين أسعار العناصر وحسابها برمجياً بطريقة ديناميكية ونظيفة.
  * تقسيم الكود إلى دوال (Functions/Methods) صغيرة ومستقلة لسهولة القراءة والصيانة.
