GitHub Example
===================

This is an example of a simple json client based on https://github.com/jiraguha/feign/tree/master/example-github example

Using Feigh without Spring, annotations... It is just needed to pass by openFeign Api's to make a custom http client.

Using sping-cloud it will need to import FeignClientsConfiguration.class as shown in http://ryanjbaxter.com/cloud/spring%20cloud/spring/2016/10/20/manual-feign-clients.html

For Custom error handling:
https://github.com/OpenFeign/feign/wiki/Custom-error-handling

Also interesting:
http://blog.ippon.fr/2016/09/21/feign-encore-un-client-http/

=== Building example with Gradle
 Install and run `gradle` to produce `build/github`
