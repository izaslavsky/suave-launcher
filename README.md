# 🚀 SuAVE Tools Launcher

This is a landing page for launching various SuAVE-based tools such as spatial statistics and arithmetic operations. It helps route the necessary query parameters to each app.

---

## 🧰 Tools Included

- [➕ Arithmetic Operations](https://your-app-url/arithmetic_operations): Create new numeric variables from arithmetic expressions.
- [📊 Spatial Statistics](https://your-app-url/spatial_statistics): Perform geographically-weighted regression and spatial autocorrelation.

---

## 🚀 Getting Started

### Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

### Running the Launcher

```bash
streamlit run launcher.py
```

---

## 🔗 URL Parameters

The launcher accepts the following parameters and passes them along to each tool:

- `user`: SuAVE username
- `csv`: CSV filename
- `surveyurl`: Full SuAVE survey URL
- `dzc`: *(Optional)* Deep Zoom config file

**Example:**

```
https://your-app-url/?user=suavedemos&csv=suavedemos_demo.csv&surveyurl=https://suave-net.sdsc.edu/main/file=suavedemos_demo.csv
```

---

## 📦 Behavior

The launcher displays clickable cards for each tool, preserving the user's query parameters and allowing easy exploration of SuAVE-based tools.
