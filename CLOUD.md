# cloud
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Traditional Approach (Before Cloud)
Before cloud computing, if we wanted to deploy an application. We had to purchase physical servers, similar to how we buy laptops. These servers had high configuration (CPU, RAM, storage, networking).
##### We were responsible for:
    * Setting up networking
    * Managing hardware
    * Maintaining infrastructure
    * Handling security and backups

Even if we bought a powerful server. Usually, we could deploy only one application on it.
  * Most of the server resources remained unused.
  * It was not cost-effective.
  * Scaling required buying more physical servers.
  * Everything had to be managed manually.

### Introduction of Virtualization
To solve this inefficiency, Virtualization was introduced.

#### What is Virtualization
Virtualization allows us to:
  * split a single physical server into multiple virtual machines (VMs).
  * Multiple operating systems, OR Multiple instances of the same OS.
  * Efficiently utilize hardware resources.

#### How It Works
A software called a Hypervisor divides one physical server into multiple virtual environments.
1 Physical Server -> VM1 (Linux), VM2 (Windows), VM3 (Linux).
Now multiple applications can run on the same hardware.

### Global Accessibility
Earlier: Servers were located in one physical place. only that location could directly manage them.
With virtualization and cloud: Infrastructure can be accessed from anywhere in the world, Applications can be deployed from different locations.

### What is cloud
* A platform that provides on-demand, automated, scalable infrastructure to support CI/CD, containers, monitoring, and deployments.
* cloud refers to infrastructure it self , where as cloud computing refers the process or delivery of computing services (servers, storage, networking, databases, software) over the internet, on-demand, without owning physical hardware.
Managed by cloud providers
  * Cloud = Infrastructure
  * Cloud Computing = Using that infrastructure as a service
Instead of buying and maintaining servers: Virtualization + Internet Delivery + On-demand Access + Pay-as-you-use + Scalability
  * You rent infrastructure from cloud providers.
  * You pay only for what you use.
  * It is scalable, flexible, and globally accessible.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Traditional
User → Company Server → App

Cloud
User → Internet → Cloud Provider → Virtual Resources → App
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Types of Cloud
* private
Private Cloud is a cloud infrastructure used exclusively by a single organization, either hosted on-premises or in a dedicated environment.
* public cloud
Public Cloud is a cloud infrastructure owned and managed by a third-party provider and delivered over the internet to multiple customers.
* hybrid cloud
Hybrid Cloud is a combination of Private Cloud and Public Cloud working together.

Simply accessing a physical server from another location does not make it cloud. A private cloud requires virtualization, automation, self-service provisioning, and cloud-like resource management within an organization.













