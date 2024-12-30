# yoshihiro
# Bilingual Kokkai Explorer

A Python program that allows you to:

1. **Enter an English keyword**  
2. **Translate it to Japanese**  
3. **Search the Japanese Diet (Kokkai) minutes via the Kokkai API**  
4. **Specify the search period (year-based) and the number of records (30, 50, or 100)**  
5. **Highlight the Japanese keyword in red within the retrieved text**  
6. **Translate the retrieved text back to English**  
7. **Save all results to a CSV file**

This project is intended to help users explore Japanese parliamentary records in a bilingual manner.

---

## Features

- **Language Conversion**: English to Japanese (for searching) and Japanese to English (for display).  
- **Flexible Search**: Choose the year and the number of records to retrieve.  
- **Text Highlighting**: Shows the searched Japanese keyword in red (ANSI escape sequence).  
- **CSV Export**: Saves your results for reference, research, or analysis.  

---

## Installation

1. **Clone the repository (or download the ZIP)**  
   ```bash
   git clone https://github.com/your-username/bilingual-kokkai-explorer.git
   cd bilingual-kokkai-explorer

