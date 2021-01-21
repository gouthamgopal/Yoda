# Weather Forecast Dashboard(Advanced distributed system)

### Thanks for checking us out!

## Collaborators
- Goutham Gopal
- Shruti Desai
- Tanvi Thote

### Checkout our [Yoda Page](https://github.com/airavata-courses/Yoda/wiki) for more details on how to clone and contribute to out repo!
[Release 1](https://github.com/airavata-courses/Yoda/wiki/Release-Notes---Assignment-1)
<br/>
[Release 2](https://github.com/airavata-courses/Yoda/wiki/Release-Notes---Assignment-2)

### Details

Each microservice has been linked to their own different branches for easier maintenance and updation.
The list of microservice branches are as follows:

- UserInterface - Handling the front end of the application.
- UserAPI - Handling the authentication for the application.
- GatewayServerAPI - Gateway server which routes all API requests to the relevant microservice.
- DataRetrievalAPI - Used for retrieving data from NEXRAD api.
- DataModelAPI - Used for modelling the API data for processing.
- DataPostProcessAPI - Used for post processing of the data into required datsets for user consumption.
- SessionManagementAPI - Used to manage user sessions and their data processing requests through a pipeline.
