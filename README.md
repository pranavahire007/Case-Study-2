# Case-Study-2
# 🎧 Customer Service Management System Using Queue

> A simple Python-based Customer Service Management System developed using the **Queue Data Structure**.

---

## 🎯 Objective

To develop a simple and user-friendly Customer Service Management System using Python and the Queue data structure to manage customer requests efficiently and serve customers in the order they arrive.

---

## 📖 Introduction

The **Customer Service Management System** is a simple application designed to manage customers waiting for assistance at a customer service center.

The project uses the **Queue data structure**, which follows the First In, First Out (FIFO) principle. According to this principle, the customer who enters the queue first is served first.

In this project, customers can be added to the waiting queue, displayed in their service order, searched by name, and served one by one. The system also provides information about the total number of customers waiting for service.

This project demonstrates the practical application of queue operations in real-world situations such as customer support centers, bank counters, ticket booking services, and help desks.

---

## ✨ Features

| **Feature** | **Description** |
|---|---|
| ➕ Add Customer | Add a new customer to the waiting queue |
| 🎧 Serve Customer | Serve and remove the first customer in the queue |
| 📋 Display Queue | View all customers waiting for service |
| 🔍 Search Customer | Search for a customer by name |
| 📊 Queue Status | Display the total number of waiting customers |
| 🚪 Exit | Exit the application |

---

## 🧩 Data Structure Used

### Queue

A **Queue** is a linear data structure that follows the First In, First Out (FIFO) principle. The first element inserted into the queue is the first element removed.

In this project, a Python list is used to implement the queue.

Each customer is added to the rear of the queue, and the customer at the front is removed when service is provided.

**Structure:**

`FRONT → [Customer 1] → [Customer 2] → [Customer 3] ← REAR`

**Example:**

If customers arrive in the following order:

`Rahul → Priya → Amit`

The service order will be:

`Rahul → Priya → Amit`

This ensures that customers are served in the order they arrive.

---

## 💻 Technology Used

- 🐍 **Python**
- 📋 **Queue Data Structure**
- 🧱 **Functions and Conditional Statements**
- 📚 **Python Lists**
- 🖥️ **Visual Studio Code (VS Code)**

---

## ⚙️ Operations

### ➕ Add Customer

Allows the user to enter a customer's name and add the customer to the rear of the waiting queue.

### 🎧 Serve Customer

Removes and serves the customer at the front of the queue. If the queue is empty, the system displays an appropriate message.

### 📋 Display Queue

Displays all customers currently waiting for service in their order of arrival.

### 🔍 Search Customer

Searches for a customer by name and displays their position in the waiting queue if found.

### 📊 Queue Status

Displays the total number of customers currently waiting for service.

### 🚪 Exit

Terminates the application.

---

## ▶️ How to Run

1. Install Python on your computer.
2. Download or clone this repository.
3. Open the project folder in VS Code.
4. Create or open the `main.py` file.
5. Open the terminal in VS Code.
6. Run the following command:

```bash
python main.py
```

7. Select an option from the menu to perform the desired operation.

---

## 📌 Learning Outcomes

Through this project, we understand:

- How the **Queue data structure** works.
- The concept of First In, First Out (FIFO).
- How to perform enqueue and dequeue operations.
- How to add, search, display, and remove customers from a queue.
- How to handle empty queues using conditional statements.
- How data structures can be applied to real-world customer service systems.
- How to implement a menu-driven application using Python functions.

---

## 🎓 Conclusion

The **Customer Service Management System** successfully demonstrates the implementation and practical use of the Queue data structure in Python. The application provides a simple and organized method for managing customer requests by maintaining the order in which customers arrive and ensuring that the first customer in the queue is served first.

Through this project, we gain a better understanding of queue operations, the FIFO principle, and the importance of linear data structures in solving real-world problems. The project also strengthens our knowledge of Python programming, functions, lists, and conditional statements.

Overall, this case study demonstrates how the Queue data structure can be used to develop an efficient and easy-to-understand customer service application, similar to the basic queue management systems used in banks, help desks, and service centers.

---

### 👩‍💻 Developed as a Data Structures and Algorithms Case Study

**Python | Queue | FIFO | Customer Service Management System**
