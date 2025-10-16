# ShoppingApp

# 🛍️ Sales Invoice Generator (Shopping App)

This is a **client-side, multi-step web application** that simulates a basic retail sales transaction. It captures customer details, records item purchases, calculates the total, and generates a printable invoice, all using standard web technologies.

---

## ✨ Features

* **Multi-Step Flow:** Guides the user through a logical sequence: Customer Info → Item Selection → Purchase Review → Final Invoice.
* **Data Persistence:** Uses **Browser Local Storage** to maintain customer data and selected items across page navigations.
* **Itemized Sales:** Allows users to select quantities for multiple predefined items and calculates the line-item totals automatically.
* **Grand Total Calculation:** Automatically calculates the final amount payable.
* **Printable Invoice:** Features a dedicated "Print Invoice" button on the checkout page, optimized for printing (hides navigation buttons using CSS media queries).
* **Simple Reset:** Includes a function to clear all stored data and start a new transaction instantly.

---

## 🛠️ Technologies Used

This project is built entirely using front-end technologies:

* **HTML5:** For structure and content.
* **CSS3:** For styling and print optimization (`styles.css`).
* **Vanilla JavaScript:** For logic, data management (`localStorage`), and navigation.

---

## 🚀 How to Run Locally

1.  **Clone the Repository:**
    ```bash
    git clone [YOUR_REPOSITORY_URL]
    cd sales-invoice-generator
    ```
2.  **Open the Project:** Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, etc.).
3.  **Follow the Steps:**
    * Start by filling out the form in `index.html`.
    * Proceed through the pages to select items and finalize the purchase.

---

## 📄 File Structure

| File Name | Description |
| :--- | :--- |
| `index.html` | **Step 1:** Customer Details Entry (Home Page). |
| `sales.html` | **Step 2:** Item Selection and Quantity Input. |
| `purchase.html` | **Step 3:** Review of Selected Items and Total. |
| `checkout.html` | **Step 4:** Final Invoice display and Print functionality. |
| `styles.css` | General CSS styling for all pages and print media queries. |

---

## 💡 Workflow Diagram

**`index.html`** (Customer Details) $\rightarrow$ **`sales.html`** (Item Selection) $\rightarrow$ **`purchase.html`** (Summary) $\rightarrow$ **`checkout.html`** (Final Invoice & Print)

**(Data is transferred via `localStorage` at each step)**

<img width="581" height="594" alt="image" src="https://github.com/user-attachments/assets/6d74e444-6ea8-443b-b207-08671fd26fb7" />
<img width="570" height="589" alt="image" src="https://github.com/user-attachments/assets/74daeb2c-5079-41b9-879a-0b783fbaaacb" />
<img width="855" height="502" alt="image" src="https://github.com/user-attachments/assets/5c622f9a-94d4-4ab1-9ac1-63d9e330e397" />
<img width="643" height="573" alt="image" src="https://github.com/user-attachments/assets/2e65894e-786d-432d-b96d-922eed6893c9" />
<img width="997" height="633" alt="image" src="https://github.com/user-attachments/assets/39208e9a-cb59-4b8f-87b0-2bc57f16c26c" />




