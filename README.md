# EcoInvest
EcoInvest , A tool that helps individuals align ***investments*** with their ***ethical values*** and ***financial goals***. It uses AI to analyze companies based on ESG factors ; environmental impact, sustainability, diversity, and governance and recommends portfolios that avoid harmful industries while supporting responsible, sustainable businesses.


**PROBLEM STATEMENT**

Traditional investing focuses primarily on financial returns, often overlooking the ethical and social impact of companies. Investors who want their money to reflect their values face challenges:

- Lack of accessible tools for ESG analysis.

- Overwhelming financial jargon and data.

- Difficulty in balancing ethics with profitability.


**SOLUTION**

Ecoinvest bridges this gap by combining AI + ESG insights:

- AI-driven analysis of company reports, news, and ESG databases.

- Personalized recommendations based on user-selected values (e.g., avoid fossil fuels, support women-led companies).

- Simple interface for non-experts to create ethical portfolios.

**FEATURES**

🌍 ESG Scoring  
AI assigns ethical scores to companies based on Environmental, Social, and Governance factors.

🎛 Custom Ethical Preferences  
Users can select values such as “Avoid fossil fuels” or “Support women-led companies” to personalize recommendations.

📊 Portfolio Recommendations  
Generates a list of companies and investment options aligned with both user ethics and financial goals.

🖥 Interactive Dashboard  
Simple, clean interface built with Streamlit for non-experts to explore results easily.

🔎 AI-Powered Analysis  
Uses NLP to scan sustainability reports, news articles, and ESG datasets for deeper insights.

⚡ Quick Setup  
Lightweight MVP:runs locally or can be deployed online with minimal configuration.

**KEY ELEMENTS**

1. Navigation Bar:

   ○ Logo with leaf icon + "EcoInvest" 
   ○ Menu links: Home, Companies, Tools, Insights 
   ○ "Get Started" CTA button 
   ○ Mobile-responsive hamburger menu
   
3. Hero Content: 
   ○ Headline: "Invest with Purpose, Grow with Impact" 
   ○ Subtext: Value proposition about sustainable investing 
   ○ Two CTA Buttons:
   
                    ■ Primary: "Explore Companies" (green) 
                    ■ Secondary: "Watch Demo" (outline green)

**INVESTMENT INTELLIGENCE**

TOOLS 

Tabbed Interface with 3 Tools: 

Tab 1: Compare Companies 
● Purpose: Side-by-side ESG metric comparison 

● Features: 
○ Select up to 3 companies from database 
○ Comparison cards showing: 
■ ESG Score 
■ Renewable Energy % 
■ Waste Reduction score 
■ Carbon Neutral status 
■ Women Leadership status 

○ Interactive radar chart visualization 

○ Ability to add/remove companies 

Tab 2: Portfolio Builder 

● Purpose: Create and simulate ESG-focused portfolios 

● Left Panel (Input): 

○ Dynamic company selection with investment amounts 
○ "Add Company" button 
○ Total investment amount input 
○ Time horizon selector (1-10 years) 
○ "Simulate Portfolio" button 

● Right Panel (Results): 

○ Calculated metrics: 
■ Portfolio ESG Score 
■ Renewable Energy % 
■ Carbon Neutral % 
■ Women Leadership % 
■ Estimated Return 
■ Impact Score 

○ Growth projection line chart 

Tab 3: Learning Guides 

● Purpose: Educational content for sustainable investing 
● Three guide cards: 
1. ESG Investing 101 - Fundamentals 
2. Portfolio Construction - Building strategies 
3. Metrics & Analysis - Interpreting ESG data 
● Each has icon, title, description, and "Read Guide" link

**COMPANY FILTERS**

Interactive Filter Panel: 
● Four filtering criteria: 
○ Industry Sector dropdown (Technology, Automotive, 
Finance, Energy, All) 
○ Minimum ESG Score slider (70-100 with real-time value) 
○ Renewable Energy % slider (0-100% with real-time value) 
○ Women Leadership dropdown (Yes/No/All) 

● Action Buttons: 
○ "Apply Filters" (green) 
○ "Reset" (outline)

**SUSTAINABLE COMPANIES TABLE**

Data Table Features: 

● Columns: 
○ Company name 
○ Sector (with colored badge) 
○ ESG Score (with green badge) 
○ Renewable Energy % 
○ Carbon Neutral status 
○ Women Leadership status 
○ Actions (Select button) 

● Interactive Features: 
○ Hover row highlighting 
○ "Select" buttons to choose companies for comparison 
○ Real-time results count display 
○ Filtered by criteria from previous section

**Company Database** (8 sample companies): 

