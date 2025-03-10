# Test program for simple checks

## Pre-requisites

1. Pulumi CLI - <https://pulumi.com/docs/iac/download-install/>
1. Account in Pulumi Cloud - <https://app.pulumi.com>
1. Organisation that account has admin access in that organisation.

## Steps

1. Clone this repo: `git clone https://github.com/pierskarsenbarg/simple-random.git`
1. Create a new stack `pulumi stack init {orgname}/dev`
1. Select stack `pulumi stack select {orgname}/dev`
1. Run update `pulumi up` and check that it works
1. Get output `pulumi stack output myPassword --show-secrets`
1. Destroy `pulumi destroy`
1. Delete stack `pulumi stack rm {orgname}/dev`
