# ec2-test-kichen

This repository contains Test Kitchen template for testing your chef recipes in the actual EC2 instance. 

## Usage

1. Install ChefDK. 
2. Install AWS command line tools.
3. Write chef recipe!
4. Run `kitchen converge` in the root directory of this project.
5. Run `kitchen login` and see your recipe has executed correctly.
6. DON'T FORGET TO RUN `kitchen destroy` as soon as the test finishes.

## References

For Test Kitchen, please look at https://kitchen.ci/
For EC2 attributes, please refer to https://github.com/test-kitchen/kitchen-ec2
