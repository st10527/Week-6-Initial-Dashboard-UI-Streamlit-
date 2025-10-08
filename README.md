# Week 6 – Initial Dashboard UI (Streamlit)

## Objective

This week, you'll begin building the web-based dashboard for your data center monitor using **Streamlit**.  
You will read data from `log.csv` and display it using tables and charts.

---

## Tasks

1. Create `app.py` and use Streamlit to:
   - Read `log.csv` into a DataFrame
   - Show the **latest 5 entries** as a table
   - Plot line charts for:
     - CPU
     - Memory
     - Disk

2. Run the dashboard locally or in Codespaces with:
   ```bash
   streamlit run app.py
