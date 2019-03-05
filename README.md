
#### Usage

(1) Extracting data from the Weather API and store to MongoDB

(2) The entire query list is stored in cityList.txt file

> Usage

> python2 dataExtractor.py ./data

(3) dataExtractor is running in cronjob as (after every 2 hours)
> 0 */2 * * * /usr/bin/python2 (absolute-link-to-data-extractor-file) (absolute-link-to-data-dir)

(4) The dashboard is build with Flask Web Framework. 
> Usage

> cd flask_dashboard

> pip install -r requirements.txt

> python2 app.py

The flask server wis hosted at http://0.0.0.0:5000/

(5) MongoDB is currently being used as a local database.
