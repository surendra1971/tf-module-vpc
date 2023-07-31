# tf-module-vpc

Information of vpc id, subnetid, cidrs are important and are needed by other modules which are created remotely

...

So, how are we going to pass this information between two different statefiles.

* Whatever the information that you would like to share, print that output.

* Once you print something as an output, that information will also be recorded on the STATEFILE.

* Once something is recored in the statefile, other resources can access it by using "terraform remote state datasource"

...