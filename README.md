<h1 align="center"><img width="30px"> I'M ARTIFICIAL INTELLIGENCE PROGRAMMER WITH PYTHON</h1>
<!-- 
<div align="center">
  <img src ="./banner.png" />
</div>
-->
<!-- <p align="left"> <img src="https://komarev.com/ghpvc/?username=jorneylopez&label=Profile%20views&color=0e75b6&style=flat" alt="jorneylopez" /> </p> -->
 <br/>

## 👨🏻‍💻 About Me:

<img  src="./programming.gif" height="290px" align="right" />
<br>

- All about me is at **[My Website](https://jompy31.github.io/)**



## Description

These first steps in your microservices learning journey with the .NET platform. Before we dive into the repository topics,let's review the fictional client application that drives the requirements for the system to be built, and the high-level architecture of all the necessary components. Let's imagine a video game where the player will need to acquire a series of items to stay healthy, become stronger, and survive the multiple dangers that await him on his adventures. There will be a series of stores that will allow the player to purchase items like potions, antidotes, and even swords and shields. These items have a price, and to purchase them, the player will need to present the right amount of some sort of currency which we will just call gil. Once the player successfully purchases an item, it then goes into his inventory bag, where it will be available for him whenever he needs it. Now, the client side of this game, the app that runs in the player's device, is already being built by our company's client team, so you don't have to worry about it. And in fact, this client app is not part of this repository. Our team has been chartered with building the backend services of this game which the client will heavily depend on to be able to store the items catalog, the players' gil and inventory, and to enable the in-game purchase experience. Let's now look at the high-level architecture of the system. To support the client app, you will build what we will be calling the Play Economy system. Here we have identified four microservices, Catalog, Inventory, Identity, and Trading. Each of these services will have their own database that has no relationship with other databases, and that are of exclusive use by the owning service. For interservice communication, we will introduce a message broker that will allow the services to publish and consume messages asynchronously. Our clients will not talk directly to all these microservices, but instead, they will do it via an API gateway, which will give us a lot of flexibility to make changes to the services without impacting the clients, and will let the services focus on their business while delegating multiple crosscutting concerns to the gateway. There is also a web frontend component just outside of our API Gateway. This is a web portal where you can manage the items catalog, the players and their inventory, and it also includes a store section where players can purchase items. That way you can exercise an end-to-end purchase scenario even if we don't have access to an actual game client. We won't be building this portal in this repository, but you will get access to all its source code so you can run it in your box, and connect it to the microservices via the API gateway.

Finally, there are a few infrastructure components like Logging, Distributed Tracing, and Monitoring that our microservices will interact with and that will greatly help us troubleshoot issues, and make sure the whole system remains healthy. In terms of the tech used for each component, all the microservices are built using .NET 5 and ASP.NET Core 5. The databases live in a MongoDB server, and the message broker is enabled via RabbitMQ. For distributed messaging, we use the MassTransit framework. Authentication and authorization are enabled via the IdentityServer4 framework. For our API Gateway, we will use Envoy proxy, and the frontend is a single page React application. All the logs will be collected and centralized via Seq. Then we will use OpenTelemetry in conjunction with Jaeger to enable distributed tracing. And for monitoring, we will Prometheus and Grafana. Also, all these infrastructure services will of repository run via Docker containers, so you won't need to install anything other than the .NET SDK to run the microservices and Docker to run the supporting infrastructure. 

## Make it Your Own!

### 1. Make sure you have what you need
To build this website, you will need to have latest .NET Software Development Kit or SDK/ Visual Studio Code/ Docker Desktop , downloaded and installed on your machine. If you don't already have it, you can get it <a href="https://dotnet.microsoft.com/download/">.net</a> / <a href="https://docs.docker.com/get-docker/">Docker</a> / <a href="https://aka.ms/vscode/">VsCode</a>
### 2. Build a microservices via .Net CLI
* run in terminal in src folder: `dotnet new webapi -n Play.Catalog.service`.
    * play.catalog.services.csproj: Define how the project will be build and .net version.
    * program.cs: Application entry point.
    * launch.json/task.json: Build and debug application.
    * Startup.cs: Service registration and request pipeline configuration.
    * weatherforecastcontrollers.cs: Gruop of actions that handle requests.
    * weatherforecast.cs: That has been setup in these template
    * settings.json: The application URL will be define
* run in terminal `dotnet build`.

### 3. Enjoy your new Resume Website
When you're all done, run `dotnet run` again and you'll see your microservices working! Congratulations!


## 🛠️ Technologies and Tools I use:

<p>
<img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"  height="25px"/>
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"  height="25px"/>
<img alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white"  height="25px"/>
<img alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white"  height="25px"/>
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"  height="25px"/>
<img alt="git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" height="25px"/>


</p>

## ❤️ Let's get connected:

<p>
  <a href="https://www.linkedin.com/in/jean-pierre-barnett-caruzo-452b9a1b1/" target="_blank"><img alt="LinkedIn" target="_blank" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"  height="30px"/></a>
<!--   <a href="https://www.instagram.com/#" target="_blank"><img alt="Instagram" target="_blank" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"  height="30px"/></a>
 -->
  <!-- 
  <a href="#" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white"  height="30px"/></a>
  <a href="#" target="_blank"><img alt="Blog" src="https://img.shields.io/badge/Blog-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white"  height="30px"/></a>
-->
  
</p>

