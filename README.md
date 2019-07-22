# OR-Tools for AWS Lambda

A Lambda layer containing Google OR-Tools for combinatorial optimization.

Check [Google OR-Tools oficial repository](https://github.com/google/or-tools)

# How to use 

You can use a pre-deployed ARN `arn:aws:lambda:us-east-1:262106746332:layer:or-tools-layer:3`

Or you can build for yourself. See tutorial below.

Check [AWS docs](https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html) for how to use lambda layers

# How to create your own layer

Clone this repo

`git clone https://github.com/matheusmessora/or-tools-layer.git`

Run build.sh

`$ ./build.sh`

Create a new layer using the zip file