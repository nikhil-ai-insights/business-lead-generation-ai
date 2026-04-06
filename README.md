# 🚀 Business Lead Generation AI

> An automated AI-powered workflow that generates high-quality local business leads using Google Maps scraping, data filtering, and structured storage.

---

## 📌 Overview

**Business Lead Generation AI** is a fully automated system designed to simplify and scale the process of finding local business leads.

Instead of manually searching and collecting data, this workflow:

- Takes user input (business type & location)
- Extracts data from Google Maps
- Filters and cleans leads
- Stores structured data in Google Sheets

> 💡 Built for freelancers, agencies, and startups who want to automate lead generation.

---

## ⚙️ Workflow Architecture

```
User Input → Search Query → Google Maps Scraping → Data Processing →
Filtering → Formatting → Google Sheets Storage
```

---

## 🧠 Key Features

- ✅ AI-powered smart search query generation
- ✅ Automated Google Maps data extraction
- ✅ Data cleaning & validation (removes incomplete leads)
- ✅ Structured formatting for CRM-ready output
- ✅ Seamless integration with Google Sheets
- ✅ Fully automated pipeline (minimal manual effort)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| ⚡ n8n | Workflow Automation |
| 🌐 Google Maps | Data Source |
| 📊 Google Sheets | Data Storage |
| 🔗 API Integration | Scraping & Processing |
| 🤖 AI Logic | Query Building & Filtering |

---

## 📂 Workflow Breakdown

### 1. 🎯 Lead Capture Interface
Accepts user input:
- **Business Type** (e.g., Restaurants, Gyms)
- **Location** (City/Area)

### 2. 🔍 Smart Search Builder
Converts input into optimized search queries.

```
"Top restaurants in Delhi with contact details"
```

### 3. 🗺️ Google Maps Data Extractor
Fetches:
- Business Name
- Phone Number
- Address
- Ratings *(optional)*

### 4. ⏱️ Data Processing Buffer
- Adds delay to ensure proper data fetching
- Prevents API throttling

### 5. 📥 Lead Data Retriever
Retrieves structured scraped data from the extractor.

### 6. 🧹 Filter Valid Leads
Removes:
- Missing phone numbers
- Incomplete entries
- Invalid data

### 7. 🧾 Format Lead Data
- Converts raw data into clean JSON format
- Ready for CRM or database use

### 8. 💾 Save to Google Sheets
- Automatically appends valid leads
- Organized and easy to access

---

## 📊 Output Example

| Business Name | Phone Number | Location | Category |
|---------------|-------------|----------|----------|
| ABC Cafe | 9876543210 | Delhi | Cafe |
| XYZ Gym | 9123456780 | Mumbai | Fitness |

---

## 🚀 Use Cases

- 🏢 Lead generation agencies
- 👤 Freelancers (cold outreach)
- 💼 SaaS startups
- 📣 Marketing teams
- 📍 Local business prospecting

---

## 🔧 Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/nikhil-ai-insights/business-lead-generation-ai.git
```

2. **Import workflow into n8n**

3. **Configure the following:**
   - Google Sheets credentials
   - API endpoints (if used)
   - Input parameters

4. **Run the workflow 🚀**

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add the following:

```env
GOOGLE_SHEETS_API_KEY=your_key
SCRAPER_API_KEY=your_key
```

---

## 📈 Future Improvements

- [ ] CRM integration (HubSpot, Zoho)
- [ ] Email automation (cold outreach)
- [ ] WhatsApp automation
- [ ] AI lead scoring system
- [ ] Dashboard analytics

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Submit a pull request

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Nikhil Kumar**
🔗 GitHub: [@nikhil-ai-insights](https://github.com/nikhil-ai-insights)

---

## ⭐ Support

If you find this project useful:

- ⭐ **Star** the repo
- 🍴 **Fork** it
- 🧠 **Share** with others

---

<div align="center">
  <sub>Built with ❤️ by Nikhil Kumar</sub>
</div>
