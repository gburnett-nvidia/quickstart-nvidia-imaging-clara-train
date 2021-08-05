# quickstart-nvidia-imaging-clara-train
## NVIDIA Clara Train SDK for Medical Imaging on the AWS Cloud

This Quick Start deploys the Clara Train SDK as a highly available service, based on Amazon Elastic Container Service (Amazon ECS).

[NVIDIA Clara Parabricks](https://developer.nvidia.com/clara-parabricks) is a computational framework supporting genomics applications from DNA to RNA. It employs NVIDIA’s CUDA, HPC, AI, and data analytics stacks to build GPU accelerated libraries, pipelines, and reference application workflows for primary, secondary, and tertiary analysis. Clara Parabricks is a complete portfolio of off-the-shelf solutions coupled with a toolkit to support new application development to address the needs of genomic labs.

This Quick Start offers two deployment options:

- Deploying NVIDIA Clara Train SDK into a new virtual private cloud (VPC) on AWS
- Deploying NVIDIA Clara Train SDK into an existing VPC on AWS

You can also use the AWS CloudFormation templates as a starting point for your own implementation.

After the CloudFormation templates have been deployed, the [stack outputs](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/outputs-section-structure.html) contain a link to the load-balanced URL for the AI-Assisted Annotation APIs and Annotation Server, and the DNS name of the Amazon Elastic File System (Amazon EFS).

The command line Clara SDK tools can be used by SSH, via the bastion host, to the ECS host. Then, open a shell to the Clara container running on the ECS host.

For architectural details, best practices, step-by-step instructions, and customization options, see the 
[deployment guide](https://fwd.aws/bzV9V).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.
If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
