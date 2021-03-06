# The AWS deep dive session at Manchester University

20th September 2018

## Agenda for the day

This has yet to be agreed. 

Suggestions from Paul Grist

1.	Workloads – creating a taxonomy of what jobs Manchester/Leeds has today, what could/would work in the cloud

2.	Current and Target architectures – Simon whiteboarded Manchester’s current platforms, would be great to complete that picture with Leeds, and outline future reference architectures 

3.	Roadmap for workload migration – what could migrate, when, and how, w/focus on Multi-account strategies to support research community, and related costing/charging

Suggestions from Simon Hood:

1. What could go wrong --- I think Charlotte/Paul mentioned a high-profile
    example last time they were here?  (Yale?)

 2. Scaling of HPC open-source apps across AWS VM instances
     -- Produce a set of *repeatable* results with input data,
        scripts, output data, etc all on Github or similar
     -- Need a list of open-source applications
     -- scale from one node (16 cores?) to 1024(?) cores
     -- need an estimate of number of CPU-hours
     -- and hence cost --- will AWS cover this?

 3. Building a Data Centre in AWS on-the-fly, e.g., for "Bursting"
     -- Terraform?
         -- https://www.terraform.io/
         -- terraform scripts for
	     -- traditional HPC clusters
	     -- other things --- VM farms...

 4. Moving from VMware on-site to hybrid on-site/AWS to non-WMware
     -- how?

 5. A Data Save Haven in AWS
     -- e.g., for pseudo-anonymised data
     -- e.g., for patient-identifiable data
     
 6. Accessing/Mirroring on-site storage from/in AWS:
    -- simply accessing
    -- async mirroring
    -- sync mirroring
   for
    -- DR
    -- acessing users' data in AWS-based compute/VMs


Mike Pacey added

Under section 2, I'd add a discussion on the hardware underlying the cloud solution - CPU type, interconnects, physical proximity/topology of the virtual cluster.

For apps, I've asked the PIs of Lancaster's largest Polaris projects; I currently have suggestions for COSA (CFD / wind turbine modeling), CASTEP (DFT) and CASINO (QMC)


## Attendees 

Add your name here.

* Martin Callaghan (University of Leeds)
* Mike Croucher (University of Leeds)
* Simon Hood (University of Manchester)