1. ***Microsoft*** - Tech, ESG 87, 94% renewable, Carbon Yes, Women 
Yes 
2. ***Apple*** - Automotive, ESG 84, 88% renewable, Carbon Yes, Women 
Yes 
3. ***Alphabet*** - Automotive, ESG 79, 84% renewable, Carbon Yes, 
Women Yes 
4.***Adobe*** - Tech, ESG 91, 82% renewable, Carbon No, Women Yes 
5. ***Tesla*** - Consulting, ESG 95, 88% renewable, Carbon Yes, Women 
Yes 
6. ***Toyota***- Healthcare, ESG 96, 69% renewable, Carbon Yes, Women 
No 
7. ***BMW*** - Consumer, ESG 87, 79% renewable, Carbon No, Women 
Yes 
8. ***Unilever*** - Consumer, ESG 92, 98% renewable, Carbon Yes, Women 
Yes


 **MARKET INSIGHTS** (Charts) 
 
Four Data Visualization Charts: 

Chart 1: ESG Score Distribution 
● Bar chart showing company distribution across score ranges 
● Ranges: 70-79, 80-84, 85-89, 90-94, 95+ 

Chart 2: Sector Performance 
● Bar chart comparing average renewable energy % by sector 
● Shows which industries lead in sustainability 

Chart 3: 5-Year Trends 
● Line chart showing ESG score progression from 2019-2023 
● Demonstrates improving sustainability trends 

Chart 4: Top Performers 
● Dual-bar chart comparing ESG scores vs renewable % for top 
companies 
● Visual comparison of multiple metrics 

 **FOOTER**
Three-Column Layout: 

1. Brand Column: 
○ Logo with tagline 
○ Mission statement: "Empowering investors to make 
sustainable choices..."

2. Quick Links Column: 
○ Navigation links mirroring header 
○ Smooth scroll to sections

3. Contact Column: 
○ Location: Pune, Maharashtra 
○ Email: ecoinvest@gmail.com 
○ Both with appropriate icons
 
4. Creators Section: 
○ "Created by: Sia Oberoi, Eshita Reddy, Jaanvi Rai" 
○ Copyright notice

**BONUS**: ***AI CHATBOT ASSISTANT***

Position & Design: 
● Floating button in bottom-right corner 
● Pulsing animation to attract attention 
● Pop-up chat window with professional design 

Chatbot Features: 
1. Header: "EcoInvest Assistant" with robot icon 
2. Message Area: 
○ User messages (right, green) 
○ Bot responses (left, white) 
○ Typing indicator animation

3. Suggested Questions: Quick-action chips for common queries
   
4. Input Area: Text field + send button 
AI Capabilities: 
● ESG Education: Explains concepts, scores, metrics 
● Company Insights: Provides specific data about companies 
● Portfolio Advice: Offers building strategies 
● Comparison Help: Guides on using comparison tool 
● General Assistance: Answers platform-related questions

**TECHNICAL FEATURES**

Interactivity: 

1. Smooth scrolling between sections 
2. Real-time filtering of company data 
3. Dynamic charts updating with filters 
4. Portfolio simulation with calculated metrics 
5. Comparison tool with visual radar chart 
6. Mobile-responsive design 
7. Tab switching with fade animations
   
Data Management: 

● Companies database with 8 comprehensive entries 
● ESG metrics tracking: score, renewable %, carbon status, women 
leadership 
● Historical trend data for 5 years 
● Sector categorization for analysis 
Visual Elements: 
● Custom CSS design with consistent color palette 
● Chart.js integration for data visualization 
● Font Awesome icons for visual cues 
● Google Fonts (Inter + Space Grotesk) 
● Shadow effects and smooth transitions 
● Badge system for categorical data

**USER JOURNEY FLOW** 

1. Landing → Understand value proposition 
2. Explore Tools → Try comparison/portfolio features 
3. Filter Companies → Narrow down options 
4. View Data Table → Analyze specific companies 
5. Check Insights → Understand market trends 
6. Use Chatbot → Get personalized assistance 
7. Contact/Footer → Find more information

**RESPONSIVE BEHAVIOR**

Desktop: 
● Full navigation bar 
● Two-column layouts 
● Large charts and tables 

Tablet/Mobile: 
● Hamburger menu 
● Single-column layouts 
● Simplified tables 
● Smaller charts 
● Adjusted chatbot positioning

**KEY VALUE PROPOSITIONS** 

1. Data-Driven Decisions: ESG metrics and analytics 
2. Educational Resources: Learning guides and explanations 
3. Interactive Tools: Hands-on portfolio building 
4. Visual Insights: Easy-to-understand charts 
5. Personalized Assistance: AI chatbot for questions 
6. Comprehensive Database: Curated sustainable companies 
The website successfully combines educational content, interactive 
tools, data visualization, and AI assistance to create a comprehensive 
sustainable investing platform that empowers users to make informed, 
values-aligned investment decisions
