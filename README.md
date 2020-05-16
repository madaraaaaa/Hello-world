#  data visualization
Dataset
Bay Wheels (previously referred to as Ford GoBike) is a regional public motorcycle sharing gadget inside the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing gadget deployed in California and on the West Coast of america with nearly 500,000 rides for the reason that launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of monthly individual trip statistics from January 2018 to December 2018 in CSV layout protecting the greater San Francisco Bay area, also to be had here.

Data wrangling process:
fix more than one fields that aren't in the suitable dtype, i.E. Start_time, end_time need to be datetime type, user_type and member_gender must be categorical records type, etc
upload new columns for journey period in minute, trip begin date in yyyy-mm-dd layout, journey begin hour of the day, day of week and month
upload a brand new column calculating riders' age from 'member_birth_year'
clear out outlier a long time from visual exam of the member age distribution and statistical percentile
cast 'member_birth_year' and 'member_age' to integer as opposed to flow type
cast 'start_dayofweek' to class dtype
cast 'start_month' to class dtype for smooth plotting
clear out outlier trip statistics where the period was very long
Summary of Findings
The quantity of trips peaked around 8-9am and 17-18pm throughout a day, there had been more journeys on paintings days (Mon-Fri) as compared to weekends. Summar time changed into the maximum popular season of a year, likely because of the weather. The riding trips tend to be shorter on Monday through Friday as compared to weekends. It indicates a quite stable and efficient usage of the motorcycle sharing system on regular work days, even as extra informal flexible use on weekends.

Most riders have been male subscribers who did not use bike percentage for all journeys. Most members were around 25 to 40 years old, because the age receives older, motorcycle utilization dropped significantly. Though now not a huge difference, male riders tend to have shorter trips as compared to lady users, indicated by using each a smaller median and shorter IQR. Riders who rented the bikes Monday through Friday are slightly older than folks who journey on weekends, which dietary supplements the paintings trip usage that become determined from some of the univariable exploration plots.

There are lots more subscriber usage than clients overall. The riding dependancy/sample varies plenty between subscribers and clients. Subscribers use the motorbike sharing machine for work commnute thus most journeys had been on work days (Mon-Fri) and specially all through rush hours (while going to work within the morning and getting off work within the afternoon), whereas customers generally tend to journey for fun inside the afternoon or early evenings over weekends. Subscriber usage peaks out on standard rush hours when people go to work inside the morning and getting off paintings inside the afternoon, which bolstered their utilization motive and goal of riding. Similar pattern changed into now not located among clients who generally tend to trip maximum inside the afternoon or early nighttime for a different motive than the subscribers.

Key Insights for Presentation
Different utilization pattern/habit between the two form of riders are seen from the exploration. Subscribers use the machine closely on work days i.E. Monday via Friday whereas customers journey a lot on weekends, specially within the afternoon. Many journeys focused round 8-9am and 17-18pm on work days for subscribers, yet customers tend to use extra within the past due afternoon round 17pm Monday to Friday. The efficient/short length of usage for subscribers corresponds to their high awareness on rush hours Monday through Friday, indicating the use is by and large for paintings travel. The more enjoyable and flexible pattern of purchaser use indicates that they may be taking gain of the motorcycle sharing machine pretty differently from the subscribers, heavily over weekends and in the afternoon, for city excursion or entertainment purpose probably.
