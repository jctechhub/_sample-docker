# sample-docker
sample for docker images


| Content            | Value                        |
| ------            | ------                        |
| Resource Group    | rg_sampleDocker               |
| Container Registry | crSampleDocker ($0.222 per day) |
| Container Instance 1 | ciSampleDocker |
| Container Instance 2 | ciSampleDockerv3 (with domain name) |
| Container Instance 3 | cihelloworldlinux (from pre-build image) |


#### Note: 
* [Registry pricing](https://azure.microsoft.com/en-us/pricing/details/container-registry/#pricing ) 
** The instance may charge money.

#### Steps

1. Build the project, publish to Azure Container Registry with tags
![image](https://user-images.githubusercontent.com/24492674/140211822-a4ab9752-4aaf-4a96-ad30-6c4eb45d3f61.png)

2. Create Container instance from Container REGISTRY. 
