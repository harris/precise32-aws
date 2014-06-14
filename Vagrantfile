# -*- mode: ruby -*-
# vi: set ft=ruby :

# From http://cloud-images.ubuntu.com/locator/ec2/
#
# name: precise
# version: 12.04 LTS
# arch: i386
# instance type: ebs

Vagrant.configure("2") do |config|
  config.vm.provider :aws do |aws, override|

    aws.region_config "ap-northeast-1", :ami => "ami-b5b9f6b4"
    aws.region_config "ap-southeast-1", :ami => "ami-22702c70"
    aws.region_config "ap-southeast-2", :ami => "ami-13bcd929"
    aws.region_config "eu-west-1",      :ami => "ami-8537f8f2"
    aws.region_config "sa-east-1",      :ami => "ami-4708a45a"
    aws.region_config "us-east-1",      :ami => "ami-ae9665c6"
    aws.region_config "us-west-1",      :ami => "ami-56585f13"
    aws.region_config "us-west-2",      :ami => "ami-bd582a8d"

    override.ssh.username = "ubuntu"
  end
end
