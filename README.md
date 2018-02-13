# ContextLoadsSample

Reference: <https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html>

Spring applications rely on loaded dependencies to perform their work.  It can be beneficial to verify that these dependencies are loaded on startup.  To achieve this, spring applications generated from the [Spring Intializer](http://start.spring.io) come with the contextLoads() unit tests.

This test loads the application context locally allowing you to validate that your dependcies, controller, etc. have loaded correctly.

![alt text][Context Loads.png]