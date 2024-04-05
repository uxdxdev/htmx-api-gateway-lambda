
# HTML API Gateway Lambda

[uxdx.dev/htmx-api-gateway-lambda](https://uxdx.dev/htmx-api-gateway-lambda/)

This shows a very simple example of sending a GET request using HTMX to a GET endpoint on AWS API Gateway returns some HTML content. The `<div id="message">` element is then replace with the content returned from the API Gateway endpoint.

![](html-page-htmx-get-request-api-gateway.png)

![](aws-api-gateway-get-method-with-cors.png)

### API Gateway endpoint information

- You must enable CORS for the endpoint and set the `Access-Control-Allow-Origin` to `*` or the origin of the server you are sending the request from.