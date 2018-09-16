# aws-cloudformation-101

AWS Cloudformation templates from beginner to advanced

#What is Cloud Formation good for?

Simplify infrastructure management
Infrastructure as code
Quickly replicate infrastructure
Control and track changes to infrastructure

#Cloud formation template basics

JSON formatted file that describes AWS infrastructure

#Template sections

AWSTemplateFormatVersion
Description
Metadata
Parameters
Mappings
Conditions
Outputs
Resources \*required

#Section overview

AWSTemplateFormatVersion - specifies the aws template version

Description - text string to describe the template

Metadata - JSON objects that describe additional information about the template

Parameters - specify values that can be passed to the template at runtime

Mappings - A mapping of keys and associated values to specify conditional parameter values - similiar to lookup table

Conditions - defines conditions that control wether certain resources are created or properties are assigned a value during stack creation or update

Outputs - the values returned on creation or update

Resources \*required - specify the stack resources and thier properties
