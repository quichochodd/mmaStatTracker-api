# mma_stat_tracker-api

## Technologies
**Back-end Development:**
- Django
  - Creating virtual environment:
    `python3 -m venv mma_stat_tracker`
  - Activate virtual environment:
    - Mac: `source mma_stat_tracker/bin/activate`
    - Windows: `mma_stat_tracker\Scripts\activate`
  - Start server: `python manage.py runserver`
  - Install dependancies: `pip install -r requirements.txt`
    - Create requirements.txt with list of dependancies: `pip freeze > requirements.txt`
  - Close enviroment: `deactivate`

**Database:**
- MySql

**Machine Learning:**
- Python: For implementing machine learning algorithms.
- Scikit-learn, TensorFlow, or PyTorch: Libraries for building and training machine learning models.
- Data preprocessing: Techniques such as feature scaling, normalization, and feature engineering may be required to prepare the data for training.
- Classification Algorithms: You can use algorithms like logistic regression, decision trees, random forests, or neural networks for predicting fight outcomes based on past statistics.

**Deployment:**
- Heroku, AWS, or DigitalOcean: Platforms for deploying and hosting your web application and machine learning models.

## Obtaining past UFC fight data:
- APIs provided by UFC Stats, Sherdog, Tapology. 
- Scraping data from these websites **research & comply with terms of service and use the data responsibly**

## Potential data sources:
*Before scraping any website, ensure you review their terms of service and adhere to them to avoid any legal issues. Additionally, check if these websites offer APIs that you can use to access the data more easily and legally.*
- UFC Stats API: This provides comprehensive data on past UFC fights, including fighter statistics, fight results, and more. You can find more information here.
- Sherdog: Sherdog provides extensive MMA fight records, including UFC fights. You may need to scrape data from their website and ensure compliance with their terms of service.
- Tapology: Tapology also offers fight records and detailed statistics for UFC and other MMA organizations. Similar to Sherdog, you'll need to scrape data while respecting their terms of use.
