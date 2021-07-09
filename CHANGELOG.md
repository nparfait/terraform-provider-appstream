## 1.0.14 (Jul 9, 2021)
BUGFIXES:
* appstream/resource_fleet.go - image update doesn't force new fleet

## 1.0.13 (May 26, 2021)
ENHANCEMENTS:
* Upgrade go version to 1.16

## 1.0.12 (Apr 11, 2021)
FEATURES:
* appstream/resource_fleet.go - add idle_disconnect_timeout

## 1.0.11 (APr 11, 2021)
BUGFIXES:
* appstream/resource_stack.go - trigger change based on application_settings

## 1.0.10 (Apr 8, 2021)
FEATURES:
* appstream/resource_usage_report_subscription.go - add usage report

## 1.0.9 (Apr 7, 2021)
FEATURES:
* appstream/resource_fleet.go - add stream_view, 
* appstream/resource_image_builder.go - add access_endpoints
* appstream/resource_stack.go - add access_endpoints, application_settings

ENHANCEMENTS:
* Upgraded modules
* Updated examples
* Upgrade build - add automated git build 

BUGFIXES:
* appstream/resource_fleet.go - change iam_role_arn to optional
## 1.0.8 (June 15, 2020)

FEATURES:
* appstream/resource_stack.go - user_settings patch from dhruv2511

ENHANCEMENTS:
* Upgraded modules
* Updated examples

BUGFIXES:


## 1.0.7 (June 9, 2020)

FEATURES:
* Added support for role ARN

ENHANCEMENTS:

BUGFIXES:

Patch by: Konstantin Odnoralov <kodnoral@pmintl.net>

## 1.0.6 (May 27, 2020)

FEATURES:
* Added Ability to Remote Image 
* Changes to iamge_arn forces new stack

ENHANCEMENTS:
* updated tf lib to 0.12.25

BUGFIXES:
* image_name changed to image_arn

Patch by: Konstantin Odnoralov <kodnoral@pmintl.net>


## 1.0.5 (May 03, 2020)

FEATURES:
* Assume Role authentication

ENHANCEMENTS:
* authentication: Adopted AWS authentication from terraform-provider-aws
* structure: changed structure and build setup of provider

BUGFIXES: 


