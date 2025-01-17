# CDP_Intf_Desc
Playbook to update Interface descriptions based on CDP Neighbor Information
Playbook contains one role. 
Inside the role are three tasks:
*  1st playbook will gather hostname from device, gather CDP Neighbor information from that device and save the data into a Yaml file.
*  2nd playbook will gather configurations of CDP connected ports and save them to a file. 
*  3rd playbook will push updated description to each CDP neighbor interface with proper Niehgbor information.
