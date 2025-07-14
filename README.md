# 🛒 SuperMarket Checkout Simulation

A Python simulation of a supermarket checkout system using logic-driven customer flow and multithreading. The simulation handles different basket sizes, lane queues, and lane types (regular vs self-checkout), and visualizes the control with a simple Tkinter GUI.

---

## 📌 Features

- Customers have random basket sizes (1–20 items)
- Two types of checkout lanes: Regular and Self-Checkout
- Lanes open and close dynamically based on usage
- Queue times and processing logic are updated in real time
- Multithreaded simulation for realistic behavior
- Tkinter GUI to start/stop simulation

---

## 🛠 Technologies Used

- **Language:** Python 3.8+
- **Libraries:** 
  - `tkinter` – for GUI
  - `threading` – for concurrent lane logic
  - `time`, `random`, `datetime` – for simulation timing and randomness

---

## 🧪 How It Works

- Regular lanes are faster but support shorter queues (5 people max)
- Self-checkout lanes are slower but support longer queues (15 people max)
- Basket size determines processing time (`items * TTP`)
- Lanes automatically close after 30 seconds of inactivity
- If all lanes are full or closed, new lanes open automatically
- Real-time lane status is printed to the terminal
- GUI allows you to start/stop simulation with a button click

---

## ▶️ How to Run

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/junayd-elahi/SuperMarket-Simulation.git
   cd SuperMarket-Simulation
   ```

2. **Run the script**
   ```bash
   python supermarket_simulation.py
   ```

3. **Use the GUI**
   - **Start Simulation** – Begins spawning customers and processing lanes
   - **Run Sub-program** – Placeholder for future feature
   - **Stop Simulation** – Stops threads and halts lane activity
   - **Exit** – Closes the GUI and ends the program

---

## 🧠 What I Learned

- Designing multithreaded simulations in Python
- Modeling real-world queue systems
- Managing GUI state with threads safely
- Balancing simplicity and concurrency in real-time systems

---

## 🧩 Possible Improvements

- Add graphical visualisation of lane queues and timers
- Export logs to CSV for later analysis
- Introduce customer priority levels (e.g. elderly, staff-only lanes)
- Implement unit tests for logic validation

---

## 📫 Contact Me

If you'd like to connect or collaborate, feel free to reach out:

📧 **junayd.elahi124@gmail.com**  
🔗 [GitHub](https://github.com/junayd-elahi) | [LinkedIn](https://www.linkedin.com/in/junayd-elahi-2029b9213/)

---
