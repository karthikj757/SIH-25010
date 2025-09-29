# Smart India Hackathon Workshop
# Date:29.09.2025
## Register Number:25017529
## Name:karthik J
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
We propose DigiKisan, an AI-powered, multilingual mobile application designed to be a farmer's all-in-one digital assistant. It aims to bridge the information gap by providing personalized, data-driven, and timely advice directly to small and marginal farmers in their native language.

How It Addresses the Problem
Personalized Advisory: Instead of generic advice, DigiKisan's core AI engine analyzes the user's specific soil type, local weather data, and farm history to recommend the most suitable and profitable crops.

Overcoming Barriers: The app features a simple, icon-based interface and a vernacular voice assistant (initially in Punjabi, Hindi, and English) to overcome language and digital literacy hurdles. Farmers can simply ask questions like, "What is the best fertilizer for my wheat crop?" and get an instant voice response.

Cost Reduction & Sustainability: A Smart Fertilizer Calculator recommends the precise amount of NPK and micronutrients needed, preventing overuse, reducing input costs, and promoting soil health.

Instant Help: The Pest & Disease Detector allows a farmer to upload a photo of an affected plant. A computer vision model instantly identifies the issue and suggests both organic and chemical treatment options, reducing reliance on local shopkeepers.

Improved Profitability: A Market Linkage feature provides live commodity prices from nearby mandis (local markets), empowering farmers to sell their produce at the most opportune time and price.

Innovation and Uniqueness
The innovation of DigiKisan lies in its hyper-personalized and integrated approach. While other apps may offer standalone features like disease detection or market prices, DigiKisan combines everything into a single, seamless platform. Its uniqueness comes from the voice-first interface designed for accessibility and the feedback loop, where the AI model continuously learns and improves its recommendations based on the outcomes reported by the farmers, creating a smarter system over time.


## Technical Approach
The innovation of DigiKisan lies in its hyper-personalized and integrated approach. While other apps may offer standalone features like disease detection or market prices, DigiKisan combines everything into a single, seamless platform. Its uniqueness comes from the voice-first interface designed for accessibility and the feedback loop, where the AI model continuously learns and improves its recommendations based on the outcomes reported by the farmers, creating a smarter system over time.

Technical Approach
Our implementation strategy focuses on building a scalable, robust, and accessible platform using modern technologies.

Technologies to be Used
Mobile App (Frontend): Flutter for cross-platform development (Android & iOS) from a single codebase.

Backend: Python with the Django framework to build RESTful APIs. Python's extensive libraries for AI/ML make it the ideal choice.

Database: A combination of PostgreSQL for structured user and farm data, and MongoDB for unstructured data like images for pest detection.

AI/ML Models:

Crop Recommendation: A Random Forest classifier trained on soil parameters, weather data, and crop labels.

Pest/Disease Detection: A Convolutional Neural Network (CNN) like MobileNetV2, optimized using TensorFlow Lite to run efficiently on mobile devices, even with low connectivity.

Voice Assistant (NLP): Google's Dialogflow for robust intent recognition and multilingual support, integrated with regional Speech-to-Text and Text-to-Speech engines.

Cloud Infrastructure: Google Cloud Platform (GCP) for hosting, using services like Compute Engine for the backend, Cloud Storage for images, and Cloud SQL for the database.

Data APIs: Integration with India Meteorological Department (IMD) for weather forecasts and the Agmarknet portal for real-time market prices.

Methodology and Process
The development will follow an agile methodology. The core user journey is illustrated below:

Onboarding: The user registers with a mobile number. The app captures the user's location via GPS to provide localized advisories.

Dashboard: The user sees a personalized dashboard with today's weather, key market prices, and critical alerts.

Advisory Flow:

The user inputs soil health data (or allows the app to fetch it from government databases where available).

The AI model processes this data along with live weather feeds.

The app presents a list of recommended crops, along with projected yield and profitability.

Pest Detection Flow:

The farmer notices a problem and opens the "Protect Crop" feature.

They take a photo of the affected plant leaf.

The image is processed by the on-device CNN model.

The app identifies the disease/pest and provides clear, actionable steps for treatment.

Information Access: The user can ask the voice assistant questions at any time or check the latest mandi prices with a single tap.

## Feasibility and Viability
Technical Feasibility: The proposed technologies are mature and well-supported. Open-source datasets (e.g., PlantVillage for disease images) and government data portals provide the necessary data for training our AI models. Initial prototypes can be developed rapidly.

Operational Feasibility: The app can be distributed via the Google Play Store. For outreach and user training, we will partner with local Krishi Vigyan Kendras (KVKs), agricultural universities, and farmer cooperatives.

Economic Viability: The initial development can be bootstrapped or funded by government grants. The business model is Freemium. All core advisory services will be free for individual farmers. Revenue can be generated through premium features for large farms, data analytics for agri-businesses, and targeted advertisements for farm inputs (without compromising user trust).

Potential Challenges and Mitigation
Challenge: Poor internet connectivity in rural areas.

Strategy: Key features like pest detection will use on-device models to work offline. Data can be synced in the background when a connection becomes available.

Challenge: Low digital literacy among farmers.

Strategy: An intuitive, icon-heavy UI combined with a powerful voice assistant. We will create video tutorials in local languages and conduct on-ground training workshops.

Challenge: Gaining the trust of farmers.

Strategy: Launch pilot programs in select districts of Punjab. We will collaborate with trusted local agricultural extension officers to demonstrate the app's value and gather testimonials to build credibility.

## Impact and Benefits
Increased Farmer Income: By increasing crop yield by an estimated 20-30% and enabling better price realization, the app will directly boost farmers' income and financial stability.

Reduced Input Costs: Optimized fertilizer and pesticide usage will lower farm expenditure significantly.

Social Impact:

Empowerment: Farmers will be empowered with knowledge, reducing their dependence on intermediaries and enabling data-driven decision-making.

Digital Inclusion: The project will promote digital literacy and bring the benefits of modern technology to rural communities.

Environmental Impact:

Sustainable Farming: The solution promotes the judicious use of chemicals, leading to improved soil health, reduced water pollution, and a more sustainable agricultural ecosystem.

Climate Resilience: Weather-based alerts will help farmers adapt to and mitigate the effects of climate change.


## Research and References
Our solution is built upon extensive research and existing data sources.

Reports and Statistics:

NABARD All India Rural Financial Inclusion Survey, 2022: Highlighting that 86% of Indian farmers are small and marginal.

World Bank studies on the impact of ICT in agriculture, showing significant yield increases.

Technical References and Datasets:

PlantVillage Dataset: An open-source repository of tens of thousands of images of healthy and diseased plant leaves, crucial for training our CNN model. (Link: https://plantvillage.psu.edu/)

data.gov.in: Indian government's open data portal, used for accessing datasets on soil health, weather patterns, and historical crop production.

Agmarknet: Portal for accessing daily market price data from mandis across India. (Link: https://agmarknet.gov.in/)

Academic Research:

"Crop Yield Prediction Using Machine Learning: A Systematic Literature Review" - A survey of various ML models applicable for our crop recommendation engine.

"A review on deep learning approaches for the diagnosis of plant diseases" - Research validating the use of CNNs for accurate, image-based plant disease detection.




