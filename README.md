# Smart-India-Hackathon

The interface contains Retrofit annotations that holds the parameters and request methods
It'll call the webservice to save the JSON data that'll be sent (POST) as parameter

ServiceGenerator class will generate Retrofit instances whenever we need to use it. It contains the Gson convertor.

The JSON data is in the MainActivity and rest of the code is the simple use of Retrofit Library

here, the base url is http://yourwebserviceapi/"
We used JsonObject of google.gson library because we are using Retrofit so Gson helps us to convert JSONObject to JsonObject

Also, for any Android Studio Error why syncing the gradle, update your Android Studio.
