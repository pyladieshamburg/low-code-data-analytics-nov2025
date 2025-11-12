# Julius AI – Platform Overview

Julius AI is an integrated environment for exploring, analyzing, and automating data workflows — all in natural language.  
It combines chat-style exploration, structured notebooks, and shareable dashboards in one interface.

## Main Sections

### 1. Chats
- Quick, conversational exploration.  
- Ask questions about your data directly (e.g., "Show me total sales by month.").  
- Ideal for ad-hoc insights, brainstorming, and data discovery.  
- You can upload files right in the chat or pull from connected data sources.

### 2. Notebooks
- Structured environments for step-by-step workflows.  
- Each notebook consists of cells (text, prompt, user input, file upload).  
- Supports saving, scheduling, and re-running analyses.  
- Great for reproducible projects or tutorials — each step is documented and executable.

### 3. Dashboards
- Visual layer for presenting insights.  
- Combine multiple charts or tables from your analyses.  
- Designed for sharing with teams or embedding in reports.  
- Dashboards auto-update if connected to live data sources.

### 4. Files
- Central place for uploaded CSVs, Excel sheets, and datasets created by Julius.  
- Files are versioned and can be re-used across notebooks and chats.  
- Uploaded files appear in the sidebar for quick access.

### 5. Data Connectors
- Secure integrations for cloud and business data sources:  
  Google Drive · Dropbox · Airtable · Notion · HubSpot · APIs · Databases.  
- Enables live connections — you don’t need to re-upload static files.  
- Configure connectors once under **Settings → Data Connectors**.

### 6. Custom Agents
- Create specialized AI assistants that follow your instructions.  
- Example: “Marketing Analyst Bot” or “Finance Auditor Agent.”  
- Each agent can use specific data sources, goals, and prompt styles.  
- Reuse them across notebooks or teams for consistent automation.

### 7. Teams & Collaboration
- Under **Create a Team**, you can invite colleagues to share notebooks, dashboards, or datasets.  
- Control access rights (view / edit / run).  
- Shared workspaces allow collaborative building and review.

### 8. Notebook Templates
- Pre-built workflows for common tasks:  
  - Customer segmentation  
  - ROI analysis  
  - Retention tracking  
  - Data cleaning & profiling  
- Use them as starting points and adapt steps to your dataset.

# Notebook Cell Types

Each Julius AI notebook consists of cells — modular, executable blocks that define a step in your analysis.  
Cells can be added (+ button or B shortcut), removed (trash icon), or reordered.

## 1. Prompt Cell
Ask Julius to perform an action or analysis in plain English.

Example:
"Create a summary table showing average revenue per region."

- Executes when you click ▶ (run) or press Cmd/Ctrl + Enter.  
- Julius interprets the instruction, runs the necessary code, and returns output (tables / charts / text).  
- Use for most analysis or visualization steps.

## 2. File Upload Cell
Attach local data to your workflow.

Example:
Upload customers.csv

- Once uploaded, the file icon appears in the cell.  
- Julius automatically detects the structure (columns, types, etc.).  
- Uploaded files stay linked to that notebook for reuse.

## 3. User Input Cell
Create an interactive step that asks the user for a value.

Example:
Question: "What type of plot should I make?"
Example Responses: scatter · line · box

- During execution, the workflow pauses for input.  
- The user types an answer (e.g. scatter) and Julius continues dynamically.  
- Perfect for customizable reports or guided templates.

## 4. File Upload vs. Prompt vs. User Input — Quick Comparison

| Cell Type        | Purpose                                  | Typical Use Case                              | Output                         |
|------------------|------------------------------------------|-----------------------------------------------|--------------------------------|
| Prompt           | Instruct Julius to analyze / visualize   | "Summarize CLV by segment"                    | Table, chart, or text summary  |
| File Upload      | Attach dataset                           | "Upload customers.csv to analyze next"        | Data object accessible later   |
| User Input       | Request value from user during workflow   | "Select metric to analyze → ROI or CLV?"      | Dynamic branch or new prompt   |
