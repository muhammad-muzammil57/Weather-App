# Weather by Muzammil

A modern, clean, and responsive weather application built using **HTML**, **CSS**, and **JavaScript**. This project allows users to search for any city and instantly view real-time weather details such as **temperature**, **condition**, **humidity**, **wind speed**, and a **multi-day forecast**.

---

## 📌 Purpose of This Project

This project was created to:

* Practice **API integration** with JavaScript.
* Build a **real‑world weather interface** with a minimal and interactive UI.
* Strengthen skills in **DOM manipulation**, **error handling**, and **responsive design**.
* Provide a beginner‑friendly weather app for learning or portfolio display.

---

## 🚀 Features

* 🔍 **Search any city** to get current weather.
* 🌤️ Displays **temperature**, **condition**, and **weather icon**.
* 💧 Shows **humidity** and **wind speed**.
* 📅 **Date auto‑updates** based on search.
* 📊 **Forecast section** (dynamic items loaded through JavaScript).
* ❌ **Error message** if city is not found.
* 🎨 Clean UI inspired by modern GitHub project READMEs.

---

## 🧩 Code Structure

```
index.html      → UI layout
style.css       → Styling and layout
script.js       → API calls, search logic, DOM updates
assets/         → Weather icons and illustrations
```

---

## 🛠️ Errors Faced During JavaScript Development

While building the app, several issues occurred:

### ❗ 1. **Error: Cannot read properties of undefined (reading 'temp')**

This happened when the API returned an invalid city and the script still tried to read weather data.
**Fix:** Added a condition to check if `data.cod === "404"` before accessing values.

### ❗ 2. **CORS Error (Blocked by CORS policy)**

Some APIs require HTTPS or specific request headers, causing CORS failures.
**Fix:** Switched to reliable open‑weather API with proper URL formatting.

### ❗ 3. **TypeError: forecastItemsContainer.innerHTML is null**

Occurred because JavaScript executed before the elements loaded.
**Fix:** Ensured script runs at bottom of HTML or wrapped logic in `window.onload`.

### ❗ 4. **Image Path Not Loading**

Relative paths for weather icons were incorrect.
**Fix:** Updated to `assets/weather/...` ensuring correct directory reference.

---

## 👨‍💻 Author

This project is written and maintained by **Muzammil TechCanvas**.

GitHub Profile: *https://github.com/muhammad-muzammil57*

---
## ▶️ How to Use

1. Download or clone this repository.
2. Open `index.html` in your browser.
3. Type any city name and click the **Search** button.

---

## 📝 Future Improvements

* Add auto‑detect **current location weather**.
* Add dark/light theme.
* Add hourly forecast.
* Convert to a full **React.js App**.

---

## 📷 Screenshots

*
<img width="1242" height="841" alt="weather" src="https://github.com/user-attachments/assets/a333c670-d63e-4099-89c7-f41d71621e35" />
 
*
