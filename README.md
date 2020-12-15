# Ansible-playbook
➡️ dockerpb.yml is an Ansible PlayBook that does the following operations in the managed nodes:

    🔹 Configure Docker

    🔹 Start and enable Docker services

    🔹 Pull the httpd server image from the Docker Hub

    🔹 Run the docker container and expose it to the public

    🔹 Copy the html code in /var/www/html directory and start the web server
   
 
 Other files associated with dockerpb.yml are: mywebpage.html
    
 Linkedin Blog URL:   https://www.linkedin.com/pulse/configuring-docker-using-ansible-ishika-sinha

➡️ Playbooks to set up HDFS cluster

    namenode_pb.yml is to configure Namenode
    datanode_pb.yml is to configure Datanode
  
 Other files associated with namenode_pb.yml are: nn_core.xml and nn_hdfs.xml
 Other files associated with datanode_pb.yml are: dn_core.xml and dn_hdfs.xml 
    
 Linkedin Blog URL:  https://www.linkedin.com/pulse/ansible-playbook-set-up-hdfs-cluster-ishika-sinha
 
➡️ Playbook to configure httpd apache webserver and make the service idempotent.
For this, we make use of handlers.

    apache_webserver_pb.yml 

Other files associated with apache_webserver_pb.yml are: vars.yml and web.conf 

Linkedin Blog URL: https://www.linkedin.com/pulse/making-httpd-service-idempotent-using-ansible-ishika-sinha
    
