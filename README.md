# 🎵 Spotify Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-779fa7?style=for-the-badge)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a dataset of Spotify tracks. The goal is to uncover the factors that contribute to a song's popularity, identifying dominant artists, preferred genres, and the impact of song characteristics like duration and explicit content.

Using **Python** and libraries such as **Pandas** and **Seaborn**, we clean, process, and visualize the data to derive actionable insights for music enthusiasts and data analysts alike.

## 🔍 Key Insights

Based on the analysis, here are some of the interesting trends observed:

* **👑 Artist Domination:** **Taylor Swift** leads the industry with the highest number of releases (324) and the top market share (3.78%), while also maintaining a perfect popularity score of 100.
* **🔞 Explicit Content:** Explicit tracks tend to be **more popular** on average (Score: ~57.8) compared to non-explicit tracks (Score: ~50.5), suggesting a listener preference or higher engagement for such content.
* **💿 Albums vs. Singles:** Songs released as part of an **Album** generally perform better (Avg. Popularity: 55.66) than Singles (46.36) or Compilations.
* **⏱️ Optimal Duration:** There is a "sweet spot" for song length. Tracks with a duration between **2 and 5 minutes** tend to achieve the highest popularity.
* **🎸 Genre Trends:** Aside from unclassified genres, **Pop**, **Country**, and **Hip Hop** are the most frequently released genres.

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**
    * `pandas` & `numpy` for data manipulation
    * `matplotlib` & `seaborn` for data visualization

## 📂 Dataset

The analysis is based on `spotify_data.csv`, which contains attributes for thousands of tracks, including:
* `track_popularity`: The metric used to measure success.
* `explicit`: Content rating of the track.
* `artist_name`: Name of the performing artist.
* `album_type`: Single, Album, or Compilation.
* `track_duration_min`: Length of the track in minutes.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/spotify-eda.git](https://github.com/yourusername/spotify-eda.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebook:**
    Open `Spotify_EDA.ipynb` in Jupyter Notebook or VS Code to explore the analysis.

## 📊 Visualizations

The notebook includes various visualizations such as:
* Bar charts for **Top 10 Most Popular Artists**.
* Pie charts showing the **Distribution of Explicit Tracks**.
* Scatter plots analyzing **Track Duration vs. Popularity**.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for deeper analysis or new visualizations, feel free to open an issue or submit a pull request.

---
*Created with ❤️ by [Your Name]*
