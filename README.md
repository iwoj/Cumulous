Cumulous
========

Simple cloud server management, from the command line.

- **list-servers**
  - Outputs a list of all your [EC2](http://aws.amazon.com/ec2/) servers
- **create-server [name]**
  - Creates a new server with the given tag name. Returns the hostname.
- **kill-server [name]**
  - Kills all servers matching the given name.

Be patient. These scripts may take up to twenty or thirty seconds to run sometimes.

Requirements
------------

You will need the EC2 Command Line Tools and EC2 AMI Tools a few security key files to get things rolling.

You will need you pk-...-.pem and cert-...-.pem files to be symlinked to pk-<instance_name>-pem and cert-<instance_name>.pem.

Mac OS X
- http://craigcottingham.github.com/2011/06/30/ec2-pantry-raid-i.html

Linux
- https://help.ubuntu.com/community/EC2StartersGuide

Other Platforms
- http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/SettingUp_CommandLine.html


