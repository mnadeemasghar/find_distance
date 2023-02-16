# Google Cloud Function: Calculate Distance between Two Lat-Long Points

This is a Node.js function for calculating the distance between two latitude-longitude points using the Haversine formula. The function takes four parameters, `lat1`, `lon1`, `lat2`, and `lon2`, which are the latitude and longitude values for the two points. The function then calculates the distance between the two points in meters using the Haversine formula.

To use this function in a Google Cloud Function, follow these steps:

1. Clone this repository to your local machine using `git clone`.
2. Install the required dependencies using `npm install`.
3. Deploy the function to your Google Cloud project using `gcloud functions deploy`.
4. Test the function by sending a request with the latitude and longitude values for the two points.

## Usage

To use this function, send a GET request to the function's endpoint with the latitude and longitude values for the two points in the URL. For example:

https://[YOUR_CLOUD_FUNCTION_URL]/calculateDistance/[LATITUDE_1]/[LONGITUDE_1]/[LATITUDE_2]/[LONGITUDE_2]


The function will return a string response that includes the calculated distance in meters.

## Dependencies

This function has the following dependencies:

- `express`: version 4.17.1

These dependencies are included in the `package.json` file and will be installed automatically when you run `npm install`.

## License

This function is licensed under the MIT License. See the `LICENSE` file for more information.
