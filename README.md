# roadraise
capture and share your road trip to fundraise for a cause important to you. bring the community on your journey.
https://www.roadrai.se

## tech stack
our product is full stack aws using the following technologies:
- route 53 (domain hosting and dns configuration)
- cloudfront (caching for performance and availability)
- s3 (holds the javascript, css, html, and image assets in this github repository)
  - bootstrap
  - jquery
  - amcharts
- api gateway (has all of the apis created - not possible to export to this repo)
  - /users - GET, POST
  - /trips - GET, POST
  - /stops - GET, POST
- dynamodb (data storage)

## charitable donations
donations are being processed via global giving via button to ensure pci compliance. these donations can be processed via globalgiving api in the future, yet we would not have been able to achieve pci compliance in the timeframe of startup bus. it was important to have a secure donation experience where we could demonstrate willingness to donate to charity.
