# rp
Docker Container for RosterPlus

Docker Container Design for RosterPlus V2.1 for Linux CentOS base on the following packages for Windows.
GroundStar_RosterPlus_V2.1.zip
RosterPlus_Model_test_V2.1.zip

First approcah Design consist of four (4) containers:  
Base:  		      centos:latest 
First Layer: 	 	centos-oracle-java:8.73
Second Layer:  	tomcat7-jre8
Third Layer: 	  myrosterplus:2.1
Fourth Layer:   test_myrosterplus:2.1
