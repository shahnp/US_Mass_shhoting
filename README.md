# US_Mass_shhoting[https://rpubs.com/shah_np/457270]

**1 Introduction:**
A recent study published by the Harvard Injury Control Research Center shows that the frequency of mass shooting has increased over time. Some of the deadliest mass shootings in the U.S. happen last year February 2018 including the Parkland high school (https://en.wikipedia.org/wiki/Stoneman_Douglas_High_School_shooting) shooting and the massacre at the Tree of Life synagogue in Pittsburgh (https://en.wikipedia.org/wiki/Pittsburgh_synagogue_shooting) that occured in October 27, 2018 which prompted widespread national horror. But the death toll is not irrelevant to
1/12/2019 Mass Shooting in US shooters’ motives. Criminologists who’ve studied them believe that body counts play a role in their calculations.But Mass shooting say a lot about the soceiety, country and how well we are making progress in overcoming loss of life.


**Why I picked these datasets**
The US has witnessed 398 mass shootings in last 50 years that resulted in 1996 o cial deaths and 2488 o cial injured.I stumble upon these datasets while uploading my other two projects one of which Bostn Crime Boston Crime (https://rpubs.com/shah_np/453629) and another one is Cambridge Crime (https://www.kaggle.com/pankajautomatic/cambridge-eda) Analysis.I thought of implementing di erent tools and show di erent prespective than I used for those two projects. The anlaysis and the approach taken in this project is quite in di erent direction than those two. I hope you will see the di erence and love the work. I have more focused on converying my story through graphs and visualisation than Exploratory analysis in this project.

**2.1 Information**
How has the number of death folded over the years?
Before I would take you the analysis and journey of US mass Shootings. Lets take a moment to realise how each of the incidents have folded over the last 50 years.
When we break the Mass shootings over the decades. - In the 1980s, there were 30 mass shootings, with 173 deaths. - In the 1990s, the number was increased to 37, with some 200 fatalities and another 186 wounded. In the 2000s , the number were 33 such shootings, even as they became deadlier – 227 deaths.
Over the last few years has contributed a lot in increased number of Mass Shootings.The terrible numbers which keeps on growing with each mass shooting.The city, state, places have changed, but the numbers have gone more wider than heading any other directions, but one thing which stands out from each and everything is the choice of weapon which remains the same. In the United States, people who would think of commiting such a henious crime always prefer guns, not with knives and or any alternative form. So is it fair to say that Mass Murders that occurs quite often now a days has something to do with guns.
Breaking down the crime: shooter
When I looks at the 158 shootings in which four or more people were killed by a lone shooter (two shooters in a few cases).What I saw is that the people who were killed came from nearly every imaginable race, religion and socioeconomic background. Their ages range from the unborn to the elderly; 186 were children and teenagers. In addition, thousands of survivors were left with devastating injuries, shattered families and psychological scars.In some of the Mass Shootings,shooters often carried more than one weapon; one was found with 24. At least 175 of mass shooters’ weapons were obtained legally and 52 were obtained illegally. It’s unclear how 78 weapons were acquired till now to general public. Our question was not how these criminals get guns but what potential damage they can cause to society once they have such weapon.

**2.3 Question: Analysis**
What were the choice of weapon during all these mass shootings?
Semiautomatic ri es have been used in some of the country’s deadliest shootings, such as those in Newtown, Orlando, San Bernardino and Las Vegas. The AR-15, a lightweight, customizable version of the military’s M16, soared in popularity after a 10-year federal ban on assault weapons expired in 2004. Some of the Las Vegas shooter’s guns had been  tted with legal devices called “bump- re stocks,” which allow semiautomatic ri es to  re as quickly as automatic ones.
The gunman who killed 32 students and teachers at Virginia Tech in 2007 used a 9mm semiautomatic Glock 19 (and a .22-caliber Walther P22, another popular caliber).

**Does all these Mass Shooters were tied with some sort of crimes?**
Some of these mass shooters were known to have violent tendencies or criminal pasts. Others seemed largely  ne until they attacked. All but 3 were male. The vast majority were between the ages of 20 and 49. More than half — 90 of them — died at or near the scene of the shooting, often by killing themselves.

**Which Gender is more prone to commit such crime?**
Between 1982 and November 19, 2018, 3 mass shootings were initiated by solo-female shooters. In contrast, 103 mass shootings were carried out by male shooters. The mass shooting in San Bernardino on December 2nd, 2016 was the only instance in which both a male and female were the shooters.
Males Males are dominant in such a henious crime.However, a look at mass shootings in the United States by gender shows a great majority of mass shootings are carried out by men. So far there were 103 Males involved in Mass shootings.
Female - The most recent female shooter was a Pakistani mother who helped kill 14 partygoers at her husband’s workplace in San Bernardino, Calif., in 2015. 3 Females have contributed till date.
Male/Female In one of the Mass shooting both Male and Female were involved.
Ex-Marine - The others are an ex-postal worker who killed a former neighbor and six employees at a Goleta, Calif., mail-processing facility in 2006; and a former tribal council chairwoman who killed her brother and three others during an eviction hearing in Alturas, Calif., in 2014.
Middle-schoolers Andrew Golden, 11, and Mitchell Johnson, 13, pulled a  re alarm to  ush students and teachers out of their Jonesboro, Ark., middle school in 1998, and began shooting from a wooded perch nearby. They killed four girls and a teacher and wounded 10 others.
In the 50 years before the Texas tower shooting, there were just 25 public mass shootings in which four or more people were killed. Since then, the number has risen dramatically, and many of the deadliest shootings have occurred within the past few years.

**What are the most frequemt place of such Crime?**
Shootings in schools and houses of worship tend to stand out in our minds, but they make up a relatively small portion of public mass shootings. More common are those in o ces and retail establishments such as restaurants and stores. California has had more of these public mass shootings than any other state, with 25.

**Does Race play any role in Mass Shootings?**
Between 1982 and November 2018, 60 out of 107 mass shootings were initiated by White shooters. The Las Vegas strip massacre in 2017 had the highest number of victims between 1982 and 2018, with 58 people killed, and over 500 injured.

**Does Gender play any role in Mass Shootings?**
Most men, of course, go through life without killing anyone. And motives for crime are very individual. Not all women and men who kill do so for the same reasons. Each case is seems unique which I found out after going through much of articles published in National dailies.
 After a little history about the Mass shootings lets dive into our datasets to see whats there for us.


4 Data Modelling
The dataset contains information about Mass shooting events, each identi ed by a unique Serial No. The dataset contains Serial No, Title, Location, Date, Summary, Fatalities, Injured, Total Victims, Mental Health Issue, Race, Gender, and Lat-Long information.All the variables are quite self explanatory.


**What were the questions that was proposed at the time of introducing these course.**
These question were directly taken from Kaggle websites.
How many people got killed and injured per year?
Visualize mass shootings on US map
Is there any correlation between shooter and his/her race, gender
Any correlation with calendar dates? Do we have more deadly days, weeks or months on average What cities and states are more prone to such attacks
Can you  nd and combine any other external dataset to enrich the analysis
Any other pattern you see that can help in prediction, crowd safety or in-depth analysis of the event How many shooters have some kind of mental health problem?
There are some questions which can be answered with these data but there are some questions which need much more deep understanding from all the  eld even before we address those questions. Future prevention needs lots of attention from di erent  elds and de netly making mass shooting guns harder to purchase can be option but its all upto the society and members of congress to address those concerns.
Lets extract some information about our datasets. Let's look at some missing data

Like mass shootings in general, school shootings have gone from being a rare tragedy to a tragic reality. Already in 2018 there have been more than a dozen instances of gun violence in U.S. schools.We may be unsure where to even begin with such a heavy topic. Consider asking our kids what their questions are before you give our two cents.But, yet, there are many individuals who su ered childhood and adulthood traumas and severe abuse and they did not become rampage shooters. They developed healthy relationships with others. Are school shooters unable to develop healthy relationships with others?


**What are the most common target place choosed by Shooters? Where does Shooter prefer to choose as choice of their location?**

California,Florida and Texas have the most shooters.
Now we are left with empty values in Location, and there are 45 of those. We can deal with those missing states with he use of Latitude and Longitude data which is avialable to us.But for these we can use google geocode variables but you need API for that.
For all these observations, Location is empty. But coordinates are given in Longitude and Latitude. This is one way to derive address from coordinates to further be used for  lling State and City values:


The statistic shows the number of mass shootings in the United States between 1982 and November 19, 2018, by race and ethnicity of the shooter(s). Between 1982 and November 2018, 60 out of 107 mass shootings were initiated by White shooters. The Las Vegas strip massacre in 2017 had the highest number of victims between 1982 and 2018, with 58 people killed, and over 500 injured.
Outer legends represents the White American or European American.
Is it fare to say that some other races are also participating in Mass Shooting beside Whites.
How has other races evolve in Mass Shootings. Lets look at the transition of our datasets.

In year 2012 we haven’t seen more shootings but which occured in Sandy hook Elementary School was henious. From 2012-2014 it has spread across the board with no correlations at all. In year 2015 we can see Mass Shooting crime is happening more mostly in beginning of the year.In early months of 2016 we can see there are more incidents which has occured. Something de netly seems to happen in year 2016 which has caused less access to guns or guns law which creates huge spun and in the year 2017 we see less crime than recent previous years but one of the deadliest shooting in US history also happen in year 2017 October 2nd.
In Some of my previous work Exploratory data analysis I have got a chance to use lea et to zoom iniside city geographical locations. I will try to use same function over here.

From the above observation most of the Mass Shootings happens either is Shooter is consider mentally retarded termed here as a psycho ,some are related to terrorism and third one is because of lack of Anger and Frustation management. Out of top three crimes I believe third one could have been controlled if guns were not accessible to these persons.

If you go with the raw numbers.According to the Gun Violence Archive, which compiles data from shooting incidents, a “mass shooting” is any incident in which a gunman shoots or kills four or more people in the same general time and location By that de nition, according to the Gun Violence Archive, we have seen 307 mass shootings from January 1 to Decemeber. The  ve deadliest shootings in the US have occurred in roughly the past 10 years.From 1966 to 2012, nearly a third of the world’s mass shootings took place in the United States. A 2016 study looked at 292 incidents in which four or more people were killed. It found 90 of them occurred in America. Put another way: While the United States has about 5% of the world’s population, it had 31% of all public mass shootings.People have a greater chance of dying in mass shootings if they’re at school or place of business

Most shooters take their own lives, or are killed.About 70% of active shooter incidents end with the shooter or shooters’ deaths, according to the FBI. Unlike a homicide or mass killing, the “active” aspect implies that both law enforcement and citizens have the potential to a ect the outcome of the event.
That averages to almost 7 mass shootings a week.
With the help of these datasets I tried to answer some basic questions. If we had multiple data source may be we could have done little better than these. Apart from implementing what I learnt from others I tried to present same with better vizualizations. Most of the analysis executive summary is presented in the beginning.
Thanks for reading.If you have any comments,suggestions I encourage you to write.Your comments are valuable for my future ways of analysis.

**If you Would like to see Report Please visit the pdf portion without running the rmarkdown code**








