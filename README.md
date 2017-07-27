# Portland 🛫 To The World
Get cheap flights from PDX to places around the world using Google QPX Express


We can make [50 queries per day](https://developers.google.com/qpx-express/v1/pricing) to the API. 


```
curl -d @FCO.json --header "Content-Type: application/json" \
https://www.googleapis.com/qpxExpress/v1/trips/search?key=$GCP_API_KEY
```