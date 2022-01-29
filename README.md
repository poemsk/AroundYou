# AroundYou

This is an sample to explore [Mapbox Map SDK](https://docs.mapbox.com/android/maps/guides/) and [Mapbox Search SDK](https://docs.mapbox.com/android/search/guides/). 

#### Configure Secret Token

This project is using stored secret token in global **gradle.properties** file. Please follow official [Mapbox Documentation](https://docs.mapbox.com/android/maps/guides/install/?size=n_10_n#configure-credentials) to do the same. 

#### Configure Public Token 

This project has stored public token in **local.properties** file which is not committed to Github. 

Please declare the following in local.properties under the project: 
```groovy
mapbox_access_token=your_public_token
```
