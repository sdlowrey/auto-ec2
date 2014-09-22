# Automated EC2 Load Management

This is a small set of simple Linux command line tools that control the launching, 
tagging, and termination of EC2 instances.

It is intended to be used with cron to control a variable load over a finite time 
interval for the purpose of testing network monitoring software.  Also saves $$.

## Configuration

Look at ec2.cfg.template for details.