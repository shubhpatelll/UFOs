# UFOs

## Overview of the UFO
This analysis was performed on Unidentified Flying Objects (UFOs) data to visualize information. The data was stored in a JavaScript array. The analysis was 
extended to filter data according to the use-input such as city, state, country and the shape of the UFOs.

### Resources
Data source: data.js

Software: JavaScript, HTML & CSS and Bootstrap


## UFO Analysis Results
The main goal of this analysis was to extract data from a JavaScript file and show them in webpage using a HTML table. Furthermore, improve the webpage 
so that users can filter the data according to their requirements.  The data was stored as objects in JavaScript object. The following image shows an example of 
one object in the data file.

  <img width="475" alt="Screen Shot 2022-11-28 at 5 07 28 PM" src="https://user-images.githubusercontent.com/112113327/204391305-5b7735de-5861-4868-9036-3018bf132044.png">

The JavaScript object in the preceding image is very similar to a dictionary in python. Keys are "datetime", "city', "state', "country", "shape", "durationMinutes" and "comments". First, data from the JavaScript file was converted to a HTML table and displayed on the web browser. The image is shown below.

  ![Screen Shot 2022-11-28 at 9 11 23 PM](https://user-images.githubusercontent.com/112113327/204421861-a84c7615-4415-4761-b4b6-105204325207.png)


Six observations of UFOs are displayed in the preceding image and the fourth row represents the object shown in the previous image. It can be observed that the observations have different values other than the country. 
Therefore, the next step is to include filters so users can change their search criteria. To achieve that, five different search boxes were included into the webpage and shown in the following image.


  ![Screen Shot 2022-11-28 at 5 47 38 PM](https://user-images.githubusercontent.com/112113327/204397126-025382c3-2c1e-4a3a-9e3a-222feea2c5ac.png)

With the help of these search boxes, users can now filter the results according to their interests. For example, if a user wishes to find the observations 
in the Oregon state (or), it can be obtained from the webpage as shown below.

  ![Screen Shot 2022-11-28 at 5 54 52 PM](https://user-images.githubusercontent.com/112113327/204398062-3c66fbfd-1c43-4931-bc1e-549ad34727b7.png)

Also, users can use more than one filter at the same time. For example, to see the observations in Massachusetts (ma) with the circular shape, following filters can be used. 


  ![Screen Shot 2022-11-28 at 8 53 44 PM](https://user-images.githubusercontent.com/112113327/204419138-d999a471-256a-4c51-a23f-bc2e66397517.png)

According to the given search criteria, the only available observation is shown in the preceding image.



## UFOs Summary
Even though this web browser is very helpful for users to filter their information, one of the drawbacks is that the user has to inspect the options for each filter if the user doesn’t know what exactly he/she is looking for. In this case, users must inspect the default table to see what the available options for filters such are as country, state and shape etc. This difficulty can be removed by introducing a dropdown menu for each filter. This would be a great inclusion to improve the value of this web browser.  

Another diffulty in this web browser is to clear the search criteria. Users have to refresh the page to clear the data. However, it would be very convenient if a clear button is included.

One last thing to improve this search would be adding filters for column headers as well. In that way, users can pick the columns they are interested. 
