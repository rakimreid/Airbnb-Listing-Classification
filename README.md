<div align = "center">
     <h1> Airbnb Listing Classification </h1>

     
 
<img src = "https://2.bp.blogspot.com/-0-xkGLW6EJ8/V6OYaRZg9UI/AAAAAAAAHcI/x2hlKbhu1Lk143IG_igMsdQ8CAPFHge6ACLcB/s1600/giphy.gif" height = 600, width = 600 />
</div>


<h2>Background</h2> 

Airbnb is an American San Francisco-based company operating an online marketplace for short and long-term
homestays. The company serves as a broker between renters and hosts. 

<h2> Part I: Exploratory Data Analysis <img src ="https://th.bing.com/th/id/OIP.j5Vj7VYXdSuB0Cho-HbMpgHaHa?pid=ImgDet&rs=1" height = 25, width = 25 />

</h2>


<h3>Data</h3> 

The dataset comes from <a href="http://insideairbnb.com/">Inside Airbnb</a>.

Inside Airbnb's is a “mission driven project that provides data and advocacy about Airbnb's impact on residential communities. We work towards a vision where data and information empower communities to understand, decide and control the role of renting residential homes to tourists.”

<h2> Part II: Supervised Learning

<img src ="https://th.bing.com/th/id/OIP.4u9QjWljrMuY5CL7nGzRkQHaFj?w=273&h=205&c=7&r=0&o=5&dpr=1.3&pid=1.7" height = 25, width = 25 />
</h2>
     

The models tested were: 

* Random Forest
* Decision Tree
* Support Vector Machine
* XGBoost 
* Extra Trees (extremely randomized trees)


     
<h3>Supervised Model Best Results</h3>
     
The tuned random forest classifier model performed the best out of the models.

The biggest finding for this project was the poor performance of the regression models to predict price as a continuous variable. I switched to a classification method and the results completely flipped - from poor to good and almost model deploy-able.

This means, at least, for AirBnB properties in Tokyo, classification methods are better than regression methods.  

     
<h2> Part III: Evaluation & Future Project Ideas 
<img src ="https://th.bing.com/th/id/R.b8644db24930cf9363566896d5253aec?rik=7SL6mGoqlQ0TNQ&riu=http%3a%2f%2fmedia.istockphoto.com%2fvectors%2fsaturn-vector-id165600450%3fk%3d6%26m%3d165600450%26s%3d612x612%26w%3d0%26h%3drEvVMsd4l40ib7bcrQzr1TzjkbLgRpcYPYGpYhJ9Nxo%3d&ehk=KabbCN8zzWnhbNSUIRMIS8eS0lrYNF2gRndPFaAxmOg%3d&risl=&pid=ImgRaw&r=0" height = 25, width = 25 />

</h2> 
     
<h3> Evaluation:</h3>
Tokyo's AirBnB property listing data has several characteristics that may make analysis challenging. Classification models, however, appear promising. Algorithms and models incorporating aggregated models are worth exploring. A single decision tree was less accurate than the Random Forest model. Classification on a hyperplane like in Support Vector Machines was even more inaccurate (.75), a ten point difference from the Random Forest model.

<h3>Future Projects</h3>

Future projects may:

* Use additional features to predict price (a binary feature) to produce a more accurate model potentially.

* Deploy the model into a web app.

* Use a different outcome feature for classification.

* Examine only one category of room_type to determine if different room types produce different results for a classification model.

* Use other model types including deep learning. This model's accuracy may have increase to 90%
     

