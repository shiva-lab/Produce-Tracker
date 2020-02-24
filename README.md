Project Ideas:
Project Idea 1


Flu State Radar


Abstract:


The flu lately has been one of the deadliest viruses in the world. This infectious disease can have various symptoms ranging from mild to very severe symptoms. There are a lot of ways to try to limit the spread of the disease such as washing your hands and making sure not to touch your face unless they are clean as the flu attacks the respiratory system and is very fast acting. There are alot of types of flu and it is hard to track along with being able to prevent these symptoms and viruses are unlike bacteria. We can only limit its duplication and bring down its symptoms.


The goal of this project would be to help citizens of certain cities to be able to show the cases of people suffering from the flu. This is not only data of people being tested for the flu as it would be for the visits to the hospital that are suffering from the symptoms as it is often patients who visits the doctor do not have the virus yet and the flu test could be negative. The months from October till April are the highest percentage of people suffering from the flu.


The application will be used by citizens, it will be a web application that is complained with any screen size incase it was accessed by tablet or phone. However this will be mainly a web browser application favorite since the Google Map API is much better to be hosted through a webserver framework. 


More Details:


The Flu State Radar will be built using various frontend and backend technologies. It will be also a one page application as users can Sign in with their Google account and be able to access the main page which contains a map area along with interactive buttons which shows some of the features the application will provide.


The map when the application is first loaded will display hot map area of the amount of people suffering from the flu in the current area and the darker and denser the map area implies the severity of people disganosed with the flu. 


Example Use Case:
1. User coming from out of town would like to visit some areas and try out some restaurants. (Users suffers from weak immune system)
2. User logs in and checks in the area he is staying at. 
3. The map area returns enough display of the map area surrounding the area he is visiting. 
4. User has an idea of what restaurants has residents around which suffer from the flu and potentially could have infected these public places.


After loggin into with Google you will be able to see a Google in the middle component. Surrounding will be 


https://user-images.githubusercontent.com/26826878/75105111-10aed400-55c6-11ea-8af4-19df42acd140.jpeg


The web application will be using a frontend and backend framework to display the home page then be able to route through the application. For the frontend part the technology that would be used mostly ReactJS along with minor tools such as less and other npm libraries that can help development such as React Boostrap. Redux is a potential tool that could be use to ease up the data flow between the REST API NodeJS calls. On the side we will have our dataset training by using Pytorch, Sci Kit Learn, Tensorflow to run the data on algorithms to provide the application with the percentages and the coloring of the hot areas.


Stack Technologies:


Front-End: ReactJS, Redux, Boostrap, Less.


Back-End: NodeJS, Express, MongoDB, Tensorflow, Sci-Kit-Learn, Python.


Full Stack: MERN MongoDB, Express, ReactJS, NodeJS.


Project Idea 2:




Produce Tracker


Abstract:


Produce goods distribution has been something that always has some flaws, as the way manufacturers and distrubters vary from one place to another. The tracking of these produce goods from one place to another are managed by many different databases. Our approach would be to instead of storing it in a database is to use a ledger (Blockchain) to track all produce goods. The time and place where it comes from can be secured on a secured platform to ensure the ability to track any good produce purchased by customers.


The project first step would be to try and find as much data possible from all manufacturers and distributors. This step would be the most challenging one as it will be difficult to find data regarding purchase of produce goods.


This application would be targeted to customers (distributors, retailers, people).


The application MVP would be a simple UI that you are able to login. After logging in using OAuth you would be asked between two options, to look up a sale or to register a sale. The UI which is developed using React would show what information is needed to to fill and then a blockchain would be created registering the sale. Other features that could be implemented in the future includes predicting what distributers might hand out damaged goods along with recommendation for specific produce.


One use case would be the problem California is facing with E Coli Roman Lettuce. The valley has been producing a lot of Roman Lettuce affected by this bacteria and has been a concern. Our application would enable all the customers to be able to register all purchases made of Roman Lettuce. After inputting this data the website would run the updated data through different algorithms and help give feedback on area with most likely infected products along with recommended places to go to purchase these types of products.






The web application will be using a frontend and backend framework to display the home page then be able to route through the application. For the frontend part the technology that would be used mostly ReactJS along with minor tools such as less and other npm libraries that can help development such as React Boostrap. Redux is a potential tool that could be use to ease up the data flow between the REST API NodeJS calls. On the side we will have our dataset training by using Pytorch, Sci Kit Learn, Tensorflow to run the data on algorithms to provide the application with the percentages and the coloring of the hot areas.


