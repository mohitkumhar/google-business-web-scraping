# Google Business Web Scraping  

This project is a **Google Business Page Scraper** built using **Python** and **Selenium**. It automates the process of extracting valuable business information from Google Business pages, helping businesses analyze competitors and improve their strategies.  

## 🚀 Features  
- Collects business details like **name, ratings, reviews, location, contact info**, and **opening hours**.  
- Handles dynamic content and CAPTCHA using Selenium.  
- Data is stored in a structured **JSON** format for easy analysis.  
- Supports scraping of multiple business pages in one go.  
- Handles pagination and scrolling for complete data extraction.  

## 🛠️ Setup  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/mohitkumhar/google-business-web-scraping.git
   ```  
2. **Navigate to the project directory:**  
   ```bash
   cd google-business-web-scraping
   ```  
3. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```  
4. **Run the script:**  
   ```bash
   python main.ipynb
   ```  

## 📝 Usage  
- Open the `main.ipynb` file.  
- Update the target business details in the script.  
- Run the script to scrape data.  
- The scraped data will be saved in `data.json`.  

## 💡 How It Works  
1. The script opens Google Business pages using Selenium.  
2. It searches for the target business using keywords.  
3. It extracts details such as business name, address, ratings, reviews, and contact info.  
4. Data is processed and stored in JSON format for easy access.  

## 🤖 Technologies Used  
- **Python** – Main programming language.  
- **Selenium** – For browser automation.  
- **JSON** – For data storage and processing.  
- **Pandas** – For data handling and organization.  

## 🤝 Contributing  
Contributions are welcome!  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Make your changes and commit them (`git commit -m 'Add new feature'`).  
4. Push to the branch (`git push origin feature-branch`).  
5. Create a Pull Request.  

## 👨‍💻 Contributors  
- **Mohit Kumhar** – [GitHub](https://github.com/mohitkumhar)  
