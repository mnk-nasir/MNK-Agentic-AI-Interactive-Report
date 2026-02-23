MNK Agentic AI Interactive Report

An interactive single-page application (SPA) designed to educate users on the transition from traditional Generative AI (Chatbots) to Agentic AI (Autonomous Coworkers). This project features real-time LLM integration using the Gemini 2.5 Flash API.

🚀 Features

Interactive Evolution Chart: A Radar chart (Chart.js) comparing Chatbot vs. Agent capabilities.

✨ Gemini Agent Brainstormer: A live tool that uses the Gemini 2.5 Flash API to architect an autonomous agent blueprint based on user input.

Agentic Loop Simulation: A visual step-by-step console and flow diagram demonstrating self-correction and iterative refinement.

Information Architecture: Thematic sections including the "Anatomy of an Agent" and "Strategic Outlook."

Responsive Design: Built with Tailwind CSS for seamless viewing on mobile, tablet, and desktop.

🛠️ Technical Stack

Frontend: HTML5, Tailwind CSS

Visualization: Chart.js

Intelligence: Google Gemini 2.5 Flash API

State Management: Vanilla JavaScript

📥 Getting Started

Clone the code: Copy the contents of MNK_Agentic_AI_Interactive_Report.html.

API Key: The application expects an apiKey variable. In a local environment, you would replace const apiKey = ""; with your Google AI Studio key.

Run: Simply open the .html file in any modern web browser.

🧠 How the Brainstormer Works

The Brainstormer uses the generateContent endpoint with a Structured JSON Response. It sends a system prompt to the model defining it as an "Agentic AI Architect." The model returns a JSON object containing:

agent_name

steps (Workflow)

tools_required

self_correction_example

This data is then dynamically injected into the UI to create a custom blueprint.

📜 License

Distributed under the MIT License.
