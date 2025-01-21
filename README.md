# FullStack Dev - Project

========================

## **Create a 2-page Responsive Vue.JS SPA web application**

---

### **Page 1: Landing Page**

- **Goal:** Create a landing page containing a table showing Spot prices using data from the following Sharenet API call:
  - **API Endpoint:** [https://api.sharenet.co.za/api/v1/px2/spots](https://api.sharenet.co.za/api/v1/px2/spots)
- **Requirements:**
  1. Create a **table** showing the **latest 5 prices** of each category with the following columns:
     - **FullName**
     - **Price**
     - **Move**
     - **Percentage Move**
     - **Time**
  2. **Sorting:** Table columns must be sortable.
  3. **Formatting:** All percentages must have **2 decimal places**.
  4. **Responsiveness:** Page must be **mobile responsive**.
  5. **Props:** Pass all data as **props**.
  6. **Navigation:** Include a **menu link** to **Page 2** and **Page 3**.

---

### **Page 2: Contact Us Page**

- **Goal:** Display Sharenet address details, contact numbers, and location using Google Maps.
- **Requirements:**
  1. **Link Back:** Provide a link back to **Page 1**.

---

### **Page 3: Venues and Workshop Dates**

- **Goal:** Display different venues and workshop dates with availability.
- **Requirements:**
  1. **Filter:** Only display dates with seats available.
  2. **Booking:**
     - Allow users to **book dates**.
     - Save booked dates to a **Node.js server** (live API, not localhost).
     - Store data in a **MySQL table**.

---

### **Bonus:**

- Package the working app in a **Docker image**.
