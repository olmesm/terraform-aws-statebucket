<!-- This file was automatically generated by the `build-harness`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->
[![README Header][readme_header_img]][readme_header_link]

[![Slalom][logo]](https://slalom.com)

# terraform-aws-s3 [![Build Status](https://travis-ci.org/jameswoolfenden/terraform-aws-statebucket.svg?branch=master)](https://travis-ci.org/jameswoolfenden/terraform-aws-statebucket) [![Latest Release](https://img.shields.io/github/release/jameswoolfenden/terraform-aws-statebucket.svg)](https://github.com/jameswoolfenden/terraform-aws-statebucket/releases/latest)

Terraform module to provision an AWS [`Codecommit`](https://aws.amazon.com/codecommit/) CI/CD system.

---

This project uses the build-harness this a is modified version of the project ["SweetOps"](https://cpco.io/sweetops) from Cloudposse. Sweet indeed.
[<img align="right" title="Share via Email" src="https://docs.cloudposse.com/images/ionicons/ios-email-outline-2.0.1-16x16-999999.svg"/>][share_email]
[<img align="right" title="Share on Google+" src="https://docs.cloudposse.com/images/ionicons/social-googleplus-outline-2.0.1-16x16-999999.svg" />][share_googleplus]
[<img align="right" title="Share on Facebook" src="https://docs.cloudposse.com/images/ionicons/social-facebook-outline-2.0.1-16x16-999999.svg" />][share_facebook]
[<img align="right" title="Share on Reddit" src="https://docs.cloudposse.com/images/ionicons/social-reddit-outline-2.0.1-16x16-999999.svg" />][share_reddit]
[<img align="right" title="Share on LinkedIn" src="https://docs.cloudposse.com/images/ionicons/social-linkedin-outline-2.0.1-16x16-999999.svg" />][share_linkedin]
[<img align="right" title="Share on Twitter" src="https://docs.cloudposse.com/images/ionicons/social-twitter-outline-2.0.1-16x16-999999.svg" />][share_twitter]

It's 100% Open Source and licensed under the [APACHE2](LICENSE).

## Usage

Include this repository as a module in your existing terraform code:

```hcl
module "statebucket" {
  source     = "git::https://github.com/jameswoolfenden/terraform-aws-statebucket.git?ref=master"
}
```

## Makefile Targets

```cli
Available targets:

  help/all:
                          Display help for all targets
  help/short:
                        This help short screen
  help:
                              Help screen
  lint                                Lint terraform code

```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| common_tags | This is a map type for applying tags on resources | map | - | yes |

## Outputs

| Name | Description |
|------|-------------|
| bucket_domain_name | The FQDN for the bucket |

## Related Projects

Check out these related projects.

- [terraform-aws-s3](https://github.com/jameswoolfenden/terraform-aws-s3) - S3 buckets

## Help

**Got a question?**

File a GitHub [issue](https://github.com/jameswoolfenden/terraform-aws-statebucket/issues).

## Terraform Module Development

## Slack Community

Join their [Open Source Community][slack] on Slack.

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/jameswoolfenden/terraform-aws-statebucket/issues) to report any bugs or file feature requests.

## Copyrights

Copyright © 2019-2019 [Slalom, LLC](https://slalom.com)

## License

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

See [LICENSE](LICENSE) for full details.

    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

      https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

### Contributors

|  [![James Woolfenden][jameswoolfenden_avatar]][jameswoolfenden_homepage]<br/>[James Woolfenden][jameswoolfenden_homepage] |
|---|

  [jameswoolfenden_homepage]: https://github.com/jameswoolfenden
  [jameswoolfenden_avatar]: https://github.com/jameswoolfenden.png?size=150

[![README Footer][readme_footer_img]][readme_footer_link]
[![Beacon][beacon]][website]

  [logo]: https://slalom.com/sites/all/themes/slalom_bootstrap/images/slalom-logo-white@2x.png
  [website]: https://slalom.com
  [github]: https://github.com/jameswoolfenden
  [slack]: https://cpco.io/slack
  [linkedin]: https://www.linkedin.com/company/slalom-consulting/
  [twitter]: https://twitter.com/Slalom
  [readme_header_img]: https://cloudposse.com/readme/header/img?repo=jameswoolfenden/terraform-aws-statebucket
  [readme_header_link]: https://cloudposse.com/readme/header/link?repo=jameswoolfenden/terraform-aws-statebucket
  [readme_footer_img]: https://cloudposse.com/readme/footer/img?repo=jameswoolfenden/terraform-aws-statebucket
  [readme_footer_link]: https://cloudposse.com/readme/footer/link?repo=jameswoolfenden/terraform-aws-statebucket
  [share_twitter]: https://twitter.com/intent/tweet/?text=terraform-aws-s3&url=https://github.com/jameswoolfenden/terraform-aws-statebucket
  [share_linkedin]: https://www.linkedin.com/shareArticle?mini=true&title=terraform-aws-s3&url=https://github.com/jameswoolfenden/terraform-aws-statebucket
  [share_reddit]: https://reddit.com/submit/?url=https://github.com/jameswoolfenden/terraform-aws-statebucket
  [share_facebook]: https://facebook.com/sharer/sharer.php?u=https://github.com/jameswoolfenden/terraform-aws-statebucket
  [share_googleplus]: https://plus.google.com/share?url=https://github.com/jameswoolfenden/terraform-aws-statebucket
  [share_email]: mailto:?subject=terraform-aws-s3&body=https://github.com/jameswoolfenden/terraform-aws-statebucket
  [beacon]: https://ga-beacon.cloudposse.com/UA-76589703-4/jameswoolfenden/terraform-aws-statebucket?pixel&cs=github&cm=readme&an=terraform-aws-statebucket