Stack Technolgoies:


Front-End: ReactJS, Redux, Boostrap, Less.


Back-End: NodeJS, Express, MongoDB, Tensorflow, Sci-Kit-Learn, OAuth, Python.


Full Stack: MERN MongoDB, Express, ReactJS, NodeJS.




Project Idea 3
* Project title- Github Workflow Manager
* Project Idea Description & Goal- One of the key challenges in Enterprise software development is issue tracking. Github is a leader in collaborative version control that doesn't offer a major capability to track issues. Our project is to develop a bot integrated with Instant Messaging Apps like Slack to notify the user about the status of the issue. Below are some of the common challenges that are faced by developers:
* Closing Stale Issues: There are many issues created nut most of them are kept on hold due to the next feature update or resource unavailability etc. hence the issue becomes stale
* Changing Issue Status: Manager or developer has to change the status manually as it gets merged, reviewed or closed
* Status Change Notifications: Not every tool can notify the assignee or watchers about the change in the issue's status, or if they have, the methods are not convenient.
* Assignee Recommendation:  it is very complex for the assignee to know about the resource utilization before assigning the issue, also to identify the current workload of the developer.


To the above-described problem because the tasks listed in the problem statements are repetitive, and hence could easily be handed over to a bot. The bot can be integrated with collaboration tools like Slack, which makes it a lot more convenient to use, as these tools are already being used for communication, file transfers, etc.
More Details:
The implementation of a bot will allow managers to leverage their time to some other important things.there will be 5 status (Open,In progress,review, In Test closed) that can be assigned to an issue based on their progress.For example once the Pull Request (PR) is approved, merged, and closed the bot will automatically update the status of the issue to "In Test" but if  PR gets rejected it will not change the status.
For stale  issues prediction, the configuration is as follows: Bot will execute a cron job every day, and it will look for the issues which do not have any activity on them in the past 3 months.The bot will notify the assignee about these issues on slack. It will also provide an option to change the status of a single issue or all issues.
The "Bot" performs the following tasks:
•        It clears the issues which do not have any activity on them for a long time. The bot provides an option to the assignee to close this issue. After approval from the assignee, it closes the stale issue.
•         With the help of the bot you can get a list of users to whom this issue can be assigned, based upon the current workload and acquired skills of the developers. 
* Technology Stack:.Ubuntu,MySQL,AWS,Ansible,Jenkins, Node JS 




Project Idea 4 
1. Project title - Predicting House prices

2. Goal - Property investment among people has become very common nowadays. As a result, there has been a major rise in price of houses in some areas especially popular ones. Due to this reason  the needy people, especially middle class people and youngsters who have recently started their careers are being misled by the high prices. Thus these people continue to live on rent for years.


Therefore we have come across a solution by creating an application that would give needy people the power to negotiate heavily with owners and builders. Our application would provide them enough data and visualization to enable them to find the dream house within their budget.


   3. Project Idea -  predict the house prices in particular areas based on various factors which influence the house negotiations. We will predict the final price of the home based on various variables using machine learning predictive analytics and advanced regression techniques. This price prediction will be helpful for any new home buyer to negotiate with property owners or real estate agents.

   4. Approach - After doing research, we found regression models as best approach to predict house price


Data Set and Collection
We will gather data from our neighbor for housing prices as a csv set. Will set the environment ready with the python libraries such as Numpy, Pandas and then import the data.

Data Visualization
Will read the csv files to create set of training data and test data and then analyze the data. Analysing data is the most important thing to understand what the data is telling us.

Here's a brief version of what the data description file would look like:
      * SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
      * MSSubClass: The building class
      * MSZoning: The general zoning classification
      * LotFrontage: Linear feet of street connected to property
      * LotArea: Lot size in square feet
      * Street: Type of road access
      * Alley: Type of alley access
      * LotShape: General shape of property
      * LandContour: Flatness of the property
      * Utilities: Type of utilities available
      * LotConfig: Lot configuration
Will plot the above data to generate bar graphs, pie chart, heatmap to visualize the data and pick these as features for our machine learning model.   

        Feature Engineering
        Will convert all columns into numeric or categorical data. After that 
     will cleanse the data by dropping null or missing values as below:

        # Categorical boolean mask
categorical_feature_mask = train.dtypes==object

