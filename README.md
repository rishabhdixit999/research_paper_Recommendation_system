# Research Paper Recommendation System

## Overview

The Research Paper Recommendation System is a web-based application designed to assist researchers in discovering relevant and high-quality research papers efficiently. This system incorporates a pipelined hybrid approach, integrating content-based filtering, collaborative filtering, and a hybrid model for optimal recommendations.

## Features

- **Content-Based Filtering:**
  - Utilizes TF-IDF, Word2Vec, and other content-based models.
  - Analyzes the content of research papers, including titles and abstracts.

- **Collaborative Filtering:**
  - Recommends papers based on the preferences of users with similar interests.
  - Implements item-based collaborative filtering for improved accuracy.

- **Hybrid Model:**
  - Pipelined approach combining content-based and collaborative filtering.
  - Enhances recommendation accuracy by leveraging the strengths of both models.

- **PageRank Algorithm:**
  - Measures the importance of research papers based on citation relationships.
  - Implemented using Neo4j for efficient graph data management.

- **User Interaction:**
  - Users can input preferences and receive recommendations based on various models.
  - Rating system allows users to provide feedback for system evaluation.

## Technologies Used

- **Frontend:**
  - Developed using Bootstrap, HTML5, and CSS for an intuitive user interface.

- **Backend:**
  - Python Flask REST API handles communication between frontend and backend models.

- **Machine Learning Models:**
  - Content-based models include TF-IDF, Word2Vec, and more.
  - Collaborative filtering uses item-based approach for improved accuracy.

- **Graph Database:**
  - Neo4j is employed for efficient storage, management, and querying of graph data for PageRank algorithm.

## Getting Started

1. Clone the repository.
2. Set up the frontend and backend environments.
3. Run the application and explore the research paper recommendations.

## System Evaluation

Users can contribute to the evaluation process by providing ratings for each recommendation. This feedback helps enhance the system's accuracy and tailors recommendations to individual preferences.

## Future Enhancements

- Integration of additional recommendation models.
- Implementation of advanced natural language processing techniques.
- Enhancement of user interface and user experience.

## Contributors

- [Rishabh Dixit]
- [Sourabh Hembrom]


## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute and make this research paper recommendation system even more powerful and user-friendly!
