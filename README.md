
# [APKGen](http://apkgen.digital)
This project is about automated generation of Android Application from URL. It uses various Devops tools such as Jenkins, Rundeck, RabbitMQ, Log4J. This repository is a link to other repositories that were used for development of this project.


### APKGen Web 
This is the link to the APKGen website code. It contains all the required files for build and deployment. Newer features are directly integrated into this website and changes are deployed through Jenkins triggers. \
[APKGen Web Github](https://github.com/tamasane/apkgen)

### Android SDK and Cordova Server
[Android SDK Installation and Testing Script](https://github.com/vbh-git/apkgen_sdk) \
This is the link to the setup script. This script can be further modified to add newer versions of SDK. It also contains an Uninstall script that reverses any changes made by the Install script.

### APKGen Job
The automated android package (APK) generation is the job of the website. The various steps that need to take place when a job is triggered are specified in form of a script. Further, as the website evolves, more jobs can be added to this repository.
[APK Generation Script](https://github.com/vbh-git/apkgen_job)

### APKGen Template
This contains link to various types of templates that are supported and can be used for APK Generation. Currently only one template exists for the URL  based Application Generation. The usage of this template can be seen in the corresponding job.
[Template 1: URL Based Application](https://github.com/vbh-git/apkgen_template1)

Further, more templates can be created based on the jobs specified.

### RabbitMQ Consumer
This is the link to the implementation and build details of the RabbitMQ Consumer which is required to serialize jobs on the website. \
[RabbitMQ Consumer](https://github.com/vbh-git/ConsumerApplication)