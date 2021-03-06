# Notifying tenants

Every now and then, we need to let our tenants know that something has happened or will happen on the platform. For example, letting teams know about security fixes, CF/stemcell/buildpack upgrades, new features and incidents.

Depending on what it is we want to tell users, we have two different channels for sending these notifications:

* incident alerts and reports are sent using [our Statuspage account](https://manage.statuspage.io/pages/h4wt7brwsqr0)
* changes, fixes and upgrades are sent using the [GOV.UK PaaS Announce Google group](https://groups.google.com/a/digital.cabinet-office.gov.uk/forum/?hl=en#!forum/gov-uk-paas-announce)
* new feature announcements are sent using the [GOV.UK PaaS Announce Google group](https://groups.google.com/a/digital.cabinet-office.gov.uk/forum/?hl=en#!forum/gov-uk-paas-announce)

## Sending incident alerts and updates

Follow the guidance in [this section](../support/incident_process/#if-youre-incident-comms) of the team manual if you're managing incident comms and you need to send alerts and updates to tenants.

## Sending platform change and new feature announcements

### Changes, upgrades and fixes

Write a draft email and share it [here.](https://drive.google.com/drive/folders/0Bw4pWpR0IbJfWGFEMVBBZlFsSDQ)

Get Tom or Jess to proof-read and add any 'product-y' elements - we want to make sure our notifications are consistent and meet the GDS style guidelines. If the email is time-sensitive and Tom/Jess are not around, get another member of the team to proof-read the email before it's sent.

### Announcing new features

These announcements are our chance to showcase how we're developing GOV.UK PaaS and will be written and sent by the product managers. Tom/Jess may ask the team member who worked on the story to provide some technical details that can be inclued in the email. 


## Sending notification emails to tenants

Use the [google group interface](https://groups.google.com/a/digital.cabinet-office.gov.uk/forum/?hl=en#!forum/gov-uk-paas-announce) to send the email.

* Click on `New topic`
* In `By` select: Post on behalf of GOV.UK PaaS announce
* The `Subject` should help identify immediately the purpose of the email.
Ex: "Incident with..."
* In `Type of post` select: "Make an announcement" to emphasize this is
one way communication
* Body: paste the content of the reviewed draft. You may have to adjust formatting.


### CF upgrade email template

Subject (ex): GOV.UK PaaS - Cloud Foundry changes - 17th March 2017

The body should contain:

 - Changes and bugfixes to highlight and new features enabled.
 - Downtime or service impact if any
 - Summary of buildpack changes.

**NB Incident comms email templates are saved in Statuspage.**
