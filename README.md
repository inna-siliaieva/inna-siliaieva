# Hi, I'm Inna 👋

### Junior Automation & Data Specialist

Focused on practical workflow automation, data processing, and business process optimization.

I build practical automation and data-processing workflows using:

- n8n
- Excel
- Python
- SQL
- API integrations
- Data transformation and reporting
- Business process automation


## Featured Projects

### 1. n8n Sales Data Pipeline

End-to-end sales data processing and reporting workflow built with n8n.

The workflow:

- retrieves sales data via API
- transforms and validates records
- calculates order totals
- filters delivered orders
- creates regional summaries
- generates a CSV report
- sends processed data through API endpoints

➡️ [View the project](https://github.com/inna-siliaieva/n8n-sales-data-pipeline)

---

### 2. n8n Automated Reporting Workflow

Automated data processing and reporting workflow built with n8n.

The workflow:

- retrieves order and customer data
- merges multiple data sources
- calculates order totals
- sorts and filters records
- creates regional summaries
- generates CSV reports
- prepares Discord reporting messages
- sends reports to Discord
- uploads generated files to an external endpoint

➡️ [View the project](https://github.com/inna-siliaieva/n8n-automated-reporting-workflow)

### 3. n8n API Integration Pipeline

API integration workflow built in n8n to combine data from multiple sources and process it through business rules.

The workflow:

- retrieves paginated order data from an API
- retrieves customer data from a second API
- merges orders with customer information
- aggregates enriched order data
- filters records based on order status
- routes enterprise customers through priority processing
- routes other customers by region
- processes priority orders in controlled batches
- uses automatic retry logic for temporary API failures
- continues through a fallback branch when the customer API fails
- finalizes the pipeline with a confirmation request

**Key concepts:** REST API integration, pagination, data merging, conditional routing, batch processing, retry logic, and error handling.

➡️ [View the project](https://github.com/inna-siliaieva/n8n-api-integration-pipeline)

### 4. Webhook-Driven Order Processing System

Modular n8n workflow for secure order intake, validation, storage, duplicate prevention, and reusable order processing.

The workflow:

- receives orders through a webhook
- validates required order fields
- prevents duplicate records
- stores orders in an n8n Data Table
- processes orders through a reusable sub-workflow
- calls an external API for order processing
- updates order status and processing timestamps
- returns structured success or validation responses

**Key concepts:** n8n, webhooks, sub-workflows, Data Tables, API integration, validation, duplicate prevention, workflow orchestration.

➡️ [View the project](https://github.com/inna-siliaieva/n8n-webhook-order-processing)

### 5. AI-Powered Customer Feedback Pipeline

AI-powered n8n workflow for customer feedback classification and personalized response generation.

The workflow:

- retrieves customer feedback from an API
- classifies feedback by sentiment, topic, urgency, and key issue
- converts AI output into structured JSON
- uses a Structured Output Parser for reliable results
- applies retry logic for AI processing
- uses different AI models for classification and response generation
- generates a context-aware customer reply
- sends the processed result to an external API endpoint

**Key concepts:** n8n, AI workflow automation, LLM chains, structured outputs, prompt engineering, API integration, JSON parsing, retry logic.

➡️ [View the project](https://github.com/inna-siliaieva/AI-Customer-Feedback-Pipeline)

### 6. AI Customer Service Agent with Tools

AI-powered n8n customer service agent that dynamically selects the appropriate tool based on the user's request.

The workflow:

- receives customer requests through an n8n chat interface
- uses an AI Agent to analyze user intent
- dynamically selects between multiple HTTP tools
- retrieves order status information
- retrieves customer account and subscription details
- retrieves product features and pricing
- extracts request parameters directly from natural-language input
- uses Simple Memory to preserve conversation context
- avoids repeated requests for information already provided by the user
- integrates Groq as the AI model

Key concepts: n8n, AI Agents, tool selection, HTTP Request Tools, REST API integration, dynamic parameters, conversation memory, prompt engineering, Groq.

➡️ [View the project](https://github.com/inna-siliaieva/AI-Customer-Service-Agent-n8n)

### 7. Excel Sales Data Analysis & Reporting

Excel portfolio project focused on practical data processing, analysis, reporting, and visualization.

The project includes:

- cleaning and organizing sales data
- working with Excel Tables
- using `IF` and `SUMIF` formulas
- calculating sales commissions
- regional sales analysis
- monthly performance analysis
- payment-method analysis
- conditional formatting
- summary reporting
- charts and data visualization

**Key skills:** Excel, data cleaning, formulas, reporting, sales analysis, data visualization.

➡️ [View the project](https://github.com/inna-siliaieva/excel-sales-data-analysis)

## Currently Learning

- Advanced n8n workflow automation
- AI agents and AI-powered workflows
- Data analytics automation
- Business process automation

## Tools & Technologies

`n8n` `Excel` `Python` `SQL` `APIs` `JSON` `CSV` `Automation`

## Contact

- GitHub: [inna-siliaieva](https://github.com/inna-siliaieva)
- LinkedIn: coming soon
