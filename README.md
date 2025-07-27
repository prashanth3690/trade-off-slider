# Trade‑Off Slider Demo

A small, modern web app that demonstrates a “trade‑off” slider system for prioritisation. Each row has an editable label, a slider (0–5), and a point counter. When one slider changes, the total of all sliders is capped at **3 × number of rows** by reducing the value of the slider that was just changed. This prevents over‑allocation of points across priorities.

## Features

- **Editable labels:** Click the label of any row to rename it (e.g., “Marketing”, “R&D”).
- **Dynamic rows:** Starts with 4 rows and allows adding up to 6 rows via the *Add Row* button.
- **Fixed slider range:** Each slider ranges from 0 to 5, regardless of the number of rows.
- **Automatic point balancing:** The total sum of slider values cannot exceed `rows × 3`. When you adjust a slider that would push the total over the limit, that slider’s value is reduced to fit within the available points.
- **Modern Bauhaus‑inspired design:** Uses a geometric sans‑serif font, simple cards, primary accent colours (red, blue, yellow), and subtle shadows.

## How It Works

1. **Open the project** by loading `index.html` in any modern browser.
2. **Rename rows** by clicking on the text field and typing a new name.
3. **Adjust sliders** to allocate points. If the total exceeds the allowed limit, the last slider you changed will be adjusted downward automatically.
4. **Add more rows** (up to 6) by clicking the *Add Row* button; the point limit scales with the number of rows.

## Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
