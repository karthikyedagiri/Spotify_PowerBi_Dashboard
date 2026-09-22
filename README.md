<img width="1162" height="741" alt="Screenshot 2026-09-22 183055" src="https://github.com/user-attachments/assets/6e30ee61-4804-47d2-b22a-6ad527a1f796" />

# 🎵 Spotify Artist Streaming Dashboard | Power BI

## 📊 Project Overview

The **Spotify Artist Streaming Dashboard** is an interactive Power BI dashboard designed to analyze music streaming data from **2020 to 2025**.

The dashboard provides insights into artist performance, streaming counts, genres, albums, release years, and music characteristics. Interactive filters and visualizations help users explore the data and identify streaming patterns.

---

## 🎯 Objectives

* Analyze total Spotify streaming performance.
* Identify artists with the highest number of streams.
* Understand streaming distribution across different genres.
* Analyze album-level streaming performance.
* Study the relationship between release year and streaming count.
* Explore music characteristics such as popularity, danceability, energy, tempo, and loudness.
* Provide an interactive dashboard for easy data exploration.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel / CSV Dataset**
* **Data Visualization**

---

## 📁 Dataset

The project uses a Spotify artist streaming dataset covering the period **2020–2025**.

### Important Columns

| Column             | Description                      |
| ------------------ | -------------------------------- |
| `track_id`         | Unique track identifier          |
| `track_name`       | Name of the track                |
| `artist_name`      | Name of the artist               |
| `album_name`       | Name of the album                |
| `release_date`     | Track release date               |
| `genre`            | Music genre                      |
| `duration_ms`      | Track duration in milliseconds   |
| `popularity`       | Popularity score                 |
| `danceability`     | Danceability score               |
| `energy`           | Energy score                     |
| `key`              | Musical key                      |
| `loudness`         | Track loudness                   |
| `mode`             | Musical mode                     |
| `instrumentalness` | Instrumentalness score           |
| `tempo`            | Track tempo                      |
| `stream_count`     | Number of streams                |
| `country`          | Country associated with the data |
| `explicit`         | Explicit-content indicator       |
| `label`            | Record label                     |
| `release_year`     | Year of release                  |

---

## 📈 Dashboard Features

### 1. 🎤 Artist Streaming Analysis

A **Clustered Column Chart** is used to compare artists based on their total streaming counts.

This helps identify artists receiving higher levels of streams.

### 2. 🎼 Genre Analysis

A **Pie Chart** displays streaming distribution across genres.

The visualization allows users to understand which genres contribute more to the overall streaming performance.

### 3. 💿 Album Analysis

A **Treemap** is used to visualize streaming performance by album.

Larger sections represent albums with higher streaming counts.

### 4. 📅 Release Year Filter

An interactive **Year Slicer** allows users to filter the dashboard by release year.

Users can select different years from the **2020–2025** period and analyze the corresponding streaming data.

### 5. 📊 Streaming KPI

A **Card/KPI visual** is used to display streaming-related metrics and provide a quick overview of the selected data.

### 6. 📉 Release Year vs Streaming

A **Scatter Chart** is used to analyze the relationship between release year and streaming count.

This helps explore whether tracks released in different years show differences in streaming performance.

### 7. 📈 Artist Streaming Overview

An **Area Chart** provides another view of streaming counts across artists, making it easier to observe differences in artist performance.

---

## 🔄 Data Analysis Process

The project follows a basic data analytics workflow:

```text
Raw Spotify Dataset
        ↓
Data Import
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX / Calculations
        ↓
Data Visualization
        ↓
Interactive Power BI Dashboard
        ↓
Business Insights
```

---

## 🧹 Data Preparation

The dataset was prepared for analysis by working with fields such as:

* Release Date
* Release Year
* Release Month
* Release Quarter
* Day of Week
* Duration
* Popularity
* Streaming Count
* Genre
* Artist
* Album
* Country
* Explicit Content

Additional analytical fields were also created for easier categorization and visualization.

---

## 📊 Power BI Visualizations Used

| Visualization          | Purpose                              |
| ---------------------- | ------------------------------------ |
| Clustered Column Chart | Compare artist streaming counts      |
| Area Chart             | Analyze artist streaming performance |
| Pie Chart              | Analyze genre distribution           |
| Treemap                | Analyze album streaming performance  |
| Scatter Chart          | Compare release year and streams     |
| Card / KPI             | Display key streaming metrics        |
| Slicer                 | Filter data by release year          |

---

## 🎛️ Interactivity

The dashboard includes interactive features such as:

* Year Slicer
* Cross-filtering
* Interactive charts
* Top-N analysis
* Artist-level exploration
* Genre-level exploration
* Album-level exploration

Selecting a value in one visual can dynamically affect other visuals on the dashboard.

---

## 💡 Key Insights

The dashboard can be used to answer questions such as:

* Which artists have the highest streaming counts?
* Which genres generate more streams?
* Which albums perform strongly in terms of streams?
* How does streaming performance vary by release year?
* What is the relationship between release year and streaming count?
* How does artist performance change when different years are selected?

---

## 📂 Project Structure

```text
Spotify-Artist-Streaming-Dashboard/
│
├── README.md
│
├── Spotify_Artist_Streaming.pbix
│
├── Dataset/
│   └── spotify_artist_streaming_2020_2025.csv
│
└── Screenshots/
    └── spotify_dashboard.png
```

> **Note:** The uploaded Power BI file is a `.pbit` template. If you save the completed report as a `.pbix`, you can include the `.pbix` file in the repository instead.

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the Power BI template/report.
3. If using the `.pbit` file, provide the required dataset when prompted.
4. Load the Spotify streaming dataset.
5. Refresh the data.
6. Explore the dashboard using the interactive visuals and year slicer.

---

## 🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Cleaning
* Data Transformation
* Data Modeling
* Power BI
* Power Query
* DAX
* KPI Creation
* Data Visualization
* Interactive Dashboard Design
* Exploratory Data Analysis
* Business Insight Generation

---

## 📌 Project Type

**Data Analytics | Business Intelligence | Power BI Dashboard**

---

## 👨‍💻 Author

**Karthik**

Aspiring Data Analyst | Power BI | Data Analytics | MySQL | Python

---

⭐ If you find this project useful, feel free to star the repository!

