# PHP Ipam with external DB


This image is configured for use External DB ( VM, RDS or Google SQL), the PHPIpam use mysql or mariadb.


### For use:
    * Change the deployment.yml with your Database IP.
    * Connect in your cluster and run command bellow.

    kubectl apply -f deployment.yml
    
    
 For the HTTPS, I used HAProxy.   
    
    


