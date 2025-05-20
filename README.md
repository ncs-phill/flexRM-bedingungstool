# flexRM-bedingungstool
Simple, browser-based tool for creating logical conditions for internal 

# Condition Builder with Validation & Live Test

This project provides a simple, browser-based tool for creating logical conditions with placeholder variables (e.g., `{ConnectionPower} >= 100`). It allows users to generate condition strings, check them for logical conflicts or invalid values, and test them interactively against input data.

---

## 🔍 Features

- Add multiple conditions with:
  - Field selection (e.g., ConnectionPower, Consumption)
  - Logical operators (`>`, `>=`, `<`, `<=`, `==`)
  - Numeric value entry
- 🔀 Conditions are combined with `&&` in the output
- ❌ Automatic validation:
  - No negative values allowed
  - Contradictory conditions are detected
- ✅ Live test:
  - Enter test values to check if all conditions pass
  - Result shown as `TRUE` or `FALSE` with explanation
- 📋 One-click copy to clipboard
- 🔄 Reset all inputs and outputs with a single button
- 📝 Output hint above result (not copied)

---

## 🚀 Usage

1. Open `bedingungen-tool.html` in any modern browser.
2. Click “➕ Add Condition” and configure one or more rules.
3. Press “✅ Generate Conditions” to see the condition string.
4. Use “🧪 Check” to test values against the current condition set.
5. Use “📋 Copy to Clipboard” to export the condition string.

---


## 🛠️ Customization

You can easily:
- Add more fields (e.g., Temperature, Pressure)
- Extend validation rules
- Modify placeholders (`{...}`) or output format

---

## 📄 License

MIT License – free to use, modify and share.
