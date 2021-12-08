# README

Members of the [OASIS Open Command and Control (OpenC2) TC](https://www.oasis-open.org/committees/openc2/) create and manage technical content in this TC GitHub repository (https://github.com/oasis-tcs/openc2-transf-http/) as part of the TC's chartered work (the program of work and deliverables described in its [charter](https://www.oasis-open.org/committees/openc2/charter.php).

OASIS TC GitHub repositories, as described in [GitHub Repositories for OASIS TC Members' Chartered Work](https://www.oasis-open.org/resources/tcadmin/github-repositories-for-oasis-tc-members-chartered-work), are governed by the OASIS [TC Process](https://www.oasis-open.org/policies-guidelines/tc-process), [IPR Policy](https://www.oasis-open.org/policies-guidelines/ipr), and other policies. While they make use of public GitHub repositories, these repositories are distinct from [OASIS Open Repositories](https://www.oasis-open.org/resources/open-repositories), which are used for development of open source [licensed](https://www.oasis-open.org/resources/open-repositories/licenses) content.

# >>> Work Product Suspended <<<

**Summary:** The OpenC2 TC has suspended work on this transfer specification, as its purpose has been accomplished with the approval of v1.1 of the _[HTTPS Transfer Specification](https://docs.oasis-open.org/openc2/open-impl-https/v1.1/cs01/open-impl-https-v1.1-cs01.html)_ as an OASIS Committee Specification.  This repository is therefore being archived.

**Details:**  The _HTTPS Transfer Spec, v1.0_ is one of the TC's initial trio of specifications, and only addressed the use of HTTP over TLS (i.e., secure communications). The use of TLS depends on having compatible certificates and certificate chains at the endpoints of the TLS connection, which often presents a challenge in a testing environment such as a plugfest.  After having TLS issues at a plugfest in January 2020, the TC initiated this _HTTP Transfer Spec_ to address non-secure testing situations. However, this specification was never actively developed.  The v1.1 update to the HTTPS Transfer Specification addresses both the secure and non-secure use of HTTP through conformance targets, negating the need for an independent _HTTP Transfer Specification_, and the TC agreed at its November 2021 meeting to officially suspend this work product.


## Description

This GitHub repository supports development of and change tracking for the OpenC2 HTTP Transfer Specification.

This repository is designed to support TC members' work on a formal specification that describes the use of HTTP as a transfer mechanism for OpenC2 messages. The provisional work product title is "Specification for Transfer of OpenC2 Messages via HTTP", edited by David Lemire (G2) and Duncan Sparrell (sFractal Consulting). The specification explains the transfer of OpenC2 command and response messages using HTTP. The authoritative format for the specification is Markdown. 

The new specification will be developed using the existing HTTPS Transfer Specification, v1.0, CS01, as a starting point. The intent is to apply lessons learned from the January 2020 Plug Fest / Hackathon in the development of the new specification.

## Contributions

As stated in this repository's [CONTRIBUTING](https://github.com/oasis-tcs/openc2-transf-http/blob/master/CONTRIBUTING.md) file, contributors to this repository must be Members of the OASIS OpenC2 TC for any substantive contributions or change requests.  Anyone wishing to contribute to this GitHub project and [participate](https://www.oasis-open.org/join/participation-instructions) in the TC's technical activity is invited to join as an OASIS TC Member. Public feedback is also accepted, subject to the terms of the [OASIS Feedback License](https://www.oasis-open.org/policies-guidelines/ipr#appendixa). 

## Licensing

Please see the [LICENSE](https://github.com/oasis-tcs/openc2-transf-http/blob/master/LICENSE.md) file for description of the license terms and OASIS policies applicable to the TC's work in this GitHub project. Content in this repository is intended to be part of the OpenC2 TC's permanent record of activity, visible and freely available for all to use, subject to applicable OASIS policies, as presented in the repository [LICENSE](https://github.com/oasis-tcs/openc2-transf-http/blob/master/LICENSE.md). 

## Further Description of this Repository

*Any narrative content may be provided here by the TC, for example, if the Members wish to provide an extended statement of purpose.*

## Contact

Please send questions or comments about [OASIS TC GitHub repositories](https://www.oasis-open.org/resources/tcadmin/github-repositories-for-oasis-tc-members-chartered-work) to the [OASIS TC Administrator](mailto:tc-admin@oasis-open.org).  For questions about content in this repository, please contact the TC Chair or Co-Chairs as listed on the the OpenC2 TC's [home page](https://www.oasis-open.org/committees/openc2/).
