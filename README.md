# Mobile-Price-Range-Prediction
<h4><b>In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is</b></h4>

<h2><b>Data Description -</b></h2>
<ul>
<li><b>Battery_power -</b> Total energy a battery can store in one time measured in mAh</li>
<li><b>Blue -</b> Has bluetooth or not</li>
<li><b>Clock_speed -</b> speed at which microprocessor executes instructions</li>
<li><b>Dual_sim -</b> Has dual sim support or not</li>
<li><b>Fc -</b> Front Camera mega pixels</li>
<li><b>Four_g -</b> Has 4G or not</li>
<li><b>Int_memory -</b> Internal Memory in Gigabytes</li>
<li><b>M_dep -</b> Mobile Depth in cm</li>
<li><b>Mobile_wt -</b> Weight of mobile phone</li>
<li><b>N_cores -</b> Number of cores of processor</li>
<li><b>Pc -</b> Primary Camera mega pixels</li>
<li><b>Px_height -</b> Pixel Resolution Height</li>
<li><b>Px_width -</b> Pixel Resolution Width</li>
<li><b>Ram -</b> Random Access Memory in Mega</li>
<li><b>Touch_screen -</b> Has touch screen or not</li>
<li><b>Wifi -</b> Has wifi or not</li>
<li><b>Sc_h -</b> Screen Height of mobile in cm</li>
<li><b>Sc_w -</b> Screen Width of mobile in cm</li>
<li><b>Talk_time -</b> longest time that a single battery charge will last when you are</li>
<li><b>Three_g -</b> Has 3G or not</li>
<li><b>Wifi -</b> Has wifi or not</li>
<li><b>Price_range -</b> This is the target variable with value of 0(low cost), 1(medium cost),2(high cost) and 3(very high cost).</li>
</ul>


![download](https://github.com/jouherdauf/Mobile-Price-Range-Prediction/assets/64728749/9d1f1417-1837-4cae-996e-aa04f3a3e6a1)

# **Conclusion**
<ol>

<li> The given dataset was very clean it has no null values, no duplicates, and no outliers</li>

<li>Half the devices have Bluetooth, and half don’t there is a gradual increase in battery as the price range increases Ram has continuous increase with price range while moving from Low cost to Very high cost.</li>

<li>Costly phones are lighter.</li>

<li>RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.</li>

<li>Form all the above experiments we can conclude that Logistic Regression>Support Vector Machine>XGboost>Random Forest>Decision Tree> Naive Bayes>KNN with using hyperparameters will got the best results.</li>
</ol>
