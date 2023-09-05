# diagrams.net AWS Architecture Icons

AWS Architecture Icons version:
[2023-04-28](https://d1.awsstatic.com/webteam/architecture-icons/q2-2023/Asset-Package_04282023.ca9655a386a46bda0b6238cca2651e8f27fcb5c9.zip)


## What is it?

Shapes library with [AWS Architecture Icons](https://aws.amazon.com/architecture/icons/)
for [diagrams.net](https://diagrams.net/)
([formerly draw.io](https://www.diagrams.net/blog/move-diagrams-net)) application.

The library can be loaded into diagrams.net by downloading particular `xml` files
and [loading them into application](https://www.diagrams.net/blog/custom-libraries)
or using links provided below.

## How it's different from the built-in AWS shapes library?

- more up-to-date
- shapes have connection points
- shapes size is 50x50 px instead of 78x78 px
  (I found it much more suitable personally)
- version with a single library with all the icons

## Library links

- [click to add to diagrams.net](https://app.diagrams.net/?splash=0&clibs=Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-App%20Integration.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Business%20Applications.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Front%20End%20Web%20Mobile.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Management%20Governance.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Blockchain.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-IoT.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Games.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Migration%20Transfer.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Storage.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Developer%20Tools.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Containers.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Serverless.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Robotics.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Security%20Identity%20Compliance.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Database.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-General%20Icons.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Cloud%20Financial%20Management.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Customer%20Enablement.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Application%20Integration.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Internet%20of%20Things.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Satellite.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Analytics.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Quantum%20Technologies.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Networking%20Content%20Delivery.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-End%20User%20Computing.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Media%20Services.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Machine%20Learning.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Compute.xml;Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230428/AWS-Contact%20Center.xml)
  (may take few seconds to load)

## Previous versions

- [2023-01-31](https://app.diagrams.net/?splash=0&clibs=Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20230131/AWS%20Architecture%20Icons%2020230131.xml)
- [2022-07-31](https://app.diagrams.net/?splash=0&clibs=Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20220731/AWS%20Architecture%20Icons%2020220731.xml)
- [2022-04-30](https://app.diagrams.net/?splash=0&clibs=Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20220430/AWS%20Architecture%20Icons%2020220430.xml)
- [2021-09-17](https://app.diagrams.net/?splash=0&clibs=Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20210917/AWS%20Architecture%20Icons%2020210917.xml)
- [2020-09-11](https://app.diagrams.net/?splash=0&clibs=Uhttps://raw.githubusercontent.com/m-radzikowski/diagrams-aws-icons/master/20200911/AWS%20Architecture%20Icons.xml)

## Generating library

Icons library is generated using [icons-asset-generator](https://github.com/m-radzikowski/icons-asset-generator):

```bash
poetry run icons-asset-generator \
    --filename-includes _48 \
    --filename-excludes Dark \
    --image-name-remove Light Arch_ Res_ _48 . - _  \
    --library-name-remove  . - _ \
    --path "./Asset-Package_04302022/" \
    diagrams.net \
    --size height=50
```

## Copyright

All right to the icons belong to Amazon Web Services.
