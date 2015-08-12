# resting
Lightweight Java component to consume REST service and transform response into objects

When we invoke a web service, often the end goal is to take the HTTP response and transform it into value objects which will be rendered in the application. Resting can be used to achieve exactly that.

Resting, a lightweight REST framework in Java, can be used to invoke a RESTful web service and convert the response into custom Java objects from the client application. Because of it's simplicity, resting is suitable for Android and other handheld devices.

Goals of resting

  1. Expose simple get(), post(), put() and delete() methods to consume REST services
  2. Support for all the commonly used MIME types like JSON, XML, ATOM and YAML
  3. Enable both HTTP and HTTPS (SSL) invocation of RESTful web services
  4. Support for basic authentication
  5. Support for proxy
  6. Support for arbitrarily complex marshalling and unmarshalling of data during transformation
  7. Support for custom representation of collections in REST request
  8. Lightweight, simple and fast. Ideal for Android.
