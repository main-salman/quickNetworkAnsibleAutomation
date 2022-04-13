# Quick and Dirty Network Ansible Automation

So, in the last couple of years (between 2020-2022), Ansible has changed significantly, with the introduction of [Collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html), and a number of older commands either already deprecated or slated to be deprecated. 

Some core Ansible files such as hosts.ini are also to be deprecated and replaced with YAML equivalent instead (i.e. hosts.yaml - or whatever else you want to name it). Further, Ansible is also encouraging administrators to use "connection = network_cli" for network automation instead of "connection = local" that the network geeks were using prior to 2020, and a number of other changes.

All of this has resulted in playbooks that look significantly different than before. All of this is a GOOD change - this will make Ansible scale better and ultimately be an even more awesome tool - but it is also a bit of a hassle to update playbooks.

This particular couple of playbooks are just a quick and dirty starting point for network automation in case you are starting on your network automation journey in 2022. Unfortunately a lot of previously shared playbooks (and related vars, hosts, and config files) don't function well or at all with current (April 2022) Ansible version 2.9. In this repository, I have included COMPLETE set of files (which is often missing in older examples) to get started with network automation. I have also even included a sample hosts file which you can use as a template to update your hosts file (if you are not using DNS in the lab environment like me).

This repository may be helpful for anyone starting in April 2022 or later to use as a starting point. 
