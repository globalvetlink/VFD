# VFD
XML and JSON standard for electronic VFDs
This repository serves as standards collaboration platform for standarized electronic VFDs.


# Fields
21 CFR 558.6(b)(3) requires the following information to be fully and accurately included on the
VFD order:
Required fields denoted with *



## Veterinarian
* The following fields are enclosed in the **veterinarian** object

#### Name*
* Field Name: **name**
* Field Type: String

#### Address*
* Field Name: **address**
* Field Type: String

#### Apt
* Field Name: **apt**
* Field Type: String

#### City*
* Field Name: **city**
* Field Type: String

#### State*
* Field Name: **state**
* Field Type: String

#### Postal Code*
* Field Name: **postalCode**
* Field Type: String

#### County
* Field Name: **county**
* Field Type: String

#### Email
* Field Name: **email**
* Field Type: String

#### Phone*
* Field Name: **phone**
* Field Type: String

#### Fax
* Field Name: **fax**
* Field Type: String

#### Signature Date*
* Field Name: **signatureDate**
* Field Type: String
* ISO-8061 Complient Time Stamp

#### Signature Image*
* Field Name: **signatureImage**
* Field Type: String
* Base64 Encoded Image

#### Signature Image Type*
* Field Name: **signatureImageType**
* Field Type: String
* Type prefix for Base64 Encoded Image

******
## Feed Mill / Pharmacy
* The following fields are enclosed in the **feedMill** object

#### Name*
* Field Name: **name**
* Field Type: String

#### Address*
* Field Name: **address**
* Field Type: String

#### Apt
* Field Name: **apt**
* Field Type: String

#### City*
* Field Name: **city**
* Field Type: String

#### State*
* Field Name: **state**
* Field Type: String

#### Postal Code*
* Field Name: **postalCode**
* Field Type: String

#### County
* Field Name: **county**
* Field Type: String

#### Email
* Field Name: **email**
* Field Type: String

#### Phone
* Field Name: **phone**
* Field Type: String

#### Fax
* Field Name: **fax**
* Field Type: String


******
## Client
* The following fields are enclosed in the **client** object

#### Name*
* Field Name: **name**
* Field Type: String

#### Address*
* Field Name: **address**
* Field Type: String

#### Apt
* Field Name: **apt**
* Field Type: String

#### City*
* Field Name: **city**
* Field Type: String

#### State*
* Field Name: **state**
* Field Type: String

#### Postal Code*
* Field Name: **postalCode**
* Field Type: String

#### County
* Field Name: **county**
* Field Type: String

#### Email
* Field Name: **email**
* Field Type: String

#### Phone*
* Field Name: **phone**
* Field Type: String

#### Fax
* Field Name: **fax**
* Field Type: String

******
## Premises
* The following fields are enclosed in the **premise** array of objects
* Note: multiple premises can be specified.

#### Name
* Field Name: **name**
* Field Type: String

#### ID
* Field Name: **ID**
* Field Type: String
* National Premise ID

#### Address
* Field Name: **address**
* Field Type: String

#### Apt
* Field Name: **apt**
* Field Type: String

#### City
* Field Name: **city**
* Field Type: String

#### State
* Field Name: **state**
* Field Type: String

#### Postal Code
* Field Name: **postalCode**
* Field Type: String

#### County
* Field Name: **county**
* Field Type: String

#### Email
* Field Name: **email**
* Field Type: String

#### Phone
* Field Name: **phone**
* Field Type: String

#### Fax
* Field Name: **fax**
* Field Type: String

#### Description
* Field Name: **description**
* Field Type: String
* A more specific description of the location of the animals (for example, by site, pen,
barn, stall, tank, or other descriptor the veterinarian deems appropriate)



******
## Drugs
* The following fields are enclosed in the **drugs** array of objects
* Note: multiple drugs can be specified.

#### Drug
* Field Name: **drug**
* Field Type: String
* The Name of the drug

#### Drug Level
* Field Name: **drugLevel**
* Field Type: String
* the level of VFD drug in the feed and duration of use

#### Indication*
* Field Name: **indication**
* Field Type: String
* The indication for which the VFD is issued


#### Instructions*
* Field Name: **instructions**
* Field Type: String
* The withdrawal time, special instructions, and cautionary statements necessary for use of the drug in conformance with the approval



******
## VFD Information
#### Issuance Date*
* Field Name: **issuanceDate**
* ISO-8061 Complient Time Stamp
* Field Type: String
* Date the VFD was issued

#### Expiration Date*
* Field Name: **expirationDate**
* ISO-8061 Complient Time Stamp
* Field Type: String
* Date the VFD expires (must be within 6 months of Issuance Date)

#### Species*
* Field Name: **species**
* Field Type: String
* The species and production class of animals to be fed the VFD feed

#### Approximate Number of Animals*
* Field Name: **animalCount**
* Field Type: Number
* The approximate number of animals to be fed the VFD feed by the expiration date of the VFD

#### Approximate Age Range
* Field Name: **ageRange**
* Field Type: String
* The approximate age range of the animals

#### Approximate Weight Range (lbs)
* Field Name: **weightRangeLbs**
* Field Type: String
* The approximate weight range of the animals

#### Reorders*
* Field Name: **reorders**
* Field Type: Number
* The number of reorders (refills) authorized, if permitted by the drug approval, conditional approval, or index listing

#### Statement*
* Field Name: **statement**
* Field Type: String
* Static String
* The statement: “Use of feed containing this veterinary feed directive (VFD) drug in a manner other than as directed on the labeling (extralabel use), is not permitted”

#### Notes
* Field Name: **notes**
* Field Type: String
* Any other information the veterinarian deems appropriate to identify the animals at issue.



******
# Contributions
If you would like to propose changes to the standard, please do so via a GitHub Pull Request.

******
# Comments and Issues
If you have comments or suggestions for the standard, you should use the 'issues' feature of github.com -- you can access it here:
https://github.com/AnimalHealthInstitute/VFD/issues
