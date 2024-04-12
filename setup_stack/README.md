# Deploying apps with Docker Stacks  
Deploying and managing cloud-native microservices applications at scale is hard. Fortunately, Docker Stacks are here to help.  

Testing and deploying simple apps on your laptop is easy, but that’s for amateurs. Deploying and managing multi-service apps in real-world production environments.  

This is where Docker Stacks come into play. They let you define complex multi-service apps in a single declarative file. They also provide a simple way to deploy and manage entire application lifecycles — initial deployment > health checks > scaling > updates > rollbacks and more.  

The process is simple. Define what you want in a *Compose file* and deploy and manage it with the `docker stack` command. That’s it!  

The Compose file includes the entire stack of microservices that make up the app. It also includes infrastructure such as volumes, networks, secrets, and more. The `docker stack deploy` command is used to deploy and manage the entire app from that single file. Simple.  

To accomplish all of this, *stacks build on top of Docker Swarm*, meaning you get all of the security and advanced features that come with Swarm.  

In a nutshell, Docker is great for application development and testing. Docker Stacks are great for scale and production.  

From and architecture perspective, stacks are at the top of the Docker application hierarchy. They build on top of *services*, which in turn build on top of containers.  

![image](https://github.com/rezaharasani/deploying-apps-with-docker-stacks/assets/73277136/98ded1c4-a081-4a16-ad9b-fb8b1376d92b)

We’ll divide this section as follows:  
• Overview of the sample app  
• Stack files  
• Deploying stacks  
• Managing stacks  

