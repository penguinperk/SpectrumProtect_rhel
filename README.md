Add the Floating IP of the new host  into the hosts file 
Attach the Block Storage volume (Container) to the VM
Attach the Block Storage volume (DBVol) to the VM

Log into the host using the FIP 
Run lsblk 
echo "- - -" > /sys/class/scsi_host/host*/scan
Update the default.config file to the correct volumes
- SSD is the DB Volumes 
- Standard is the Contaiener Volumes 


echo "- - -" > /sys/class/scsi_host/host*/scan


