This project is an Agentic AI-powered healthcare assistant developed to help a clinic proactively identify high-risk chronic disease patients who require follow-up care.
The AI agent autonomously retrieves patient information using specialized tools, analyzes clinical data using the Gemini Large Language Model (LLM), prioritizes patients based on clinical risk, and generates follow-up recommendations for the care coordination team.

#Features : 
Patient data loading and exploratory data analysis (EDA)
AI-powered autonomous clinical reasoning
Tool-based agent architecture
Single patient clinical risk assessment
Missed appointment follow-up prioritization
Automated recommendation generation
Export results to CSV
Visualizations using Matplotlib and Seaborn

#Workflow : 
Patient Dataset (CSV)
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Agent Tools
(get_patient,
get_vitals,
get_lab_results,
get_notes,
get_appointment)
        │
        ▼
Gemini LLM
        │
        ▼
Autonomous Tool Calling
        │
        ▼
Clinical Risk Assessment
        │
        ▼
Follow-up Recommendations
        │
        ▼
CSV Report Generation
