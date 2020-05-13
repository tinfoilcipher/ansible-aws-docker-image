Source Dockerfile for https://hub.docker.com/repository/docker/tinfoilcipher/ansible-aws.

This container is intended to provide a ready-made environment for running AWS-targeted Ansible Playbooks and already includes the relevant pip modules (Python 2.7.18):

 * boto
 * boto3
 * botocore
 * ansible

Building will require installation of docker-io package.

For use in a pipeline deployment and contains a single ENTRYPOINT named **ansible**.

Files intended for use in conjuction with the blog post Improving Your CI/CD Pipeline With Custom Docker Images https://www.tinfoilcipher.co.uk/?p=1220
