# karshakamithra



Problem Statement
Farmers in the current agricultural market system face low income and limited control over their produce due to the involvement of multiple intermediaries.

Despite being the primary producers, farmers often receive only a small portion of the final market price, while buyers pay significantly higher costs due to added commissions, transportation, and storage layers.

Additionally, the system lacks:

Price transparency
Direct communication between farmers and buyers 
Efficient and fair distribution mechanisms

On the other hand, completely removing middlemen introduces new challenges such as:

Logistics management
Demand uncertainty
Limited technological accessibility for farmers


Project Description

This project proposes a digital farmer–buyer interface platform designed to improve transparency, fairness, and efficiency in agricultural trade.

The system enables farmers to directly list their produce by uploading real-time images, specifying quantity, and setting expected prices. Buyers—both wholesale and retail—can view these listings and make informed purchasing decisions based on clear, visible data.

To ensure flexibility and practicality, the platform supports two types of buyers:

Wholesale buyers, who purchase in bulk and manage transportation either independently or through shared farmer logistics systems.
Retail buyers, who purchase smaller quantities and receive products through integrated delivery partners or local distribution networks.

Unlike traditional systems that rely heavily on intermediaries, this platform reduces unnecessary layers while still maintaining essential support functions such as logistics coordination and transaction handling.

Additionally, the system incorporates trust-building mechanisms like image verification, transparent pricing, and buyer categorization, ensuring that both farmers and buyers engage in a reliable and informed marketplace.

By balancing direct interaction with structured support, the platform aims to increase farmer income, reduce buyer costs, and create a more sustainable and equitable agricultural ecosystem


Google AI Usage

 GEMINI,firebase, antigravity

 How Google AI Was Used

 
1. Multilingual Voice AssistantThe most critical integration is the Voice AI Advisor found in the Farmer Portal.Speech-to-Text Integration: The project uses the Web Speech API to capture a farmer's spoken query in their native language (such as Malayalam or Hindi) and convert it into text.Natural Language Processing (Gemini): This text is sent to the Gemini 1.5 Flash model via a secure API call. The AI is prompted to act as a "Professional Indian Agriculture Expert".Context-Aware Responses: Gemini analyzes the farmer's specific question—whether it's about crop diseases, pest control, or soil health—and generates a concise, practical response in the same local language script.2. Expert Farming Knowledge BaseInstead of a simple "if/else" search system, the project leverages the generative capabilities of Gemini to act as a dynamic knowledge base:Problem Solving: Farmers can describe symptoms of a failing crop, and the AI uses its training data to predict environmental stress or identify potential diseases.Optimization Strategies: In advanced versions of the platform, the AI can analyze real-time data points (like temperature or resource usage) to provide specific "Optimization Strategies" for city or campus resource management.3. Smart Market InsightsWhile the Buyer Marketplace primarily handles transactions, AI is used to enhance the user experience:Automated Categorization: AI can assist in categorizing produce listed by farmers to ensure buyers find what they need efficiently.Logistics Intelligence: The system includes logic to differentiate between "Retail Delivery" and "Bulk Trucking" based on quantity, a process that can be further optimized by AI to predict the best transport routes and methods.Technical Integration SummaryThe integration is achieved through a REST API connection:Endpoint: https://generativelanguage.googleapis.com/v1/models/gemini-1.5-flash:generateContent.Request: A JSON payload containing the user's question and a "system instruction" that defines the AI's persona as an agricultural expert.Response: A high-speed, low-latency text output that is rendered instantly in the project's chat window.

Proof of Google AI Usage

https://docs.google.com/document/d/1T11iVput0YTFQpOg3m-KnXj5hTLGEvQyjbB8q9emEoo/edit?usp=sharing

Screenshots
Add project screenshots:

https://docs.google.com/document/d/1S5_1qwfqOMNm6F-Gdd65B0RmpSNLGObSvbXmHuvtMkY/edit?usp=sharing

