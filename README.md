# Airbnb_TripAdvisor_ReviewScore
Using TripAdvisor Helpfullness flag to predict Airbnb review helpfullness and extacting helpful business insights.


TripAdvisor Data for training:
Source:https://www.cs.cmu.edu/~jiweil/html/hotel-review.html
Size: 878,561 X 3
Customer review with labels

Airbnb Data for result analysis:
Source:http://insideairbnb.com/get-the-data.html
Size: 584,586 X 6
Customer review without labels


Task:
Inspect Airbnb business activity during COVID-19 pandemic 2019 July - 2020 April (time series)   
Build word vectors to represent customer reviews from tripAdvisor data using pyspark on AWS 
Compare binary text classification models in predicting helpfulness of customer reviews using pyspark on AWS
Generalize insights from how helpfulness of reviews are related to other features, like comment length, review count

Requirement:
boto3==1.17.78
botocore==1.20.78
branca==0.4.2
certifi==2020.12.5
chardet==4.0.0
click==8.0.1
Flask==2.0.1
folium==0.12.1
idna==2.10
itsdangerous==2.0.1
Jinja2==3.0.1
jmespath==0.10.0
MarkupSafe==2.0.1
numpy==1.20.3
pandas==1.2.4
plotly==4.14.3
python-dateutil==2.8.1
pytz==2021.1
requests==2.25.1
retrying==1.3.3
s3transfer==0.4.2
six==1.16.0
urllib3==1.26.4
Werkzeug==2.0.1


