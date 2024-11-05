#  Similarity recommendation Project

## Project Outline

A refined text analysis project examining intriguing connections among 64 literary works. Leveraging advanced comparison algorithms, the project reveals concealed patterns and resemblances in classic literature.

##  Characteristics

- Pinpoints the 100 most impactful words within the literary collection  
- Creates a detailed 64x64 matrix to show similarities  
- Highlights the top 10 most closely connected book pairs  
- Accurately processes and examines raw text  
- Employs reliable comparison algorithms

##  Results Highlight

Our analysis uncovered intriguing links between various books. Here are some key insights:

1. Gerard's *Herbal* volumes exhibit a high degree of similarity, with a 91% match between Vol. 3 and Vol. 4.
2. *Memoirs of Laetitia Pilkington* displays strong narrative continuity across its volumes.
3. *Foxe's Book of Martyrs* consistently upholds thematic unity across its sections.

## Practical specification

### Core Components
- A custom `Book` class is designed for efficient text representation.
- An advanced text preprocessing pipeline is included.
- Sophisticated algorithms are implemented for similarity calculations.
- A comprehensive analysis of word frequency is conducted.

### Technology Stack
- Programming Language: C++
- Data Format: Raw text files
- Analysis Approach: Statistical text comparison

## Performance

The program processes 64 books efficiently and performs:
- Word frequency analysis over the entire corpus
- 2,016 distinct comparisons between books
- Ranking and sorting based on similarity

## Getting Started

1. Clone the repository.
2. Place all text files of books in the specified directory.
3. Compile the C++ source files.
4. Run the executable.
5. Access results in the output directory.

## Output Files

The program produces several output files:
- `common_words.txt`: Contains the 100 most frequent words.
- `similarity_matrix.txt`: A complete matrix of comparisons.
- `similar_books.txt`: Lists the top 10 most similar pairs of books.

## Future Scope

- Integration of Natural Language Processing
- Development of an interactive visualization dashboard
- Adding semantic analysis capabilities
- Enabling genre classification
- Supporting multiple languages

## Technical Note

Currently, a single-threaded approach is used for optimal stability and reliability. Although this design impacts processing speed, it ensures consistent results across different system setups.

## Acknowledgments

Special thanks to:
- The professors for their guidance
- The open-source community for their inspiration

Submitted by - iitgcs_24061080 (Arnab Kr. Pal aka. rdxakp)