# filter categorical columns using mask and turn it into a list
categorical_cols = train.columns[categorical_feature_mask].tolist()

        We will then pick some features for the model. For this we are going to
     use correlation matrix and we are going to pick most correlated with 
     sale price.      
        
Regression Models
     We will train out model on the training set and then use the test set to 
     evaluate the model by checking out it's coefficients and how we can 
        interpret them. Will grab predictions off our test set and see how well 
     it did. Will be using  three common evaluation metrics for regression 
problems such as Mean Absolute Error (MAE), Mean Squared Error (MSE) and 
Root Mean Squared Error (RMSE) and compare these metrics.



        Linear Regression
        from sklearn.linear_model import LinearRegression
lm = LinearRegression()
lm.fit(X_train,y_train)

        Support Vector Machine Regression
        from sklearn.svm import SVR
svr = SVR(kernel = 'rbf')
svr.fit(X_train, y_train)


Random Forest Regression
        from sklearn.ensemble import RandomForestRegressor
rfr = RandomForestRegressor(n_estimators = 500, random_state = 0)
rfr.fit(X_train, y_train)


Model Comparison
By looking at Mean Square Error(MSE) rates, we shall be able to predict 
the best model

        error_rate=np.array([metrics.mean_squared_error(y_test, 
predictions),metrics.mean_squared_error(y_test, 
clf_pred),metrics.mean_squared_error(y_test, 
dtr_pred),metrics.mean_squared_error(y_test, 
svr_pred),metrics.mean_squared_error(y_test, rfr_pred)])


Technology Stack
Front End: Flask Framework, HTML, CSS
Back End: Python, Sci-Kit-Learn, Tensorflow, Mongo/MySql




Project Idea 5
Wildfire California Predictor


Abstract


Wildfires in California have been an issue as with Climate Change alot of fires are occuring in forests and since California has a very unique climate it has been suffering from this problem.


Wildfires are very hard to deal with as depending on the cause, how fast it spreads and the amount of resources that can be lost during this change. July 2018 marked a very high history temperature which was at almost 80 Fahrenheit. Since managing Climate Change and the care for the forests has been so poor in California. Another contribute to the danger of wildfires in California is the risk people are at since there has been an increase of urban expansion into high risk fire zones. 


Goal:


Developing an application to help prepare for these type of disasters would help prepare for such events. Preventing wildfire is a very difficult task as there are multiple causes and with all the proposed solutions California has yet not been able to sustain these fires in an efficient time manner. The goal of the project is to give the Fire Department and the California Government an idea of the specific areas which could be at risk.


More Details:


The application would require some data to be acquired from Kaggle and other dataset websites. Also the California gov website provides some data regarding this issue. We will be using multiple Machine Learning tools such as PyTorch, Sci-kit-Learn, Tensorflow and other potential tools that could support and help our application. The application will use these tools to datamine the data and run the training dataset on some ML algorithms to able to predict things such as popular fire locations, the frequency of surrounding area along with a feature that would be implemented if time allows is to be able to enter a city name or a coordination to give you the percent of a fire nearby. 


The application will mainly be a one page application which is a main feature in React JS. This page would contain multiple components the main component would be a map. This map will contain the and these components will simple be a search enginer that would help zoom into specific area and show the hot map of likely fires along with percent of one occurring.


https://user-images.githubusercontent.com/26826878/75104419-a8f48b00-55bd-11ea-9d58-d451e3c90f92.jpeg


The web application will be using a frontend and backend framework to display the home page then be able to route through the application. For the frontend part the technology that would be used mostly ReactJS along with minor tools such as less and other npm libraries that can help development such as React Bootstrap. Redux is a potential tool that could be use to ease up the data flow between the REST API NodeJS calls. On the side we will have our dataset training by using Pytorch, Sci Kit Learn, Tensorflow to run the data on algorithms to provide the application with the percentages and the coloring of the hot areas.




The plan for the project is to build a MVP that would be a simple web application that is friendly to all devices. This application would be more intended for the scientists and the Fire Department to help them have an idea of potential danger to California cities that are near these wild forest areas. More detail will come along with depth research while implementing the project.


Stack Technologies:


Front-End: ReactJS, Redux, Bootsrap, Less.


Back-End: NodeJS, Express, MongoDB, Tensorflow, Sci-Kit-Learn, Python.


Full Stack: MERN MongoDB, Express, ReactJS, NodeJS.