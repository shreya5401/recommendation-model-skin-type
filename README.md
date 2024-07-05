# Skin-Tone Based Product Recommender

## Overview

This project is a recommendation system that suggests skincare products based on a user's skin type and skin tone. It utilizes K-Nearest Neighbors (KNN) algorithm for generating recommendations and includes a web scraper built with Selenium to collect product data from various online sources.

## Features

- Skin type and tone analysis
- Product recommendation using KNN algorithm
- Web scraping functionality for up-to-date product information
- User-friendly interface for input and displaying recommendations

## Technologies Used

- Python 3.10+
- Scikit-learn for KNN implementation
- Selenium for web scraping
- Pandas for data manipulation
- NumPy for numerical operations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Navya-Verma11/Recommendation-model-based-on-skin-type
cd skin-tone-recommender
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```
3. Install the required packages:
```bash
pip install -r requirements.txt
```
4. Download and install the appropriate WebDriver for Selenium (e.g., ChromeDriver for Google Chrome).

## Usage

1. Run the main script:

2. Follow the prompts to input your skin type and tone.

3. View the recommended products based on your input.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [website](https://github.com/Randon-Myntra-HackerRamp-21/CV-skin-care-recommendation/tree/main/ML/Skin_metrics/Skin_tone/public/skin%20tone%20values) for providing the initial dataset of skincare products.
- Skin tone classification based on the research by [paper](http://www.eleco.org.tr/openconf_2017/modules/request.php?module=oc_proceedings&action=view.php&id=248&file=1/248.pdf&a=Accept+as+Lecture).