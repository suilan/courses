# Creating VM on Azure Cloud

## Learning about Virtual Machines(VM)
[Read More](../../virtual_machine/README.md)

## Finding the VM Service
- Acessing the [Azure Portal](https://portal.azure.com/?l=en.pt-br#home)
- Select the **Virtual Machine** (called **Azure Service**)
  - In the home page

  ![Home Page](../_images/lab00-find_service_home.jpg)

  - On the left menu 

  ![VM service in the Left Menu](../_images/lab00-find_service_menu.jpg)


  - Or in the Search Box

  ![VM service in the Search Input](../_images/lab00-find_service_search_input.jpg)

## Creating the VM
- In the Virtual Machine Page, select the **+ Add** option

  ![Create new VM](../_images/lab00-add_vm.jpg)

- Select One f the options: **Virtual Machine** or **Start with a preset configuration**

  ![Options to create the VM ](../_images/lab00-add_vm_options.jpg)

  - The first option, **+Virtual Machine**, will create a VM from scratch.

  ![Create the VM From Scratch ](../_images/lab00-add_vm_from_zero.jpg)

  - The second option, **+Start with a preset configuration**, will be based on a template available in the Azure Cloud 
  
  ![Create the VM from Template ](../_images/lab00-add_vm_from_template.jpg)

### Creates a VM from Scratch
- First, you have to create or choose a [Resource Group](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal#what-is-a-resource-group) that will contain the resource
  - *A resource group is a container that holds related resources for an Azure solution*


  ![Create the VM - Create ou choose a resource group ](../_images/lab00-add_vm_create_resource_group.jpg)

  - **Create new** resource group called "**AZ204_Ambiente**"
  - **Virtual machine name** as **AZ204AmbienteVM**
  - **Region**: **(US) East US**
    - *When you choose a Region you have to consider latency and costs*
  - [Availability Options](https://docs.microsoft.com/en-us/azure/virtual-machines/manage-availability)
    - https://livebook.manning.com/book/learn-azure-in-a-month-of-lunches-second-edition/chapter-7/21
    - *No infrastructure redundancy required* (No redundancy) **(Choose this one)**
    - *Availability zone* - Lets you distribute VMs across physically isolated segments of an Azure region to further maximize your application redundancy
    - *Availability set* - Lets you logically group VMs to distribute them across a single Azure data center and minimize disruption from outages or maintenance updates.




VM Name
AZ204_AmbienteVM

VM Resource Group
AZ204_AmbienteRG
