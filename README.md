# Analysis of Factors Affecting IMDb Ratings

## Project Overview
This project explores the key factors influencing IMDb ratings of movies. We focused on analyzing three main areas: movie duration, film critics and reviews, and genre popularity. Our goal was to identify which of these factors have the most significant impact on IMDb ratings, thereby providing actionable insights for industry professionals.

## Project Structure
The project is divided into the following components:

1. **Proposal**: Identification of the research problem, data collection, and preparation for analysis.
2. **Final Report**: A comprehensive analysis and findings report.
3. **Presentation**: Highlights of the research problem, conducted analysis, and conclusions.

## Data
The dataset used in this project is the "IMDb Top 250 Movies," which includes detailed information about the top 250 movies by IMDb rating. The dataset contains various attributes like movie titles, IMDb ratings, duration, genre, cast, and user reviews, making it suitable for our research.

- **Raw Data**: [IMDb Top 250 Movies](path_to_data)
- **Cleaned Data**: [Cleaned Data](path_to_cleaned_data)

## Analysis
### 1. Influence of Movie Duration on IMDb Ratings
We explored the correlation between movie duration and IMDb ratings using linear regression and Pearson correlation techniques. The analysis revealed a weak positive correlation, suggesting that movie duration has some impact, but it is not the primary determinant of a movie's rating.

- **R Code for Analysis**: [Duration Analysis](path_to_code)
- **Key Findings**: Longer movies tend to receive slightly higher ratings, but the effect is minimal.

### 2. Impact of Film Critics and Reviews
We analyzed the impact of film critics and user reviews on IMDb ratings using regression tree models with emotion and TF-IDF features. The models showed that while there is some impact, emotional content and specific keywords in reviews are not strong predictors of movie ratings.

- **R Code for Analysis**: [Critics and Reviews Analysis](path_to_code)
- **Key Findings**: Emotion features have a minimal impact, and more complex models are needed to improve prediction accuracy.

### 3. Relationship Between Genres and IMDb Ratings
We investigated the relationship between film genres and IMDb ratings using linear regression analysis. Our findings indicate that genres like Drama, Horror, and Western are strong predictors of higher ratings. The combination of genres also plays a significant role in determining a movie's rating.

- **R Code for Analysis**: [Genre Analysis](path_to_code)
- **Key Findings**: Drama emerges as the highest-rated genre, and specific genre combinations tend to receive higher ratings.

## Conclusions and Recommendations
- **Duration**: While longer movies tend to get slightly better ratings, the impact is minimal. Industry professionals should consider other factors like storyline quality and casting.
- **Critics and Reviews**: Emotional content and specific review keywords are not strong predictors. Future models should include additional factors such as director and plot complexity.
- **Genres**: Drama and certain genre combinations are particularly appealing to audiences. Filmmakers should consider these insights for future projects.

## Final Report
The full analysis and detailed conclusions are available in the [Final Report](APAN 5205 Project Final Report-1.pdf).

## Presentation
A summary of our findings is available in the project presentation: [Presentation](path_to_presentation).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
