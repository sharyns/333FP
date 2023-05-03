# 333FP
This project was created with Eclipse and uses Maven for the build and testing, and Docker for the build and deployment purposes.

-----------------------------------Maven-----------------------------------

A Maven file was created in Eclipse, with all tests and classes stored under the apropriate folders and packages.

![EclipsexMaven](https://user-images.githubusercontent.com/70311132/235823956-c6ebe553-284b-4f29-adca-a410949293f8.png)



-----Build-----

Right clicking on the Maven file and selecting Run As -> Maven Build will allow us to build the Maven file, and results in a Build Success message.

![EclipsexBuild](https://user-images.githubusercontent.com/70311132/235823870-58c2531f-8eee-4b2b-8f1e-ad31f71225df.png)

![EclipsexBuild(1)](https://user-images.githubusercontent.com/70311132/235823879-69b67715-d5a7-4ac6-847d-8eae413668f4.png)



-----Tests-----

We can see the test results and coverage through the Launch Tests button.

![EclipseTests](https://user-images.githubusercontent.com/70311132/235824720-f5e464c6-9ab6-4ba5-8b73-bd0de7ffa720.png)



-----------------------------------Docker-----------------------------------

A docker file was created and written inside the Maven project, then is connected through a TCP connection and a host to connect to Docker daemon. In order to build a docker image, we right click on the Dockerfile and select Run As -> Docker Image Build.  After succesfully building, we can see it listed under docker images.

![EclipsexDocker](https://user-images.githubusercontent.com/70311132/235824426-eff18da8-4128-4bee-ac65-a8713120fb19.png)
