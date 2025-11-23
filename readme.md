# Print Shop Calculator

A simple, beautiful, and fast web-based calculator designed specifically for **print shops** to quickly calculate total sheets and billing amount for **B&W** and **Color** prints.

No installation required — just open in any browser (mobile or desktop).

**Live Demo**: [Open Calculator](https://your-username.github.io/print-calculator/) *(replace with your actual link or remove if local)*

---

### Features

- Clean, minimal UI with **Inter** font
- Separate counters for **B&W Sheets** and **Color Sheets**
- Use **+ / −** buttons to adjust quantity
- **Add** button (green) to confirm and add the amount to total
- Shows calculation breakdown (e.g., `10+25+50`)
- Automatically calculates:
  - B&W: **Rs. 8 per sheet**
  - Color: **Rs. 30 per sheet**
- **Generate total and texts** → displays final bill summary
- **Copy to Clipboard** button → instantly copy formatted bill text  
  (Perfect for sending via WhatsApp, SMS, or email)

**Copied text format**:
Total B&W sheets: 7
Total Color sheets: 2
total amount Rs. 116
text- **Reset** button to clear everything
- Fully responsive — works great on phones and tablets
- No frameworks, no dependencies — pure HTML, CSS, and JavaScript

---

### How to Use

1. Open `index.html` in any browser (double-click the file)
2. For B&W or Color:
   - Use **+** and **−** to set the number of sheets
   - Click **Add** (green button) to include it in the total
3. Repeat for multiple entries
4. Click **Generate total and texts**
5. Click **Copy to Clipboard** → paste directly into WhatsApp or anywhere

---

### Pricing (Hardcoded)

| Type         | Price per Sheet |
|--------------|-----------------|
| B&W Sheets   | Rs. 8           |
| Color Sheets | Rs. 30          |

*(You can easily change these in the JavaScript if needed)*

---

### File Structure
print-calculator/
├── index.html         ← Main file (open this)
└── README.md          ← This file
text---

### Customization (Optional)

To change prices, open `index.html` and edit these lines in the `<script>`:

```js
const totalAmount = (bwTotal * 8) + (colorTotal * 30);  // ← Change 8 and 30 here
And in the copyResult() function too.

For Developers

Built with vanilla HTML, CSS, and JavaScript
Uses Google Fonts (Inter) — loaded via CDN
Uses Clipboard API (navigator.clipboard) — works in modern browsers
No build tools, no npm, no React/Vue

Just open and use!

Made with ❤️ for print shop owners who need speed and simplicity.
Star this repo if you find it useful!