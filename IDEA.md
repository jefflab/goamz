# Goal

Make it easier to write unit tests for projects that use the goamz library

# Plan

Make ec2.New return an interface rather than a concrete class so it can be swapped with a test double

# 