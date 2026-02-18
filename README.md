#Spotify Dashboard in Power BI
📌 Overview
This project demonstrates how to build an interactive Spotify Dashboard using Power BI and DAX measures. It transforms raw Spotify data (such as the Global Top 50 chart) into meaningful insights, allowing analysis of songs, artists, popularity trends, and explicit vs. non‑explicit tracks.

The project leverages the DAX Query View feature in Power BI to define multiple measures in a single script, saving time and improving efficiency.

🚀 Features
Import Spotify datasets (CSV format) into Power BI.

Define a comprehensive library of DAX measures including:

Total Songs, Distinct Songs, Distinct Artists

Average, Max, and Min Popularity

Explicit vs. Non‑Explicit song counts and percentages

Duration analysis (average, max, min in minutes)

Position‑based metrics (e.g., Position 1 songs and artists)

Album type breakdown (singles vs. albums)

Artist‑scoped and Year‑scoped measures

Build visuals such as KPI cards, bar charts, donut charts, and tables.

Create a professional‑grade dashboard for portfolio or business use.

🛠️ Setup Instructions
Get Data:

Download your Spotify listening history or use a public dataset (e.g., Global Top 50).

Save the file in CSV format.

Import into Power BI:

Open Power BI Desktop.

Go to Home → Get Data → Text/CSV.

Load the dataset and rename the table (e.g., Top-50-world).

Enable DAX Query View:

Go to File → Options and settings → Options → Preview features.

Enable DAX Query View and restart Power BI.

Add Measures:

Open DAX Query View.

Paste the provided DAX script to define all measures.

Click Apply all updates to add them to your model.

Build Dashboard:

Use Report View to design visuals with the new measures.

Examples: KPI cards for total songs, bar charts for album types, donut charts for explicit vs. non‑explicit songs.
