# 🏦 Mortgage Proposal Application

&#x20;  &#x20;

---

> **A dynamic, customizable, and print-ready tool for generating professional mortgage proposals.**

---

## 🚀 Features


---

```plaintext
index.html        # Main Application
README.md         # This Documentation
assets/           # (optional, for logos or branding)
```

---

## ✨ Quick Start

1. **Open** `index.html` in any modern browser.
2. **Edit fields**: Click on any value to update.
3. **Add/Remove Options**: Use the “Add Option” and “Remove Option” buttons.
4. **Upload your logo** (file upload or direct URL).
5. **Print or Save as PDF**: Click “Print to PDF”.

---

## ⚙️ Automated Data Input

- You can pre-populate the proposal via a **Base64-encoded hash** in the URL:

  ```text
  file:///path/to/index.html?hash=BASE64_ENCODED_DATA
  ```

- The order of fields matches the `populateFieldsFromHash()` function in JavaScript.

- ⚠️ **For automation or API use only; not for manual editing.**

---

| Section                | Editable? | Notes                                       |
| ---------------------- | --------- | ------------------------------------------- |
| Cover Page             | Yes       | Client and Advisor info, Logo               |
| Financial Requirements | Yes       | Add/remove mortgage options dynamically     |
| Transaction Fees       | Yes       | Add/remove columns/rows, auto-summarization |
| Bank Fees              | Yes       | Per bank option                             |
| Required Documents     | Yes       | Salaried/Business Client Lists, editable    |

---

## 🎨 Customization

- **Colors/Fonts/Branding:**\
  Edit the `<style>` section in `index.html`.
- **Rows/Sections:**\
  Add/remove `<tr>` elements for more/less details.
- **Max Options:**\
  Currently, up to 3 mortgage options are supported for clarity.

---

## 🖨️ Printing & PDF Export

- Click `Print to PDF` for a presentation-quality output.
- On print, input fields become styled text for clarity.
- Logos auto-place to cover/footer as appropriate.
- Emphasized fields (thick borders) highlight critical values.
- Uses CSS `@media print` for perfect pagination and style.

---

## 🛠️ Technologies Used

| Tech       | Purpose                    |
| ---------- | -------------------------- |
| HTML5      | Markup                     |
| CSS3       | Styling, print media       |
| Vanilla JS | Logic, dynamic rendering   |
| Cleave.js  | Input formatting (numbers) |

---

## 📌 Best Practices

- ✔️ **Review all fields before printing.**
- ✔️ **Always upload the correct logo.**
- ✔️ Use Base64-encoded hashes only if you know the data structure.
- ✔️ Stick to max 3 options for legibility.

---

## 🐞 Known Issues

- Print layout may vary slightly between browsers—always preview before sharing.
- The encoded hash must follow the required field order.
- For security, only use trusted input for automation.

---

## 📝 License

> **Proprietary** – Internal or client-authorized use only.

---

## 💬 Support & Questions

For technical issues or feature requests, please contact your IT representative or project maintainer.

---

> **“Professional proposals made effortless, accurate, and beautiful.”**

---

