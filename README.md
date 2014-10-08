Attempting to create a proxy with Jetty.

Start by running `mvn jetty:run`

Navigate to http://localhost:8080/cnn

Expect to see content from http://cnn.com, but the page just keeps trying to load until it receives a `504 Gateway Timeout` error.
