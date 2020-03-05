# vue_fe_dotnet_be_okta_auth
A Simple example CRUD with segregated MC in dotnet & VC in vue.js / node.
It also includes an user authentication example implementation of an integration of Okta's authentication services.

# References
[Okta based CRUD](https://developer.okta.com/blog/2018/08/27/build-crud-app-vuejs-netcore#set-up-authentication-for-your-vue-application) is a helpful read, but the example is broken.
# Notes
  * Please uncomment [here](https://github.com/kryochronic/device_tracker_be/blob/ffd616478398e99daa367e02c78a15b134bc3f90/Controllers/DeviceRecordsController.cs#L12) to enable authorsation from Okta for the backend as well.
  * Replace Okta's credentials with your own, since it might stop working whenever I delete the credentials. [Here](https://github.com/kryochronic/device_tracker/blob/29a17f208aa9f2a3fb2c464d32a311047f3da2e0/src/router/index.js#L12) and [here](https://github.com/kryochronic/device_tracker_be/blob/ffd616478398e99daa367e02c78a15b134bc3f90/appsettings.json#L2).
  
 # Usage
 
 ```shell
 git clone https://github.com/kryochronic/vue_fe_dotnet_be_okta_auth.git
 cd vue_fe_dotnet_be_okta_auth
 git submodule init
 git submodule update
 cd device_tracker
 npm install
 npm run serve &
 cd ../device_tracker_be
 dotnet run &
 ```
 
