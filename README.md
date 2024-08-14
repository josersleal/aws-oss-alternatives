# Open Source Alternatives to AWS Services

Groups covered: Storage, Database, Analytics, Compute

AWS Service             | What it does              | OSS Alternatives
------------------------|---------------------------|-----------------
S3                      | Object store              | [Minio](https://min.io/), [Swift](https://launchpad.net/swift), [Ceph](https://ceph.io/), ...
EFS                     | File system
FSx                     | File system               | [Lustre](http://lustre.org/)
S3 Glacier              | Archive storage
Storage Gateway         | Hybrid storage            |
AWS Backup              | Backup for AWS services   | n/a
RDS                     | Relational database       | [MariaDB](https://mariadb.org/), [MySQL](https://www.mysql.com/), [Postgres](https://www.postgresql.org/)
DynamoDB                | NoSQL database            | [Apache Cassandra](https://cassandra.apache.org/)
ElastiCache             | In-memory cache           | [Memcached](https://www.memcached.org/), [Redis](https://redis.io/)
Neptune                 | Graph database            | [Neo4j](https://neo4j.com/)
Amazon Redshift         | Data warehousing          | [Spark SQL](https://spark.apache.org/sql/), [Apache Hive](https://hive.apache.org/), [Presto](https://prestodb.github.io/)
Amazon QLDB             | Ledger database           | [[imudb](https://immudb.io/)
Amazon DocumentDB       | Document database         | [MongoDB](https://www.mongodb.com/)
Athena                  | Data warehousing          | [Spark SQL](https://spark.apache.org/sql/), [Apache Hive](https://hive.apache.org/), [Presto](https://prestodb.github.io/)
EMR                     | Hadoop / Spark            | [Apache Spark](https://spark.apache.org/)
CloudSearch             | Search                    | [Elasticsearch](https://www.elastic.co/products/elasticsearch)
Elasticsearch Service   | Elasticsearch             | [Elasticsearch](https://www.elastic.co/products/elasticsearch)
Kinesis                 | Data streaming            | [Apache Kafka](https://kafka.apache.org/)
QuickSight              | Business analytics
Data Pipeline           | ETL                       | [Apache Airflow](https://airflow.apache.org/)
AWS Glue                | ETL                       | [Apache Airflow](https://airflow.apache.org/)
AWS Lake Formation      | Data lake                 | [HDFS](http://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html)
MSK                     | Data streaming            | [Apache Kafka](https://kafka.apache.org/)
EC2                     | Virtual machines
EC2 EBS                 | Block storage for EC2     | [OpenEBS](https://www.openebs.io/), [Portworx](https://github.com/portworx/px-dev)
Lightsail               | Virtual machines
ECR                     | Container registry        | [Docker Registry](https://github.com/docker/distribution), [Quay](https://quay.io/)
ECS                     | Container orchestration   | [Kubernetes](https://kubernetes.io/), [Marathon](https://mesosphere.github.io/marathon/)
EKS                     | Container orchestration   | [Kubernetes](https://kubernetes.io/)
Lambda                  | Serverless                | [Knative](https://knative.dev/), [OpenFaaS](https://www.openfaas.com/), [Fn](https://fnproject.io/)
Batch                   | Job queue                 | [Apache Airflow](https://airflow.apache.org/)
Elastic Beanstalk       | App deployment
Serverless App. Repo.   | Serverless repository


# Awesome AWS alternatives/replacements [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome AWS alternatives: open source repos, libraries, tools, frameworks, software. 

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

**Contribute?** Check [AWS in Plain English](https://www.expeditedssl.com/aws-in-plain-english) for better section name.

## Run an App Services

### EC2 - Amazon Virtual Servers

* [Hetzner](https://hetzner.de) - Dedicated and Virtual servers. Well-known company for providing dedicated and virtual services.
* [DigitalOcean](https://digitalocean.com) - Virtual Servers, Block storage, Load balancing and Firewalls. Another well-known company that provides dedicated and virtual servers.
* [Contabo](https://contabo.com) - Servers and VPS (found [here](http://www.yegor256.com/2017/07/25/my-favorite-websites.html)).
* [ArubaCloud](https://www.arubacloud.com/vps/virtual-private-server-range.aspx) - VPS: 1 euro/month for 1GB RAM, 20GB storage, 2TB data transfer.

### S3 - Unlimited Storage

* [Backblaze B2 storage](https://www.backblaze.com/b2/cloud-storage.html) - inexpensive cloud storage, they claim to will cost you ¼ the Price.
* [Scalable Object Storage on DigitalOcean](https://blog.digitalocean.com/introducing-spaces-object-storage/) - object storage from DigitalOcean with [AWS S3 compatibility](https://developers.digitalocean.com/documentation/spaces/#introduction).

## Web Developer Services

### CodeDeploy - Deployment and testing

* [CodeShip](https://codeship.com) - Automated unit testing and deployment.

### Route53 - DNS and Domains

* [Moniker](https://www.moniker.com/) - Domain Management & Domain Services.


### SES Simple Email Service 

* [Mailgun](https://www.mailgun.com/) - E-mail relay and delivery/open tracking.
* [Postmark](https://postmarkapp.com/) - E-mail relay and delivery/open tracking.
* [SendGrid](https://sendgrid.com/) - E-mail delivery/open tracking.


## Enterprise / Corporate Services

### WorkMail

* [Yandex.Connect](https://connect.yandex.com) - E-mail and online storage for your domain.
* [Zoho Mail](https://www.zoho.com/mail/) - Webmail for your domain, free up to 25 users.

## AWS Management Services

### CloudWatch - statistics storage

* [Graphite](https://graphiteapp.org) - Used in Uber and [Etsy](http://codeascraft.etsy.com/2011/02/15/measure-anything-measure-everything/).

## Search Engines

* [PaaSfinder](https://paasfinder.org/) - Allows for selecting a PaaS service provider based on requirements.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Roman Pushkin](https://github.com/ro31337) has waived all copyright and related or neighboring rights to this work.
