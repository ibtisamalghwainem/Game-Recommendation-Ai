# Game Recommendation AI
Unsupervised AI system for recommending games based on user behavior, playtime, and genre diversity.

## Overview
This project builds an unsupervised recommendation system for video games using clustering techniques.  
It analyzes user behavior, playtime, genre diversity, and interaction patterns to group similar users and suggest relevant games.

## Dataset Features
- **UserID**: Unique identifier for each user
- **GameName**: Title of the game
- **Hours**: Time spent playing
- **Behavior**: Play or Purchase
- **Categories**: Game modes (e.g., Single-player, Multi-player)
- **Genres**: Game genres (e.g., Action, Strategy)
- **is_recommended**: Boolean flag indicating user recommendation

## Workflow Summary
1. **Data Cleaning**: Handling nulls and duplicates
2. **Feature Engineering**:
   - Total playtime, purchase count, genre/category diversity
   - Purchase ratio and average playtime
3. **Encoding**:
   - One-hot encoding for top 100 games
   - Label encoding for behaviors and game names
4. **Normalization**: Standardizing numerical features
5. **Clustering**:
   - K-Means with silhouette and Davies-Bouldin scores
   - DBSCAN with noise filtering and cluster comparison
6. **Visualization**:
   - Top games by average playtime
   - Behavior distribution
   - Cluster analysis

## Notebooks
- `notebooks/Game_Recommendation_System.ipynb`: Full Colab notebook with preprocessing, feature engineering, clustering, and evaluation

## Author & Contact

**Ibtisam Alghwainem**  

📬 **Contact**  
- GitHub: [github.com/ibtisamalghwainem](https://github.com/ibtisamalghwainem)  
- LinkedIn: [linkedin.com/in/ibtisamalghwainem](https://linkedin.com/in/ibtisamalghwainem)  
- Email: ibtisamalghwainem@gmail.com
