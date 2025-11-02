# Prompting Guide for AI Browser

[AI Browser](https://aibrowser.surf) allows anyone to build and deploy AI browser agents for web automation by writing simple prompts. Anyone with prompting experience can create AI browser agents that can automate any website without writing a single line of code.

## ✨ Features of AI Browser

- 🤖 **Prompt-Based Creation** - Build AI browser agents using simple prompts
- 👀 **Live View Agent** - Watch your agents work in real-time with live browser preview
- ⏰ **Smart Scheduling** - Set your browser agents to run automatically at specified times
- 🌐 **Community Hub** - Access pre-built agents for popular websites and services
- 🔧 **Playwright Powered** - Built on robust browser automation technology

## 🚀 Quick Start

### 1. Create Your First Agent

Simply describe what you want your agent to do:

```
"Go to Amazon, search for wireless headphones under $100, and save the top 3 results to a spreadsheet"
```

### 2. Watch It Work

Use our Live View feature to see your agent navigate websites in real-time, making adjustments as needed.

### 3. Schedule & Deploy

Set your agent to run daily, weekly, or at custom intervals to automate repetitive tasks.

## 📖 Usage Examples

### E-commerce Price Monitoring

**Prompt:** "Check the price of iPhone 15 on BestBuy every morning at 9 AM and send me an email if the price drops below $800"

**Agent Configuration:**
- **Action:** Navigate to BestBuy
- **Search:** "iPhone 15"
- **Extract:** Price information
- **Condition:** If price < $800
- **Notify:** Send email alert

### Social Media Management

**Prompt:** "Post my blog articles to LinkedIn every Tuesday at 2 PM, including the title, summary, and link"

**Agent Configuration:**
- **Action:** Navigate to user's blog
- **Action:** Click latest blog post
- **Extract:** Blog data
- **Schedule:** Weekly (Tuesdays, 2 PM)
- **Action:** Create LinkedIn post
- **Content:** Auto-generate from blog data

### Data Collection

**Prompt:** "Collect job listings for 'Software Engineer' positions from Indeed daily and save them to Google Sheets"

**Agent Configuration:**
- **Action:** Navigate to Indeed.com
- **Search:** "Software Engineer"
- **Extract:** Job title, company, location, salary
- **Export:** Google Sheets integration
- **Schedule:** Daily at 6 AM

## 🎯 Building Browser Agents - Best Practices

### 1. Be Specific and Atomic

**Good Prompts:**
- "Click the 'Sign In' button in the top right corner"
- "Type my email address into the email field"
- "Extract the product price from the main product page"

**Avoid Vague Instructions:**
- "Do something interesting on the page" (too broad instruction)
- "Fill out the form and submit it" (combine multiple actions)

### 2. Use Variables for Sensitive Data

Instead of hardcoding sensitive information in your prompts, use variables:

**Action Field:** "Type %email% into the email field"
**Variables Section:** 
- email: "john.doe@example.com"

This keeps your personal information secure.

### 3. Start Simple, Then Expand

Begin with basic single-page interactions:

**Beginner:** "Click the search button"
**Intermediate:** "Search for products and filter by price range"
**Advanced:** "Compare prices across multiple e-commerce sites"

### 4. Use Community Agents

Browse our community library for pre-built agents:
- **Wellfound Job Hunt Agent**
- **Indeed AutoApply to Jobs**
- **Amazon Price Tracker**
- **LinkedIn Auto-Poster**
- **Google Maps Business Scraper**
- **Twitter Engagement Bot**
- **News Article Collector**

## 🔧 Platform Interface

### Prompt Based Builder

Our visual interface translates your prompts into actionable steps:

1. **Action Field** - Describe what you want to do in natural language
2. **Variables Panel** - Define reusable values and sensitive data
3. **Conditions** - Set up if/then logic for smart decision making
4. **Scheduling** - Configure when and how often to run

### Action Types (Depricated)

- **GOTO:** Go to specific URLs or pages
- **ACT:** Interact with buttons, links and enter text into input fields
- **Extract:** Collect data from pages
- **Wait:** Pause for page loading or specific conditions
- **IF:** Add logic for different scenarios

## 📊 Live View & Monitoring

### Real-Time Execution

Watch your agents work with our Live View feature:
- See the browser in action
- Monitor each step as it happens
- Pause or stop execution if needed
- Debug issues in real-time

### Execution Logs

Track your agent's performance:
- Success/failure rates
- Execution time
- Error messages and solutions
- Historical run data

## ⏰ Scheduling Options

### Flexible Timing

Set your agents to run:
- **One-time:** Run once at a specific date/time
- **Daily:** Every day at chosen time
- **Weekly:** Specific days of the week
- **Monthly:** On specific dates
- **Custom:** Complex schedules with cron expressions

## 🌐 Community & Marketplace

### Discover Pre-Built Agents

Browse agents created by the community:
- **E-commerce:** Price monitoring, inventory tracking
- **Social Media:** Content posting, engagement automation
- **Data Collection:** Web scraping, research automation
- **Productivity:** Task automation, report generation

### Share Your Creations

Contribute to the community:
- Publish your successful agents
- Help others with similar automation needs
- Earn recognition and feedback
- Build your automation portfolio

## 💡 Advanced Tip

### Handle Dynamic Content

For pages with changing layouts:
- Use descriptive selectors: "the blue 'Add to Cart' button"
- Add wait conditions: "wait for the price to load"
- Use fallback actions: "if the first button isn't found, try the second"

## 🚨 Important Notes

- **Rate Limiting:** Respect website terms of service
- **Data Privacy:** Keep sensitive information secure using variables
- **Monitoring:** Check agent's performance regularly for optimal results
- **Updates:** Browser agents may need adjustments when websites change layouts

## 📄 Pricing

- **Free Tier:** 10 browser hours per month
- **Pro Plan:** Upto 1,000 browser hours per month, advanced scheduling, priority support
- **Enterprise:** Custom solutions, dedicated support, on-premise deployment

## 🆘 Getting Help

- **Support Ticket:** [Direct help from our team](mailto:hello@aibrowser.surf)

---

**Made with 💌 for everyone who wants to automate the web**
