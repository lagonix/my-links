- 98% OSS
- 1% free-as-in-beer closed source software
- 1% in-browser tools
- Please don't submit to Reddit, HN, or post this on Twitter. Share, but share with close friends!

---

# Table of Contents

- [Tools by Category](#tools-by-category)

- [IT News](#it-news)

- [Learning Resources](#learning-resources)

- [Notes from the book Software Engineering at Google: Lessons Learned from Programming Over Time](https://www.seagnotes.com)

- [Josh's Website](https://www.joshturgasen.com)

- [Josh's Tech Blog v2](https://jturgasen.github.io)

---

# Tools by Category

- [X](#asset-management) Asset Management
- [X](#aws-and-azure-tools) AWS and Azure Tools
- [X](#backups) Backups
- [X](#cloud-file-sync-and-sharing) Cloud File Sync and Sharing
- [X](#collaboration-tools) Collaboration Tools
- [X](#containers) Containers
- [X](#data-visualization-and-dashboards) Data Visualization and Dashboards
- [X](#distributed-systems-tools) Distributed Systems Tools
- [X](#editors) Editors
- [X](#git-tools) Git Tools
- [X](#graphics-stuff) Graphics Stuff
- [X](#high-availability-clustering-tools) High Availability Clustering Tools
- [X](#hpc-tools) HPC Tools
- [X](#infrastructure-as-code-tools) Infrastructure as Code Tools
- [X](#kubernetes) Kubernetes
- [X](#live-cd-tools) Live CD Tools
- [X](#logging) Logging
- [X](#metrics-and-time-series-data) Metrics and Time Series Data
- [X](#monitoring-and-alerting) Monitoring and Alerting
- [X](#networking-tools) Networking Tools
- [X](#network-performance-analysis-tools) Network Performance Analysis Tools
- [X](#orchestration) Orchestration
- [X](#package-patch-and-repository-tools) Package Patch and Repository Tools
- [X](#performance-analysis-tools) Performance Analysis Tools
- [X](#provisioning-tools) Provisioning Tools
- [X](#python-tools-and-resources) Python Tools and Resources
- [X](#python-programming-tutorials) Python Programming Tutorials
- [X](#rdbms-and-sql-tools) RDBMS and SQL Tools
- [X](#rdbms-performance-analysis-tools) RDBMS Performance Analysis Tools
- [X](#regular-expressions) Regular Expressions
- [X](#secrets-management) Secrets Management
- [X](#security-tools) Security Tools
- [X](#shell-scripting-and-tools) Shell Scripting and Tools
- [X](#software-development-tools) Software Development Tools
- [X](#ssh-tools) SSH Tools
- [X](#ssl-tools) SSL Tools
- [X](#storage-tools) Storage Tools
- [X](#storage-performance-analysis-tools) Storage Performance Analysis Tools
- [X](#terminal-tools-and-ssh-clients) Terminal Tools and SSH Clients
- [X](#tracing-and-profiling) Tracing and Profiling
- [X](#two-factor-authentication) Two Factor Authentication
- [X](#virtualization-and-sdn) Virtualization and SDN
- [X](#vmware-tools) VMware Tools
- [X](#vpns-and-tunnels) VPNs and Tunnels
- [X](#web-and-http-tools) Web and HTTP Tools
- [X](#web-and-http-performance-analysis-tools) Web and HTTP Performance Analysis Tools
- [X](#misc-tools-of-note) Misc Tools of Note
- [X](#learning-resources) Learning Resources

---

# IT News

> A mix of industry and technical, traditional and next generation, dev and ops

- [Ars Technica](https://arstechnica.com/)
- [AWS News Blog](https://aws.amazon.com/blogs/aws/)
- [CIO.com](https://www.cio.com/)
- [Computerworld](https://www.computerworld.com/)
- [Dark Reading](https://www.darkreading.com)
- [Data Center Knowledge](https://www.datacenterknowledge.com/)
- [DZone](https://www.dzone.com/)
- [Engineering Blogs](https://github.com/kilimchoi/engineering-blogs)
- [eWeek](https://www.eweek.com/)
- [Google Cloud Blog](https://cloud.google.com/blog/)
- [High Scalability](http://highscalability.com/)
- [InfoQ](https://www.infoq.com/)
- [Infosec Industry](https://infosecindustry.com/news/)
- [Kubernetes Blog](https://kubernetes.io/blog/)
- [Light Reading](https://www.lightreading.com/)
- [Microsoft Azure Blog](https://azure.microsoft.com/en-us/blog/)
- [Network Computing](https://www.networkcomputing.com/)
- [Network World](https://www.networkworld.com)
- [Packet Storm](https://packetstormsecurity.com/news/)
- [Re/Code](https://recode.net/)
- [SD Times](https://sdtimes.com/)
- [TechCrunch](https://techcrunch.com/)
- [The New Stack](https://thenewstack.io/)
- [The Next Web](https://thenextweb.com/)
- [The Next Platform](https://www.nextplatform.com/)
- [The Register](https://www.theregister.co.uk/)
- [Webshit Weekly](http://www.n-gate.com/)

---

## Asset Management

> Asset management, inventories, asset discovery, CMDB, and IPAM - see also [Infrastructure as Code Tools](#infrastructure-as-code-tools)

- [Collins](https://tumblr.github.io/collins/) - Infrastructure source of truth, created by Tumblr -- `Scala`
- [iTop](https://www.combodo.com/itop-193) - IT Service Management (ITSM), asset tracking, and ITIL -- `PHP`
- [Fusion Inventory](http://www.fusioninventory.org/) - Multi-lingual, can be paired with GLPI for a killer solution -- `perl`
- [Genesis](https://github.com/tumblr/genesis) - Hardware discovery, by Tumblr, can report to Collins -- `Ruby`
- [GestioIP](https://www.gestioip.net/) - IP address management (IPAM), web based, supports discovery -- `perl`
- [GLPI](https://glpi-project.org/) - Also provides license management, software auditing, and ticketing -- `PHP`
- [ITDB (IT ITems DataBase)](http://www.sivann.gr/software/itdb/) - Includes purchase order management, floor plans, and ISO20000-like features -- `PHP`
- [NetBox](https://github.com/digitalocean/netbox) - IPAM and DCIM by Digital Ocean -- `Python`
- [Netdisco](https://metacpan.org/pod/App::Netdisco) - Web-based network management and discovery tool, written in perl, uses SNMP -- `perl`
- [NIPAP](https://spritelink.github.io/NIPAP/) - Next-generation IPAM -- `Python`
- [OCS-NG (OCS Inventory NG)](https://ocsinventory-ng.org/?lang=en) - Automated inventory, deployment system, can sync with GLPI -- `perl`
- [openDCIM](https://opendcim.org/) - Data center infrastructure management -- `PHP`
- [Open-AudIT](https://open-audit.org/) - Track and report assets and configurations, supports Windows too -- `PHP`
- [phpIPAM](https://phpipam.net/) - IPAM -- `PHP`
- [RackTables](https://github.com/RackTables/racktables) - Data center asset management, being updated again! -- `PHP`
- [racktables-contribs](https://github.com/RackTables/racktables-contribs/) - RackTables user-contributed plugins -- `PHP`
- [Ralph](https://ralph.allegro.tech/) - DCIM and CMDB, supports auto-discovery -- `Python pip`
- [Snipe-IT](https://snipeitapp.com/) - Uses Bootstrap, web based, supports mobile -- `PHP`

---

## AWS and Azure Tools

> And some GCP / Google Cloud

- [Action Hero](https://github.com/princespaghetti/actionhero) - Uses an AWS SDK feature known as Client Side Monitoring to help you create least privilege IAM Policies for AWS -- `Golang`
- [asecurecloud](https://asecure.cloud/) - A free library of 400+ customizable AWS security configurations and best practices (CF, Terraform, and AWS CLI) -- `collection`
- [AutoSpotting](https://github.com/AutoSpotting/AutoSpotting) - A tool implementing an automated bidding algorithm against the Amazon AWS EC2 spot market -- `Golang`
- [awacs (Amazon Web Access Control Subsystem)](https://github.com/cloudtools/awacs) - Allows for easier creation of AWS Access Policy Language JSON by writing Python code to describe the AWS policies -- `Python pip`
- [aws-runas](https://github.com/mmmorris1975/aws-runas) - A friendly way to do AWS STS AssumeRole operations so you can perform AWS API actions using a particular set of permissions -- `Golang`
- [aws-gate](https://github.com/xen0l/aws-gate) - Connect to instances by other means (e.g. DNS, IP, tag, instance name, autoscaling group) -- `Python pip`
- [aws-shell (formerly Supercharged AWS CLI (SAWS))](https://github.com/awslabs/aws-shell) - The best CLI for interacting with AWS -- `Python pip`
- [aws-ssm-tree](https://github.com/brunorubin/aws-ssm-tree) - Provides a tree visualization of the parameters hierarchy from AWS System Manager Parameter Store -- `Python pip`
- [aws-vault](https://github.com/99designs/aws-vault) - A vault for securely storing and accessing AWS credentials in development environments -- `Golang`
- [AWSConsoleRecorder](https://github.com/iann0036/AWSConsoleRecorder) - Records actions made in the AWS Management Console and outputs the equivalent CLI/SDK commands and CloudFormation/Terraform templates -- `Chrome` `JavaScript`
- [awspec](https://github.com/k1LoW/awspec) - rspec for AWS resources -- `Ruby gem`
- [AWSSupport-SetupIPMonitoringFromVPC](https://aws.amazon.com/blogs/networking-and-content-delivery/debugging-tool-for-network-connectivity-from-amazon-vpc/) - SSM Automation document that launches a Monitor Instance in the specified subnet. The Monitor Instance pushes subnet network telemetry data to CloudWatch Logs -- `article`
- [AWS Amplify](https://github.com/aws-amplify) - Front end JS suite that provides a templated foundation for cloud-centric apps including authn, analytics, API, push notifications, Graph QL, and more -- `JavaScript`
- [AWS Copilot](https://aws.github.io/copilot-cli/) - OSS CLI to build, release, and operate apps for ECS and Fargate -- `Golang`
- [AWS Encryption CLI](https://docs.aws.amazon.com/encryption-sdk/latest/developer-guide/crypto-cli.html) - CLI for KMS -- `Python`
- [AWS Extend Switch Roles](https://github.com/tilfin/aws-extend-switch-roles) - Extend your AWS IAM switching roles by Chrome extension or Firefox add-on -- `JavaScript`
- [AWS IAM Authenticator for Kubernetes](https://github.com/kubernetes-sigs/aws-iam-authenticator) - A tool for using AWS IAM credentials to authenticate to a Kubernetes cluster -- `Golang`
- [AWS Lambda Power Tuning](https://github.com/alexcasalboni/aws-lambda-power-tuning) - A state machine powered by AWS Step Functions that helps you optimize your Lambda functions for cost and/or performance in a data-driven way -- `JavaScript`
- [AWS Quick Start](https://github.com/aws-quickstart) - Automated gold-standard deployments on AWS, by AWS -- `various lang`
- [AWS SAM Local](https://github.com/awslabs/aws-sam-local) - CLI tool for local development and testing of Lambda applications -- `Golang`
- [AWS Samples](https://github.com/aws-samples) - Over 2k code samples for all AWS services -- `collection`
- [AWS Secrets Manager and Configuration Provider (ASCP)](https://docs.aws.amazon.com/secretsmanager/latest/userguide/integrating_csi_driver.html) - Plugin for the industry-standard Kubernetes Secrets Store Container Storage Interface (CSI) Driver used for providing secrets to applications operating on EKS -- `Golang`
- [AWS Toolkit for Visual Studio Code](https://aws.amazon.com/visualstudiocode/) - Give it a go -- `various lang`
- [AWS Tools for PowerShell](https://aws.amazon.com/powershell/) - Use an automation language instead of a programming langue -- `various lang`
- [AzCopy](https://github.com/Azure/azure-storage-azcopy) - CLI to copy data to and from containers and file shares in Azure Storage accounts -- `Golang`
- [Azure Portal Desktop App](https://portal.azure.com/App/Download) - Faster than a browser, full Cloud Shell, fast search -- `various lang`
- [Azure Resource Manager (ARM) Tools for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools) - Language support, resource snippets, and resource auto-completion -- `various lang`
- [Azure Resource Manager (ARM) Viewer for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=bencoleman.armview) - Graphical preview of ARM templates -- `various lang`
- [boto3](https://boto3.readthedocs.io/en/latest/) - The AWS SDK for Python 3 -- `Python`
- [boto3_type_annotations](https://github.com/vemel/mypy_boto3_builder) - Adds code completion in IDEs such as PyCharm -- `Python`
- [botostubs](https://github.com/jeshan/botostubs) - boto3 code assistance for any API in any IDE, always up to date -- `Python`
- [Chalice](https://github.com/aws/chalice) - Microframework for writing and testing serverless apps in Python -- `Python`
- [Chamber](https://github.com/segmentio/chamber) - Parameter Store + IAM for secrets including at rest protection, audit trail, and access control policies, by Segment -- `Golang`
- [Chrome AWS SAML Token Expiry Reminder (CASTER)](https://chrome.google.com/webstore/detail/chrome-aws-saml-token-exp/mbfkedefmlagincpblmgeeeehhamgpbn?hl=en-US) - Automatically re-logs into AWS via ADFS before credentials expire -- `Chrome`
- [CloudBerry Explorer](https://www.cloudberrylab.com/explorer/windows/amazon-s3.aspx) - Windows client for accessing AWS S3 buckets -- `closed source` `Windows`
- [CloudCraft](https://cloudcraft.co/) - Create professional AWS architecture diagrams -- `in-browser`
- [CloudFormation Checklist](https://github.com/jeshan/cloudformation-checklist) - A list of all elements you need to have / to test before launching your infra to production -- `collection`
- [CloudFormation Designer](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/working-with-templates-cfn-designer.html) - GUI for creating CloudFormation templates, very slick -- `in-browser`
- [CloudFormation Roadmap](https://github.com/aws-cloudformation/aws-cloudformation-coverage-roadmap) - Official roadmap -- `article`
- [CloudMapper](https://github.com/duo-labs/cloudmapper) - Generates network diagrams of Amazon Web Services (AWS) environments and displays them via your browser, by Duo Security -- `Python`
- [CloudSploit Scans](https://github.com/cloudsploit/scans) - Scan AWS accounts for security risks -- `JavaScript`
- [CloudTracker](https://github.com/duo-labs/cloudtracker) - Find over-privileged IAM users and roles by comparing CloudTrail logs with current IAM policies. -- `Python`
- [ClusterCloner](https://github.com/doitintl/ClusterCloner) - Reads the Kubernetes clusters in one location (optionally filtering by labels) and clones them into another (or just outputs JSON as a dry run), to/from AWS, GCP, and Azure -- `Golang`
- [Complete AWS IAM Reference](https://iam.cloudonaut.io/) - Unofficial but concise -- `collection`
- [credstash](https://github.com/fugue/credstash) - Secrets management using AWS KMS -- `Python pip`
- [Disposible Cloud Environment (DCE)](https://dce.readthedocs.io/en/latest/home.html) - Temporary, limited Amazon Web Services (AWS) accounts. Accounts can be “leased” for a period of time or up to a pre-determined budget amount. When the period of time is reached or the maximum budgeted amount is exceeded, the lease is expired -- `Golang`
- [eb_deploy](https://github.com/ThoughtWorksStudios/eb_deployer) - Elastic Beanstalk blue-green deployment automation -- `Ruby gem`
- [EB CLI](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html) - CLI for Elastic Beanstalk -- `Python`
- [ec2-price-check](https://github.com/Bjorn248/ec2-price-check) - Gives a quick price check for an instance type -- `shell`
- [ec2instances.info](https://instances.vantage.sh/) - Open source and up to date instance price comparison tool -- `Python`
- [ec2.shop](https://ec2.shop/) - ec2 price checker, supports curl -- `various lang`
- [eksctl](https://eksctl.io/) - CLI tool for creating and managing clusters on AWS EKS -- `Golang`
- [EKS Boilerplate](https://github.com/maddevsio/aws-eks-base) - IaC boilerplate in mostly Terraform -- `various lang`
- [EKS Distro](https://distro.eks.amazonaws.com/) - Use me for multi-cloud EKS -- `various lang`
- [Fargate](https://github.com/jpignata/fargate) - CLI for AWS Fargate, unofficial -- `Golang`
- [Force MFA](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_users-self-manage-mfa-and-creds.html) - Allows users to manage their own passwords and MFA devices but nothing else unless they authenticate with MFA, also makes API calls require MFA -- `policy`
- [Former2](https://github.com/iann0036/former2) - Generate CloudFormation / Terraform / Troposphere templates from your existing AWS resources via self-hosted web GUI -- `JavaScript`
- [gcpviz](https://github.com/GoogleCloudPlatform/professional-services/tree/master/tools/gcpviz) - Visualization tool that takes input from Cloud Asset Inventory -- `Golang`
- [GKE Autopilot](https://cloud.google.com/kubernetes-engine/docs/concepts/autopilot-overview) - Think an opinionated version of GKE, somewhat similar to AWS Fargate -- `neat`
- [Google Cloud Samples](https://cloud.google.com/docs/samples) - Searchable by language and product -- `collection`
- [haproxy-autoscale](https://github.com/markcaudill/haproxy-autoscale) - Wrapper for haproxy that handles auto-scaling EC2 instances -- `Python`
- [iamlive](https://github.com/iann0036/iamlive) - Generate a basic IAM policy from AWS client-side monitoring (CSM) -- `Golang`
- [IAM Policy Simulator](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_testing-policies.html) - Built-in tool where you can test and troubleshoot identity-based policies, IAM permissions boundaries, Organizations service control policies (SCPs), and resource-based policies -- `in-browser`
- [kappa](https://github.com/garnaat/kappa) - CLI tool that makes it easier to deploy, update, and test Lambda functions -- `Python`
- [kinesis-scaling-tools](https://github.com/awslabs/amazon-kinesis-scaling-utils) - Tools to make Kinesis shards scale like ASGs -- `Java`
- [localstack](https://github.com/localstack/localstack) - A fully functional local AWS cloud stack for offline dev and test -- `Python`
- [Moto](https://github.com/spulec/moto) - Library that allows your Python tests to easily mock out the boto library -- `Python pip`
- [My Arsenal of AWS Security Tools](https://github.com/toniblyx/my-arsenal-of-aws-security-tools) - List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc -- `collection`
- [ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) - AWS supported Open Source cluster management tool to deploy and manage HPC clusters in the AWS cloud -- `Python`
- [Prowler](https://github.com/toniblyx/prowler) - For AWS account security assessment and hardening, based on aws-cli commands -- `shell`
- [refunc](https://github.com/refunc/refunc) - Run AWS Lambda on Kubernetes, a Lambda-compatable API -- `Golang`
- [s3cmd](https://s3tools.org/s3cmd) - Backup to AWS via the command line -- `Python`
- [s4cmd](https://github.com/bloomreach/s4cmd) - s3cmd with additional features -- `Python`
- [Serverless (formerly JAWS)](https://github.com/jaws-stack/JAWS) - Javascript + AWS stack, the entire backend is Lambda functions, server-free -- `JavaScript`
- [Serverless by Design](https://github.com/danilop/ServerlessByDesign) - In-browser or self-hosted GUI for making flow charts for serverless apps -- `various lang`
- [Serverless Stack Toolkit (SST)](https://serverless-stack.com/) - extension of AWS CDK that includes a live Lambda dev environment and more -- `JavaScript`
- [Session Manager Plugin for AWS CLI](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html) - Used to start and end sessions that connect you to your managed instances -- `Python`
- [Sneaker](https://github.com/codahale/sneaker) - Store secrets on S3 using Amazon KMS -- `Golang`
- [ssh2ec2](https://pypi.python.org/pypi/ssh2ec2) - SSH into EC2 instances by tag name and/or other metadata filters -- `Python pip`
- [SSM Helpers](https://github.com/disneystreaming/ssm-helpers) - Interactive shell with an instance via AWS Systems Manager Session Manager and more -- `Golang`
- [StackMaster](https://github.com/envato/stack_master) - Provides a ton of info pre-CloudFormation run so that you know exactly what will change -- `Ruby gem`
- [StarCluster](http://star.mit.edu/cluster/) - Toolkit for using AWS for high performance computing (HPC), by MIT -- `Python`
- [Steampipe](https://github.com/turbot/steampipe) - Query cloud resources using a SQL syntax -- `Golang`
- [Stout](https://github.com/cloudflare/Stout) - Easy way to reliably upload a static website to S3, capable of configuring CloudFront and Route 53 -- `Golang`
- [taskcat](https://github.com/aws-quickstart/taskcat) - Tool that tests AWS CloudFormation templates. It deploys your AWS CloudFormation template in multiple AWS Regions and generates a report with a pass/fail grade for each region, by AWS -- `Python`
- [Terraformer](https://github.com/GoogleCloudPlatform/terraformer) - Generate Terraform files from existing infrastructure (reverse Terraform), supports AWS and GCP, by Google -- `Golang`
- [Terraforming](https://terraforming.dtan4.net/) - Export all AWS resources into Terraform -- `Ruby gem`
- [Terragrunt Reference Architecture (AWS)](https://github.com/antonbabenko/terragrunt-reference-architecture) - Nice, looking forward to their GCP one -- `various lang`
- [Tools for Amazon Web Services](https://aws.amazon.com/tools/) - Amazon's portal for their official tools -- `various lang`
- [troposphere](https://github.com/cloudtools/troposphere) - Python library to create CloudFormation descriptions -- `Python pip`
- [Zappa](https://github.com/Miserlou/Zappa) - Build and deploy serverless, event-driven Python applications -- `Python`

---

## Backups

> Traditional backup software - see also [Cloud File Sync and Sharing](#cloud-file-sync-and-sharing)

- [Amanda](http://www.amanda.org/) - The classic -- `C` `perl`
- [Backupninja](https://0xacab.org/riseuplabs/backupninja) - Centralize way to configure and schedule many different backup utilities -- `shell`
- [BURP (BackUp and Restore Program)](https://burp.grke.org/) - Reduces network traffic and the amount of space required by using librsync -- `C`
- [BackupPC](http://backuppc.sourceforge.net/) - Dedupe and a web GUI for restores -- `perl`
- [Backup](https://github.com/backup/backup) - Gem for backup and restore, supports tons of platforms and notifiers (RDBMS, S3, Dropbox, rsync, Hipchat, Zabbix) -- `Ruby gem`
- [Bacula](https://www.bacula.org/) - Open source backup tool, lots of downloads so I guess it's good I don't know -- `C`
- [Back in Time](https://github.com/bit-team/backintime) - Similar to TimeMachine, simple GUI backup program -- `Python`
- [Bareos (Backup Archiving REcovery Open Sourced)](https://www.bareos.org/) - Fork of Bacula with additional features -- `C`
- [borgmatic](https://torsion.org/borgmatic/) - A simple wrapper script for the Borg backup software that creates and prunes backups-- `Python`
- [bup](https://github.com/bup/bup) - Uses the git packfile format, supports global dedupe, can use "par2" redundancy -- `Python`
- [DAR (Disk ARchive)](http://dar.linux.free.fr/) - Better than tar, focuses on disks instead of tapes -- `C++`
- [ddrecover](https://www.gnu.org/software/ddrescue/) - This should be the first data recovery tool you use -- `C`
- [Deja Dup](https://launchpad.net/deja-dup) - GUI for duplicity -- `C`
- [Duplicati](https://github.com/duplicati/duplicati) - Supports encryption and dedupe -- `Mono`
- [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm -- `Python`
- [Elkarbackup](https://elkarbackup.github.io/) - Comes as a ready to use VM, supports Linux and Windows -- `PHP`
- [Fpart](https://sourceforge.net/projects/fpart/) - Packs file systems into "partitions" so you can do multi-threaded or multi-node rsyncs -- `C`
- [FSArchiver](http://www.fsarchiver.org/) - Save the contents of a file system to a compressed archive, if one of the checksums doesn't match the file is lost, not the whole backup -- `C`
- [Grsync](http://www.opbyte.it/grsync/) - GUI for rsync -- `Windows` `OS X` `C`
- [Mondo Rescue](http://www.mondorescue.org/) - Disaster recovery, supports tapes, disks, network and CD/DVD as backup media, multiple filesystems, LVM, software and hardware RAID -- `C`
- [rdiff-backup](https://github.com/sol1/rdiff-backup) - Combines the best features of a mirror and an incremental backup in a bandwidth efficient manner -- `Windows` `OS X` `Python`
- [Redo Backup and Recovery](https://sourceforge.net/projects/redobackup/) - Simple bare metal backup and restore, live CD -- `Windows`
- [Relax and Recover (REAR)](http://relax-and-recover.org/) - BMR, simple, integrates with commercial backup solutions -- `shell`
- [rsnapshot](https://www.rsnapshot.org/) - Uses rsync and hard links, can keep multiple full backups available while using very little disk space -- `OS X` `perl` `shell`
- [SafeKeep](http://safekeep.sourceforge.net/) - Superb project, uses LVM snapshots -- `Python`
- [SnapRAID](https://www.snapraid.it/) - Backup program that also stores RAID parity information -- `C`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Multi-OS file sync tool, syncs from both sides, no master -- `OS X`
- [UrBackup](https://www.urbackup.org/) - Supports Windows, has a web interface -- `Windows` `C++`

---

## Cloud File Sync and Sharing

> Sync files to and share from public or private file stores (think Dropbox, Google Drive, etc) - see also [Backups](#backups)

- [Drive](https://github.com/odeke-em/drive) - Push or pull files to Google Drive via the command line -- `Golang`
- [git-annex Assistant](https://git-annex.branchable.com/assistant/) - Sync folder(s) to any device (NAS, mobile, thumb, cloud, etc) via git -- `C` `OS X` `mobile`
- [lsyncd](https://github.com/axkibe/lsyncd) - Watches a local directory trees event monitor interface (inotify or fsevents) and kicks off an rsync when things change -- `Lua`
- [Mackup](https://github.com/lra/mackup) - Sync your Mac application settings to various cloud services or git -- `Python` `OS X`
- [Nextcloud](https://nextcloud.com/) - Fork of and replacement for OwnCloud, a self-hosted Dropbox -- `various lang` `Windows` `OS X`
- [Pydio](https://pyd.io/) - Formerly AjaXplorer, AGPL license -- `PHP`
- [rclone](https://rclone.org/) - Probably the best cloner, supports almost any source and dest -- `Golang`
- [Seafile](https://seafile.com/en/home/) - Also offers a paid professional edition with more features, supports most platforms -- `C`
- [SparkleShare](https://sparkleshare.org/) - Uses git under the hood, neat -- `Windows` `OS X`
- [Syncany](https://www.syncany.org/) - Supports tons of different protocols for the transfer (SCP, FTP, Samba, S3, etc) -- `Gradle`
- [Syncthing](https://syncthing.net/) - Uses an ID rather than an IP address, share your ID with friends and go -- `Golang`
- [Tahoe-LAFS](https://www.tahoe-lafs.org/trac/tahoe-lafs) - Free and open decentralized cloud storage system -- `Python`

---

## Collaboration Tools

> ChatOps, code review, groupware, webmail, code sharing, and more - see also [Dashboards and Data Visualization](#dashboards-and-data-visualization) and [Graphics Stuff](#graphics-stuff) and [Editors](#editors) and [Git Tools](#git-tools) and [Software Development Tools](#software-development-tools)

- [Citadel](http://www.citadel.org/) - Messaging, collaboration tools, and groupware - an all-in-one package -- `C`
- [Codeshare](https://codeshare.io/) - In-browser screenshare to teach coding, group code, or as an interview whiteboard -- `in-browser`
- [dev-setup](https://github.com/donnemartin/dev-setup) - Automated setup scripts for laptop tools like Sublime Text, AWS, Spark, Android dev, and more -- `collection`
- [Etherpad](https://etherpad.org/) - Enter, save, and share text/code in a web browser -- `JavaScript`
- [FreeIPA](https://www.freeipa.org/page/Main_Page) - Identity, policy, and audit suite, think Active Directory for Linux (LDAP, CA, x509, DNS, Kerberos) -- `various lang`
- [FreeMind](https://en.wikipedia.org/wiki/FreeMind) - OSS mind mapping software, great for brainstorming -- `Java` `Windows` `OS X`
- [gcalcli](https://github.com/insanum/gcalcli) - CLI for Google Calendar -- `Python pip`
- [gmvault](http://gmvault.org/) - Export/backup and restore your Gmail account -- `Python`
- [Got Your Back](https://github.com/jay0lee/got-your-back) - Gmail backups over HTTPS -- `Python`
- [Haste / hastebin](https://github.com/seejohnrun/haste-server) - Open source pastebin alternative for sharing code, can be installed locally / on-site -- `JavaScript`
- [Hubot](https://hubot.github.com/) - Chat bot that can do deploys, look up images, integrate with Google Maps, and tons of other stuff -- `CoffeeScript`
- [Isso](https://posativ.org/isso/) - A commenting server similar to Disqus -- `JavaScript`
- [Kanboard](https://kanboard.org/) - Simple Kanban board -- `PHP`
- [Kolab](https://kolab.org/) - Unified communication and collaboration system -- `PHP`
- [LDAP Account Manager (LAM)](https://www.ldap-account-manager.org/lamcms/) - Full featured LDAP management GUI, can manage almost anything -- `PHP`
- [Mattermost](https://about.mattermost.com/download/) - OSS Slack alternative -- `Golang` `JavaScript`
- [Mailtrain](https://github.com/Mailtrain-org/mailtrain) - Self hosted news letter e-mail app, similar to Mailchimp -- `JavaScript`
- [OpenProject](https://www.openproject.org) - Web-based project management system built on Ruby on Rails -- `Ruby`
- [osTicket](https://osticket.com/) - Routes inquiries created via email, web-forms and phone calls into a web-based customer support platform -- `PHP`
- [OTRS](https://www.otrs.com/) - Open source help desk software -- `perl`
- [OwnTracks](https://owntracks.org/) - Self-hosted location tracking you can share - use for diaries, work orders, etc -- `various lang` `mobile`
- [Pandoc](https://pandoc.org/) - Convert files from one markup format to another, supports a ton of formats -- `Haskell`
- [Phabricator](https://www.phacility.com/) - Suite of web-based software dev collaboration tools, and all-in-one project management tool -- `PHP`
- [PrivateBin](https://privatebin.info/) - Pastebin where the server has zero knowledge of pasted data, data is encrypted/decrypted in the browser using 256 bits AES -- `various lang`
- [QueryClips](https://www.queryclips.com/) - Pastebin for Postgres or my mySQL SQL query sharing -- `in-browser`
- [RainLoop](https://www.rainloop.net/) - Simple, modern & fast web-based email client -- `PHP`
- [Redmine](https://www.redmine.org/) - Project management webapp -- `Ruby`
- [Request Tracker](https://bestpractical.squarespace.com/download) - Bug tracking, help desk ticketing, customer service, workflow processes, change management and more -- `perl`
- [Review Board](https://www.reviewboard.org/) - Code review tool for multiple SCM systems -- `Python`
- [Rocket.Chat](https://rocket.chat/) - OSS Slack clone built with Meteor.js -- `JavaScript`
- [Roundcube](https://roundcube.net/) - Browser-based multilingual IMAP client -- `PHP`
- [Scribus](https://www.scribus.net/) - Open source desktop publishing (layout, typesetting, etc), Adobe InDesign alternative -- `C++` `Windows` `OS X`
- [SOGo](https://www.sogo.nu/) - Groupware that integrates with Microsoft, Android, and Apple products -- `Objective-C` `OS X`
- [Sovereign](https://github.com/al3x/sovereign) - Set of Ansible playbooks to deploy a suite of self-hosted apps (mail, colab, calendar, file sync, and more) -- `Python`
- [Synergy](https://synergy-project.org/) - Share a single keyboard and mouse with multiple physical computers, only the old version is free now -- `closed source` `Windows` `OS X`
- [Taiga](https://taiga.io/) - Project management web application with agile/ scrum in mind -- `Python` `CoffeeScript`
- [TermRecord](https://github.com/theonewolf/TermRecord) - Record and playback terminal sessions, outputs self-contained HTML -- `Python`
- [VisioCafe](www.visiocafe.com/) - The largest collection of free Visio stencils -- `collection`
- [WeKan](https://wekan.github.io/) - OSS Trello-like kanban board -- `JavaScript`
- [YOURLS (Your Own URL Shortener)](https://yourls.org/) - Lets you run your own URL shortener a'la TinyURL or bit.ly -- `PHP`
- [Zulip](https://www.zulip.org/) - Group chat with chat threads, by Dropbox -- `various lang` `mobile` `Windows` `OS X`

---

## Containers

> Linux containers, container orchestration, networking, Docker, OpenShift, and related tools - see also [Distributed Systems Tools](#distributed-systems-tools) and [Virtualization and SDN](#virtualization-and-sdn) and [Web and HTTP Tools](#web-and-http-tools)

- [Alpine Linux](https://alpinelinux.org/) - Super minimal BusyBox based Linux distro, perfect for hosting containers -- `various lang`
- [Anchore](https://github.com/anchore/anchore-engine) - A centralized service for inspection, analysis and certification of container images -- `Golang`
- [appscale](https://github.com/AppScale/appscale) - Open source implementation of Google App Engine -- `Python`
- [Awesome Docker](https://github.com/veggiemonk/awesome-docker) - Massive Docker collection -- `collection`
- [Buildah](https://github.com/containers/buildah) - A low-level interface to core-utils, build container images with the scripting language of your choice without using Dockerfiles, compare to Podman -- `Golang`
- [cadvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers -- `Golang`
- [cert-manager](https://github.com/jetstack/cert-manager) - Automate the management and issuance of TLS certificates from various issuing sources -- `Golang`
- [Cilium](https://github.com/cilium/cilium) - Transparently secure layer 7 services, communicate based on identity groups, load balancing, BPF-level for performance and instrumentation & more -- `Golang`
- [Clear Linux](https://clearlinux.org/) - New name for Clear Containers, attempts combine the security advantages of VMs with the deployment advantages of containers -- `various lang`
- [ClusterCloner](https://github.com/doitintl/ClusterCloner) - Reads the Kubernetes clusters in one location (optionally filtering by labels) and clones them into another (or just outputs JSON as a dry run), to/from AWS, GCP, and Azure -- `Golang`
- [CodeReady Containers](https://github.com/code-ready/crc) - Run OpenShift 4.x locally on your laptop, RECOMMENDED -- `various lang`
- [CodeReady Single Node Cluster (SNC)](https://github.com/code-ready/snc) - Script to create an OpenShift 4.x single node cluster on Linux using KVM -- `shell`
- [crane](https://github.com/michaelsauter/crane) - Docker orchestration, similar to Docker Compose -- `Golang`
- [ctop](https://ctop.sh/) - ncurses top-like UI for containers -- `Golang`
- [Dex](https://github.com/dexidp/dex) - A federated OpenID Connect provider -- `Golang`
- [distroless](https://github.com/GoogleContainerTools/distroless) - "Distroless" images contain only your application and its runtime dependencies and nothing else, by Google -- `various lang`
- [docker-debug](https://github.com/zeromake/docker-debug) - Attach a new "debug container" to existing namespaces so you don't have to include debug tools in the app containers -- `Golang`
- [docker-gc](https://github.com/spotify/docker-gc) - Docker garbage collection of containers and images -- `shell`
- [DockerSlim](http://dockersl.im/) - Uses static and dynamic analysis to create skinny image variants of your fat images -- `Golang`
- [dockerviz](https://github.com/justone/dockviz) - Great tool for analyzing images -- `Golang`
- [Docker Bench](https://github.com/docker/docker-bench-security) - Checks for dozens of common best-practices around deploying Docker containers in production -- `shell`
- [Docker Compose](https://github.com/docker/compose) - Define and run multi-container apps with Docker, previously known as fig, official -- `Python`
- [Docker Desktop](https://www.docker.com/products/docker-desktop) - Notable because it works without admin / root, Mac and Windows -- `Golang`
- [Docker Distribution](https://github.com/docker/distribution) - AKA Docker Registry 2.0 - pack, ship, store, and deliver containers -- `Golang`
- [Docker Hub](https://registry.hub.docker.com/) - Official Docker images for many projects -- `various lang`
- [Docker Toolbox](https://www.docker.com/toolbox) - Docker Client, Machine, Compose, Kitematic, VirtualBox, and the boot2docker VM in a single package, official -- `various lang`
- [dockerfile-security](https://github.com/gbrindisi/dockerfile-security) - Open Policy Agent (OPA) rules for dockerfiles that can be integrated into your pipeline -- `collection`
- [Dockit](https://github.com/awkspace/dockit) - Jump into a container image of your choosing, taking all the files from the current directory with you -- `shell`
- [Dokku](https://github.com/progrium/dokku) - Docker powered mini-Heroku (PaaS) in around 100 lines of bash -- `shell`
- [dumb-init](https://github.com/Yelp/dumb-init) - Minimal init system for containers, by Yelp -- `C`
- [Fedora CoreOS](https://coreos.fedoraproject.org/) - The best of CoreOS + Fedora Atomic Host, upstream to RHEL CoreOS, successor to now sunset RHEL / Fedora Atomic & Container Linux -- `various lang`
- [Flatcar Container Linux](https://www.flatcar-linux.org/) - Immutable Linux distribution for containers, the modern choice -- `various lang`
- [gvisor](https://github.com/google/gvisor) - User-space kernel, can be used to sandbox containers, by Google -- `Golang`
- [img](https://github.com/genuinetools/img) - Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder -- `Golang`
- [Jenkins Docker Slaves Plugin](https://github.com/jenkinsci/docker-slaves-plugin) - Aka Dockins, execute a Jenkins job inside one or more containers, supports most job types -- `Java`
- [jib](https://github.com/GoogleContainerTools/jib) - Build container images for your Java applications, by Google -- `Java`
- [Kata Containers](https://katacontainers.io/) - A mix of Clear Containers / Clear Linux and Hyper's runV -- `frankencontainers` `various lang`
- [Kitematic](https://kitematic.com/) - GUI Docker management on Mac & Windows (laptops), official -- `JavaScript` `Windows` `OS X`
- [Kraken](https://github.com/uber/kraken) P2P Docker registry capable of distributing TBs of data in seconds using a slightly modified BitTorrent protocol -- `Golang`
- [Lazydocker](https://github.com/jesseduffield/lazydocker) - Terminal UI for both docker and docker-compose -- `Golang`
- [LinuxKit](https://github.com/linuxkit/linuxkit) - Toolkit for building custom minimal, immutable Linux distributions -- `Golang`
- [Logspout](https://github.com/gliderlabs/logspout) - Log router for Docker containers -- `Golang`
- [Minishift](https://www.openshift.org/minishift/) - OpenShift in a VM for testing / learning -- `Golang`
- [ngnix-proxy](https://github.com/jwilder/nginx-proxy) - Nginx proxy for Docker containers using docker-gen, recommened -- `Python`
- [Nomad](https://www.nomadproject.io/) - Highly scalable application, process, and container orchestraction, multi-cloud support -- `Golang`
- [OKD](https://www.okd.io/) - The upstream for Red Hat's OpenShift 3.x, previously OpenShift Origin -- `Golang`
- [OKD Install](https://github.com/gshipley/installcentos) - Set of file that installs OKD 3.x (OpenShift's upstream, formerly OpenShift Origin) on a single CentOS VM for testing & dev -- `shell`
- [OpenShift 4 Bare Metal Install - User Provisioned Infrastructure (UPI)](https://github.com/ryanhay/ocp4-metal-install) - For testing and learning, requires access to RedHat OpenShift Cluster Manager -- `various lang`
- [OpenShift Container Platform Install Demo](https://gitlab.com/redhatdemocentral/ocp-install-demo) - Install an OpenShift 4.x demo system on Linux, Windows, or Mac, by Red Hat -- `various lang`
- [OpenShift Virtualization Hands-on Lab](https://github.com/rdoxenham/openshift-virt-labs) - Script that builds out an OpenShift UPI installation on a single baremetal machine where all of the masters and workers are virtualised -- `shell`
- [Panamax](https://panamax.io/) - Containerized app creator with an open-source app marketplace hosted in GitHub -- `various lang`
- [Permission Manager](https://github.com/sighupio/permission-manager) - Excellent solution for standalone or onprem isolated clusters -- `Golang`
- [pipework](https://github.com/jpetazzo/pipework) - SDN for Linux Containers -- `various lang`
- [Popeye](https://github.com/derailed/popeye) - Scans the live cluster for dead or unused resources such as ports mismatches, metrics utilization, probes, container images, RBAC rules, naked resources, etc -- `Golang`
- [Portainer](https://github.com/portainer/portainer) - Web interface for Docker aka us-for-docker -- `JavaScript`
- [pulumi](https://pulumi.io/) - HOT create and deploy cloud programs that use containers, serverless functions, hosted services, and infrastructure, on any cloud, supports most languages -- `various lang`
- [Pulumi Cloud Framework](https://github.com/pulumi/pulumi-cloud) - Multi-cloud support via a single API -- `various lang`
- [Rancher](https://rancher.com/) - Provides a complete platform for operating Docker in production -- `various lang`
- [Registrator](https://github.com/gliderlabs/registrator) - Service registry bridge for Docker, supports Consul, etcd -- `Golang`
- [swarm-viz](https://github.com/mikesir87/swarm-viz) - Docker Swarm visualizer -- `JavaScript`
- [Watchtower](https://github.com/v2tec/watchtower) - Monitors your running Docker containers and restart them when a new image is available -- `Golang`
- [Weave](https://github.com/zettio/weave/) - Virtual network that connects Docker containers deployed across multiple hosts -- `Golang`

---

## Dashboards and Data Visualization

> Dashboards for monitoring, alerting, metrics, data visualization tools, and status boards - see also [Metrics and Time Series Data](#metrics-and-time-series-data) and [Logging](#logging) and [Monitoring and Alerting](#monitoring-and-alerting)

- [Bigdesk](https://github.com/hlstudio/bigdesk) - Live charts and statistics for Elasticsearch cluster -- `JavaScript`
- [Cachet](https://cachethq.io/) - Create beautiful, responsive status pages -- `PHP`
- [Cacti](https://cacti.net/) - Web-based network monitoring and graphing tool designed as a front-end to RRDtool -- `PHP`
- [Dashkiosk](https://github.com/vincentbernat/dashkiosk) - An excellent, simple dashboard that supports multiple screens -- `JavaScript`
- [Facette](https://facette.io/) - Time series data visualization and graphing software -- `Golang`
- [Flame Graphs](http://www.brendangregg.com/flamegraphs.html) - Stack trace visualizer by Brendan Gregg -- `perl`
- [Gource](https://github.com/acaudwell/Gource) - Software version control visualization tool -- `C++`
- [Graphene](https://jondot.github.io/graphene/) - Graphite dashboard in D3 and Backbone -- `JavaScript`
- [Hygieia](https://github.com/capitalone/Hygieia) - Visualize near real-time status of the entire delivery pipeline, by Capital One -- `Java`
- [ksar](https://sourceforge.net/projects/ksar/) - Creates pretty graphs from sar output -- `Java`
- [logstalgia](https://logstalgia.io/) - Web site access log visualization tool, aka Apache Pong -- `C++`
- [Loki](https://github.com/grafana/loki) - Like Prometheus but for logs -- `Golang`
- [lsofgraph](https://github.com/zevv/lsofgraph) - lsof output into to Graphviz -- `Lua`
- [Grafana](https://grafana.org/) - Modern dashboard for Graphite -- `JavaScript`
- [grafana-statusmap](https://github.com/flant/grafana-statusmap) - Grafana status panel -- `JavaScript`
- [Mozaik](https://github.com/plouc/mozaik) - Create beautiful dashboards using Node/React/D3 -- `JavaScript`
- [MRTG (Multi Router Traffic Grapher)](https://oss.oetiker.ch/mrtg/) - Still being updated -- `perl`
- [Nagdash](https://github.com/lozzd/Nagdash) - Dashboard / NOC screen for Nagios -- `PHP`
- [NagVis](https://www.nagvis.org/) - Visualization suite for Nagios -- `PHP`
- [Nagiosgraph](http://nagiosgraph.sourceforge.net/) - Another visualization tool for Nagios data -- `perl`
- [Network Weathermap](https://www.network-weathermap.com/) - Network visualization tool, create a "weather map" just like big ISPs use, not dead yet -- `PHP`
- [OpenSearch Dashboards](https://github.com/opensearch-project/OpenSearch-Dashboards) - Derived from Kibana 7.10.2, for use with OpenSearch, by Amazon -- `JavaScript`
- [pdash](https://github.com/Jahaja/psdash) - web dashboard for linux using data mainly served by psutil -- `Python pip`
- [PNP4Nagios](https://docs.pnp4nagios.org/) - Analyzes performance data provided by plugins and stores them automatically into RRD-databases -- `PHP`
- [promviz](https://github.com/nghialv/promviz) - Visualize the traffic of your clusters in realtime from Prometheus data -- `Golang`
- [redash](https://redash.io/) - Web application that allows to easily query an existing database, share the dataset and visualize it in different ways -- `various lang`
- [Seyren](https://github.com/scobal/seyren) - Alerting dashboard for Graphite -- `Java`
- [Smashing](https://github.com/Smashing/smashing) - Successor to Dashing -- `Ruby`
- [Staytus](https://github.com/adamcooke/staytus) - Complete solution for publishing the latest info about issues with your web applications, networks or services -- `Ruby`
- [Tessera](https://github.com/urbanairship/tessera) - Graphite dashboard in Python -- `Python pip`
- [Thruk](https://www.thruk.org/) - Web interface for Nagios, Icinga, Shinken and Naemon, can create SLA reports, has a mobile client -- `JavaScript`
- [vnstati](https://linux.die.net/man/1/vnstati) - Creates PNG images using vnStat data -- `built-in`

---

## Distributed Systems Tools

> DCOSes, microservices, service discovery, schedulers, and related tools for dynamic, warehouse-scale computing - see also [Containers](#containers) and [HPC Tools](#hpc-tools)

- [Akkio](https://code.fb.com/core-data/akkio/) - Data placement service that determines how and when to move information in order to optimize retrieval speed for people across the globe, using the minimum required number of copies -- `various lang`
- [Avro](https://avro.apache.org/) - Data serialization system with backwards compatible schemas -- `Java`
- [Celery](http://www.celeryproject.org/) - Async task/job queue based on distributed message passing -- `Python`
- [Chaperone](https://github.com/uber/chaperone) - End-to-end Kafka auditing (data loss, latency, message duplication, etc), by Uber -- `Java`
- [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul -- `Golang`
- [Crossplane](https://crossplane.io/) - Multicloud control plane -- `Golang`
- [Cruise Control](https://github.com/linkedin/cruise-control) - Fully automate the dynamic workload rebalance and self-healing of a Kafka cluster, by Linkedin -- `Java`
- [Cruise Control UI](https://github.com/linkedin/cruise-control-ui/) - Also by Linkedin -- `JavaScript`
- [consul](https://www.consul.io/) - Service discovery and configuration via DNS or HTTP, great for auto-scaling -- `Golang`
- [consul Tools](https://www.consul.io/downloads_tools.html) - Official, includes consul-template and others -- `various lang`
- [DoctorKafka](https://github.com/pinterest/doctorkafka) - Kafka cluster auto healing and workload auto-balancing -- `Java`
- [etcd](https://github.com/coreos/etcd) - Distributed, consistent key-value store for shared configuration and service discovery -- `Golang`
- [fabio](https://github.com/eBay/fabio) - Zero-conf load balancing HTTP(S) router for deploying microservices managed by Consul, by eBay -- `Golang`
- [Flink](https://flink.apache.org) - Next-generation true stream processing platform for real-time analytics -- `Java`
- [GraphQL](https://en.wikipedia.org/wiki/GraphQL) - Alternative to REST, allows clients to define the structure of the data, subscribing to data flows, and more -- `various lang`
- [groupcache](https://github.com/golang/groupcache) - A replacement for memcached by the same guy -- `Golang`
- [Hystrix](https://github.com/Netflix/Hystrix) - Circuit breaker library to stop cascading failures, by Netflix -- `Java`
- [Ignite](https://ignite.apache.org/) - General-purpose in-memory platform for in-memory computing use cases -- `Java`
- [jespen](https://github.com/aphyr/jepsen) - A framework for distributed systems verification, with fault injection -- `Clojure`
- [JVM Profiler](https://eng.uber.com/jvm-profiler/) - Distributed profiler to collect JVM performance and resource usage metrics and serve them for further analysis, by Uber -- `Java`
- [kafdrop](https://github.com/obsidiandynamics/kafdrop) - Web UI for viewing Kafka topics and browsing consumer groups -- `Java`
- [Kafka](https://kafka.apache.org) - Stream processing platform (logs, IoT metrics, anything) -- `Java`
- [kafkacat](https://github.com/edenhill/kafkacat) - Generic CLI producer and consumer -- `C`
- [keto](https://github.com/ory/keto) - OSS implementation of Zanzibar: Google's Consistent, Global Authorization System -- `Golang`
- [Kong](https://getkong.org/) - Microservice abstraction layer (aka API Gateway or Service Mesh), great for creating API endpoints -- `Lua`
- [LogDevice](https://logdevice.io/) - A distributed data store for logs, by Facebook -- `C++`
- [Mantl](https://mantl.io/) - Complete microservices infrastructure built using OSS tools by Cisco -- `various lang` `yowza`
- [MaxScale](https://github.com/mariadb-corporation/MaxScale) - General purpose DB query proxy, router, and load balancer, by MariaDB -- `C`
- [mcrouter](https://github.com/facebook/mcrouter) - memcached protocol router for scaling memcached, by Facebook -- `C++`
- [Mitogen](https://mitogen.readthedocs.io/en/latest/) - Python library for writing distributed self-replicating programs like magic -- `Python`
- [mrjob](https://github.com/Yelp/mrjob) - Lets you write MapReduce and Spark jobs in Python 2.7/3.4+ and run them on several platforms (AWS, GCP) -- `Python pip`
- [NATS](https://nats.io/) - Pub / sub -- `Golang`
- [nsq](https://nsq.io/) - Realtime distributed messaging platform / message queue -- `Golang`
- [OpenStack](https://www.openstack.org/) - Private cloud -- `Python`
- [Pinpoint](https://github.com/naver/pinpoint) - Application Performance Monitoring (APM) for distributed systems, based on Dapper -- `Java`
- [Plumber](https://github.com/batchcorp/plumber) - Read and write messages to Kafka, RabbitMQ, Google Cloud PubSub, and more -- `Golang`
- [redis-cell](https://github.com/brandur/redis-cell) - Redis module that provides rate limiting in Redis as a single command using GCRA -- `C`
- [Redisson](https://github.com/mrniko/redisson) - Distributed and scalable Java data structures on top of Redis -- `Java`
- [Redpanda](https://vectorized.io/) - Kafka compatible event streaming platform no Zookeeper, no JVM, and no code changes required -- `C++`
- [Riemann](http://riemann.io/) - Aggregates events from your servers and applications with a powerful stream processing language, for distributed systems, similar to Borgmon -- `Clojure`
- [Serf](https://www.serfdom.io/) - Decentralized solution for service discovery and orchestration -- `Golang`
- [Spark](https://spark.apache.org) - Near real-time analytics processing platform, succeeded by Flink (real streaming vs Spark's microbatches) -- `various lang`
- [Spring Cloud Config](https://cloud.spring.io/spring-cloud-config/) - Allows Java Spring to read config info from service discovery or similar source -- `Java`
- [uReplicator](https://github.com/uber/ureplicator) - Improved Kafka MirrorMaker by Uber -- `Java`
- [Zookeeper](https://zookeeper.apache.org/) - Distributed configuration service, synchronization service, and naming registry -- `Java`

---

## Editors

> IDEs, text & source editors, vim plugins, and similar tools - see also [Graphics Stuff](#graphics-stuff) and [Collaboration Tools](#collaboration-tools)

- [010 Editor](https://www.sweetscape.com/010editor/) - Professional hex editor that supports binary templates for easy reading, scripting, and more -- `closed source`
- [activate-power-mode](https://github.com/JoelBesada/activate-power-mode) - Activate POWER MODE and write code in style, an Atom plugin -- `CoffeeScript`
- [Atom](https://atom.io) - Superb text editor, created by GitHub -- `CoffeeScript`
- [Atom Vim Mode](https://github.com/atom/vim-mode) - vi/vim style controls for Atom -- `CoffeeScript`
- [Atom Linters](https://github.com/AtomLinter) - A collection of lint tools for the Atom editor -- `various lang`
- [Brackets](http://brackets.io/) - Modern editor that understands and focuses on web design, by Adobe -- `JavaScript`
- [LargeFile](https://www.vim.org/scripts/script.php?script_id=1506) - vim plugin that automatically disables certain things so you can edit large (multi-gig) files faster -- `vim`
- [Light Table](http://lighttable.com/) - Next-generation editor that gives you instant feedback -- `Clojure`
- [MacDown](https://macdown.uranusjr.com/) - Markdown editor and live preview for Mac -- `Objective-C` `OS X`
- [MacVim](https://github.com/macvim-dev/macvim) - Has far more features than the vim that's included with the OS -- `C`
- [Nuclide](https://nuclide.io/) - Collection of packages for Atom to provide IDE-like functionality for a variety of programming languages and technologies, by Facebook -- `JavaScript`
- [Notepad++](https://notepad-plus-plus.org/) - Killer GPL'ed text editor for Windows -- `C++`
- [percol](https://github.com/mooz/percol) - Interactive grep (search) tool -- `Python`
- [Powerline](https://github.com/powerline/powerline) - Provides various statues on the bottom of your session, flexible -- `Python`
- [Textmate](https://macromates.com/) - GUI text editor for OS X -- `C++`
- [UltiSnips](https://github.com/SirVer/ultisnips) - The ultimate snippet solution for vim -- `Python`
- [vim-json](https://github.com/elzr/vim-json) - A better JSON plugin for vim -- `vim`
- [vim-snippets](https://github.com/honza/vim-snippets) - snipMate & UltiSnip snippets -- `vim`
- [Vimium](https://vimium.github.io/) - Chrome extension that provides vi/vim style shortcuts for navigation and control -- `CoffeeScript` `Chrome`
- [Visual Studio Code - Open Source](https://code.visualstudio.com/Download) - Open source version of Microsoft's product -- `JavaScript`
- [Vundle](https://github.com/VundleVim/Vundle.vim) - Popular plug-in manager for vim -- `vim`
- [wasavi](https://github.com/akahuku/wasavi) - vim/vi controls in browser text areas -- `JavaScript` `Firefox` `Chrome`
- [wxHexEditor](https://www.wxhexeditor.org/) - Free hex editor, disk editor, and big file editor for Linux, Windows and Mac OS X -- `C`
- [YouCompleteMe](https://valloric.github.io/YouCompleteMe/) - Fuzzy-search code completion engine for vim -- `Python`

---

## Git Tools

> Tools for interacting with git and GitHub - see also [Software Development Tools](#software-development-tools)

- [BFG Repo-Cleaner](https://github.com/rtyley/bfg-repo-cleaner) - Scrub large blobs and sensitive data from git history -- `Scala`
- [blackbox](https://github.com/StackExchange/blackbox) - Safely store secrets in Git, by Stack Exchange -- `shell`
- [Completion](https://github.com/git/git/tree/master/contrib/completion) - Shell tab completion for git branch names -- `shell`
- [Gerrit](https://www.gerritcodereview.com/) - Web based code review and repo management for Git -- `Java`
- [git-fat](https://github.com/jedbrown/git-fat) - Like git-media but without the Ruby dependencies -- `Python`
- [GitKraken](https://www.gitkraken.com/) - Probably the best multi-platform git GUI -- `closed source` `Windows` `OS X` `Linux`
- [GitHub Pull Request Builder Plugin (gprbp)](https://wiki.jenkins-ci.org/display/JENKINS/GitHub+pull+request+builder+plugin) - Jenkins plugin that allows certain comment strings to kick off builds or take other actions -- `Java`
- [GitLab](https://about.gitlab.com/) - Kinda like an open source GitHub, has both a community and paid version -- `Ruby`
- [GitLab CI](https://about.gitlab.com/gitlab-ci/) - CI that integrates with GitLab -- `Ruby`
- [gitsome](https://github.com/donnemartin/gitsome) - Supercharged CLI with GitHub integration -- `Python`
- [GitUp](https://gitup.co) - Maybe the best git GUI -- `Objective-C`
- [gitwatch](https://github.com/nevik/gitwatch) - Automatically commit changes when specified files or directories are modified -- `shell`
- [Git Interfaces, Frontends, and Tools](https://git.wiki.kernel.org/index.php/Interfaces,_frontends,_and_tools) - Massive list on the official kernel.org wiki -- `various lang`
- [Gogs](https://gogs.io/) - Painless, self-hosted Git service written in -- `Golang`
- [hub](https://hub.github.com/) - Official CLI for GitHub -- `Golang`
- [myrepos](https://myrepos.branchable.com/) - Flexible tool for managing many repos -- `perl`
- [Signing](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work) - Sign commits and/or tags using GPG keys to verify the identity of the commiter -- `built-in`

---

## Graphics Stuff

> Not everything happens in the browser or on the command line - see also [Collaboration Tools](#collaboration-tools) and [Data Visualization and Dashboards](#data-visualization-and-dashboards)

- [Archimate](https://www.archimatetool.com/) - Open source cross platform tool for enterprise architects -- `Java`
- [Avidemux](http://fixounet.free.fr/avidemux/) - Simple, all-in-one, GUI video editor and converter -- `C++` `Windows` `OS X`
- [Blender](https://www.blender.org/) - 3D graphics software for animated films, visual effects, art, 3D printed models, and more -- `C` `Python` `Windows` `OS X`
- [blockdiag](http://blockdiag.com/en/) - Generate simple block/sequence/activity/network diagrams from text files -- `Python pip`
- [Darktable](https://www.darktable.org/) - Photography workflow application and RAW developer, Adobe Lightroom replacement -- `C` `OS X`
- [draw.io](https://www.draw.io/) - Free online flow chart maker / Visio alternative, can be self-hosted -- `in-browser`
- [drawio-desktop](https://github.com/jgraph/drawio-desktop) - draw.io in Electron -- `JavaScript`
- [GlyphSearch](https://glyphsearch.com/) - Search for icons from Font Awesome, Glyphicons, IcoMoon, Ionicons, and Octicons -- `collection`
- [GIMP (GNU Image Manipulation Program)](https://www.gimp.org/) - Open source Adobe Photoshop replacement -- `C`
- [Graphviz](https://www.graphviz.org/) - Graph visualization and flow chart software -- `wacky license`
- [Greenshot](https://getgreenshot.org/) - The best Windows screenshot tool -- `C#` `Windows`
- [Inkscape](https://www.inkscape.org/) - Open source vector image editor, Adobe Illustrator replacement -- `C` `C++` `Windows` `Mac`
- [LICEcap](https://www.cockos.com/licecap/) - Capture an area of your desktop and save it to a GIF -- `C` `Windows` `OS X`
- [mac2imgur](https://github.com/mileswd/mac2imgur) - Auto-upload screenshots to Imgur -- `Swift` `OS X`
- [maim](https://github.com/naelstrof/maim) - The most powerful and flexible Linux desktop screenshot tool -- `various lang`
- [Media Player Classic - Home Cinema (MPC-HC)](https://mpc-hc.org/) - Open source media player for Windows -- `C++` `Windows`
- [OpenShot](https://openshot.org/) - Video editing software, 2.0 will support other additional platforms -- `Python` `Windows` `OS X`
- [Origami](https://origami.design/) - Interactive UI design prototyping without programming, by Facebook -- `various lang`
- [Pencil](https://pencil.evolus.vn/) - Open source GUI prototyping and mockup tool, supports all platforms -- `Windows` `OS X`
- [PlantUML](http://plantuml.com/) - Easily create beautiful UML Diagrams from simple textual description -- `Java`
- [ScreenToGif](https://www.screentogif.com/) - Record a selected area of your screen, edit and save it as a GIF or video -- `C++`
- [ShareX](https://getsharex.com/) - One of the best screenshot/screencast capture and sharing tools for -- `Windows` `OS X`
- [Skitch](https://evernote.com/skitch/) - Feature-rich screenshot editing, sharing, and annotation tool Mac/OS X -- `closed source`
- [VLC Media Player](https://www.videolan.org/vlc/) - Media (music, video, etc) player and streaming server -- `C` `Windows` `OS X`
- [yEd Graph Editor](https://www.yworks.com/en/products/yfiles/yed/) - Flowcharts and UML diagrams -- `closed source`

---

## High Availability Clustering Tools

> HA clustering tools including storage replication, failover, VIPs, and more - see also [Distributed Systems Tools](#distributed-systems-tools) and [Containers](#containers)

- [Corosync](https://corosync.github.io/corosync/) - HA framework and cluster engine -- `C`
- [csync2](https://github.com/LINBIT/csync2) - General purpose cluster file sync tool -- `C`
- [DRBD (Distributed Replicated Block Device)](https://docs.linbit.com/) - Mirror block devices to a remote system aka replication -- `C`
- [Ganeti](http://www.ganeti.org/) - Wrappers around existing tools to make it easy to create HA clusters, by Google -- `Python`
- [HAproxy](https://www.haproxy.org/) - Open source software load balancer -- `C`
- [haproxyctl](https://github.com/flores/haproxyctl) - Wrapper to talk to the HAProxy socket, as well as regular init (start stop restart) shit -- `Ruby`
- [keepalived](http://www.keepalived.org/) - Load balancing and high availability -- `C`
- [huptime](https://github.com/amscanne/huptime) - Zero downtime restarts of unmodified programs -- `C`
- [Linux-HA](http://www.linux-ha.org) - Building blocks for high availability systems -- `wiki-and-collection`
- [LVS (Linux Virtual Server)](http://www.linuxvirtualserver.org/) - Linux-based load balancer, also includes the IPVS kernel module -- `C`
- [Multibinder](https://github.com/github/multibinder) - Simple Ruby daemon that makes true zero downtime reloads simple, by Github -- `Ruby`
- [Pacemaker](https://clusterlabs.org/) - HA resource manager -- `C`
- [rcron](https://code.google.com/p/rcron/) - cron redundancy and failover, ensures a job will only run on the "active" machine -- `lost-to-the-internet` `C`
- [rmanager](https://linux.die.net/man/8/rgmanager) - Resource group manager daemon for cluster services -- `built-in`
- [Seesaw](https://github.com/google/seesaw) - Load balancer based on Linux Virtual Server (LVS), by Google -- `Golang`
- [Traefik](https://github.com/containous/traefik) - Modern HTTP reverse proxy and load balancer, supports many backends -- `Golang`
- [UCARP](https://www.pureftpd.org/project/ucarp) - VIP management using the CARP protocol -- `C`

---

## HPC Tools

> High performance computing for simulations, supercomputing, shared memory systems, and grid computing - see also [Distributed Systems Tools](#distributed-systems-tools) and [Containers](#containers)

- [Clustered File System](https://en.wikipedia.org/wiki/Clustered_file_system) - Ceph, GlusterFS, Lustre, etc, take your pick -- `various lang`
- [HTCondor](http://research.cs.wisc.edu/htcondor/) - Workload management system for compute-intensive jobs, formerly Condor
- [Maul Cluster Scheduler](http://www.adaptivecomputing.com/products/open-source/maui/) - Precursor to the Moab HPC Suite
- [MPI for Python (mpi4py)](https://pypi.python.org/pypi/mpi4py) - Python bindings for the Message Passing Interface (MPI) standard
- [MPICH](http://www.mpich.org/) - High-performance and widely portable implementation of the Message Passing Interface (MPI) standard
- [MUNGE](https://dun.github.io/munge/) - Authentication service for creating and validating credentials, designed for HPC
- [MVAPICH2](http://mvapich.cse.ohio-state.edu/) - MPI-3 over OpenFabrics-IB, OpenFabrics-iWARP, PSM, and TCP/IP
- [OpenMP](https://openmp.org/) - API that supports multi-platform shared memory multiprocessing programming in C, C++, and Fortran -- `article`
- [OpenMPI](https://www.open-mpi.org/) - Popular Message Passing Interface (MPI) library -- `C`
- [Open Grid Scheduler](http://gridscheduler.sourceforge.net/) - Formerly known as Sun Grid Engine -- `C`
- [OSCAR (Open Source Cluster Application Resources)](svn.oscar.openclustergroup.org/trac/oscar) - Makes it easy to create a Beauwulf-type HPC cluster
- [ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) - AWS supported Open Source cluster management tool to deploy and manage HPC clusters in the AWS cloud -- `Python`
- [Rocks Cluster Distribution](http://www.rocksclusters.org/) - Linux cluster distribution that enables end users to easily build computational clusters, grid endpoints and visualization displays
- [Slurm (Simple Linux Utility for Resource Management)](https://slurm.schedmd.com/) - One of the mostly widely used schedulers
- [StarCluster](http://star.mit.edu/cluster/) - Toolkit for using AWS for HPC, by MIT -- `Python`
- [TORQUE (Terascale Open-source Resource and QUEue Manager)](http://www.adaptivecomputing.com/products/open-source/torque/) - An updated and extended version of Portable Batch System (PBS)

---

## Infrastructure as Code Tools

> OS and cloud-level configuration management - see also [Asset Management](#asset-management) and [Orchestration](#orchestration) and [Package Patch and Repository Tools](#package-patch-and-repository-tools)

- [Ansible](https://www.ansible.com) - CM and orchestration, also can do provisioning -- `Python`
- [ansible-hardening](https://github.com/openstack/ansible-hardening) - For STIG compliance -- `Python`
- [ansible-runner](https://github.com/ansible/ansible-runner) - Provides a stable and consistent interface abstraction to Ansible so you can embed Ansible into other systems such as CI/CD, Jenkins, or other automated tooling -- `Python pip`
- [Ansible Galaxy](https://galaxy.ansible.com/) - Community site for finding, reusing, and sharing Ansible content -- `various lang`
- [ara (ARA Records Ansible)](https://github.com/ansible-community/ara) - Provides reporting by saving detailed and granular results of ansible and ansible-playbook commands -- `Python pip`
- [asecurecloud](https://asecure.cloud/) - A free library of 400+ customizable AWS security configurations and best practices (CF, Terraform, and AWS CLI) -- `collection`
- [Atlantis](https://github.com/runatlantis/atlantis) - A unified workflow for collaborating on Terraform through GitHub and GitLab, by Hootsuite -- `Golang`
- [Automatic Server Hardening](https://dev-sec.io/) - Linux hardening cookbooks/manifests/playbooks for Puppet, Chef, and Ansible -- `various lang`
- [awx](https://github.com/ansible/awx) - Upstream to Ansible Tower - REST API, task engine, etc -- `Python`
- [Azure Resource Manager (ARM) Tools for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools) - Language support, resource snippets, and resource auto-completion -- `various lang`
- [Azure Resource Manager (ARM) Viewer for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=bencoleman.armview) - Graphical preview of ARM templates -- `various lang`
- [Blueprint](https://github.com/devstructure/blueprint) - Reverse engineer a server configuration -- `Python pip`
- [Boxen](https://boxen.github.com/) - Mac / OS X configuration management -- `Ruby gem` `OS X`
- [Former2](https://github.com/iann0036/former2) - Generate CloudFormation / Terraform / Troposphere templates from your existing AWS resources via self-hosted web GUI -- `JavaScript`
- [GKE Demo](https://github.com/ilya-lesikov/gke-demo) - Demonstration of complete, fully-featured CI/CD and cloud automation for microservices, done with GCP/GKE -- `various lang`
- [Jenkins Ansible Tower Plugin](https://github.com/jenkinsci/ansible-tower-plugin) - Run Ansible Tower jobs as a build step -- `Java`
- [kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) - Test Kitchen plugins for testing Terraform configurations with InSpec -- `Ruby gem`
- [Molecule](https://github.com/ansible-community/molecule) - Used for testing Ansible roles -- `Python`
- [Oxidized](https://github.com/ytti/oxidized) - RANCID replacement, supports many platforms (Cisco, Brocade, Juniper, Citrix, etc) -- `Ruby gem`
- [python-terraform](https://pypi.org/project/python-terraform/) - Python wrapper for Terraform -- `Python pip`
- [RANCID - (Really Awesome New Cisco confIg Differ)](https://www.shrubbery.net/rancid/) - Pulls and saves network device configs and saves them into a CVS, now supports git -- `C`
- [Reclass](https://reclass.pantsfullofunix.net/index.html) - External node classifier for most CM systems, allows for a tagging system that's a layer above the CM tool -- `Python`
- [Salt / Saltstack](https://www.saltstack.com/) - Orchestration, server provisioning, and configuration management -- `Python`
- [Terraform](https://www.terraform.io/) - 1.0 released! - Infrastructure provisioning using existing tools, supports many providers (AWS, Azure, DO, OpenStack, etc) -- `Golang` `Hashicorp`
- [Terraformer](https://github.com/GoogleCloudPlatform/terraformer) - Generate terraform files from existing infrastructure (reverse Terraform), supports AWS and GCP, by Google -- `Golang`
- [Terraform CDK](https://github.com/hashicorp/terraform-cdk) - Use TypeScript or Python to generate Terraform config files -- `Golang`
- [Terraform Docs](https://terraform-docs.io/user-guide/introduction/) - Utility to generate documentation from Terraform modules in various output formats -- `Golang`
- [Terraform Landscape](https://github.com/coinbase/terraform-landscape) - Makes terraform plan easier to read -- `Ruby`
- [Terraform Modules by Cloud Posse](https://registry.terraform.io/namespaces/cloudposse) - Well written, well maintained, recommended -- `collection`
- [terraform-exec](https://github.com/hashicorp/terraform-exec) - Go module for constructing and running Terraform CLI commands -- `Golang`
- [Terraformer](https://github.com/GoogleCloudPlatform/terraformer) - Generate Terraform files from existing infrastructure (reverse Terraform), supports AWS and GCP, by Google -- `Golang`
- [Terraforming](https://terraforming.dtan4.net/) - Export all AWS resources into Terraform -- `Ruby gem`
- [Terragrunt](https://github.com/gruntwork-io/terragrunt) - Tools for keeping your Terraform configurations DRY, working with multiple Terraform modules, and managing remote state -- `Golang`
- [Terragrunt Reference Architecture (AWS)](https://github.com/antonbabenko/terragrunt-reference-architecture) - Nice, looking forward to their GCP one -- `various lang`
- [Terratest](https://github.com/gruntwork-io/terratest) - Makes it easier to write automated tests for your infrastructure code, provides a variety of helper functions and patterns for common infrastructure testing tasks -- `Golang`
- [tflint](https://github.com/wata727/tflint) - Terraform linter for detecting errors that can not be detected by terraform plan -- `Golang`
- [tfwriter](https://www.tfwriter.com/) - Auto-generate Terraform code in a non-opinionated way, also great for seeing which parameters a resource provides -- `in-browser`

---

## Kubernetes

> Kubernetes is ancient Egyptian for "he who has won the platform wars", see [Learning Resources](#learning-resources) for tutorials

- [Nomad](https://www.nomadproject.io/) - Consdier Nomad as a lightweight alternative to Kubernetes, by Hashicorp -- `Golang`
- [Ambassador](https://www.getambassador.io/) - Kubernetes-native API gateway built on Envoy proxy includes gRPC, auth, TLS, and more -- `Python`
- [Argo](https://github.com/argoproj/argo) - Container-native workflow engine implemented as a Kubernetes CRD (Custom Resource Definition) -- `Golang`
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - Collection -- `collection`
- [Banzai Cloud](https://github.com/banzaicloud) - Kubernetes based, open source, multi-cloud with all the good stuff baked in (Prometheus, CICD pipelines, and more) CHECK THIS -- `various lang`
- [ClusterCloner](https://github.com/doitintl/ClusterCloner) - Reads the Kubernetes clusters in one location (optionally filtering by labels) and clones them into another (or just outputs JSON as a
  dry run), to/from AWS, GCP, and Azure -- `Golang`
- [Contour](https://github.com/heptio/contour) - Kubernetes ingress controller using Lyft's Envoy proxy -- `Golang`
- [DevSpace](https://github.com/covexo/devspace) - Build, test and run code directly inside any Kubernetes cluster, no more waiting for rebuild + redeploy, run code instantly -- `Golang`
- [draft](https://github.com/Azure/draft) - Streamlined Kubernetes development with sandbox testing & deployment in seconds -- `Golang`
- [draino](https://github.com/planetlabs/draino) - Automatically drains Kubernetes nodes based on labels and node conditions, can be used for auto-remediation -- `Golang`
- [drone](https://github.com/drone/drone) - CI platform built on Docker / containers, can also deploy to Kubernetes -- `Golang`
- [Eirini](https://github.com/cloudfoundry-incubator/eirini) - Kubernetes backend for Cloud Foundry -- `Golang`
- [Envoy Proxy](https://lyft.github.io/envoy/) - Sidecar container for distributed applications or microservices, data plane service mesh / edge proxy -- `C++`
- [Escalator](https://github.com/atlassian/escalator) - Batch or job optimized horizontal autoscaler for Kubernetes -- `Golang`
- [Fluent Bit Kubernetes Daemonset](https://github.com/fluent/fluent-bit-kubernetes-logging) - The best logger, super light weight -- `Golang`
- [Flux](https://github.com/weaveworks/flux) - Tool that automatically ensures that the state of a Kubernetes cluster matches the config in git via Kubernetes operators -- `Golang`
- [Flux v2](https://toolkit.fluxcd.io/) - Re-written and redesigned -- `Golang`
- [Flannel](https://github.com/coreos/flannel) - Network fabric for containers via etcd, designed for Kubernetes -- `Golang`
- [Gangway](https://github.com/heptiolabs/gangway) - Enable authentication flows via OIDC (OpenID Connect Tokens) for a Kubernetes cluster -- `Golang`
- [Gatekeeper](https://github.com/open-policy-agent/gatekeeper) - Gatekeeper is a validating webhook that enforces CRD-based policies executed by Open Policy Agent -- `Golang`
- [Gitkube](https://gitkube.sh/) - Build and deploy docker images to Kubernetes using git push -- `various lang`
- [Gloo](https://github.com/solo-io/gloo) - Gateway / abstraction layer between upstream services, based off of Envoy -- `Golang`
- [Goldilocks](https://github.com/FairwindsOps/goldilocks) - Helps you identify a starting point for resource requests and limits -- `Golang`
- [gravity](https://github.com/gravitational/gravity) - Creates snapshots of a Kubernetes cluster that can be restored elsewhere (on-prem, DR situation, etc) -- `Golang`
- [Helm](https://github.com/kubernetes/helm) - tool for managing Kubernetes charts (packages of pre-configured Kubernetes resources) -- `Golang`
- [Heptio Sonobuoy](https://github.com/heptio/sonobuoy) - Kubernetes end to end conformance testing and debugging tool -- `Golang`
- [Istio](https://istio.io) - Envoy + auth, policy enforcement, telemetry, traffic flow management etc control plane that runs on top of Mesos and Kubernetes, service mesh control plane -- `various lang`
- [Istio Operator](https://github.com/banzaicloud/istio-operator/) - An operator that manages Istio deployments on Kubernetes, by Banzai Cloud -- `Golang`
- [Jenkins Kubernetes Plugin](https://wiki.jenkins.io/display/JENKINS/Kubernetes+Plugin) - Use a Kubernetes cluster to dynamically provision a Jenkins agent (using Kubernetes scheduling mechanisms to optimize the loads), run a single build, then tear-down that agent -- `Java`
- [Jenkins X](https://jenkins-x.io/) - Another Kubernetes deployer -- `various lang`
- [k3s](https://k3s.io/) - Lighweight Kubernetes in a 40mb binary, built for the edge or laptop or Pi, by Rancher -- `Golang`
- [k8spurger](https://github.com/yogeshkk/k8spurger) - Delete unused resources in your cluster, default mode is dry run -- `Python`
- [kaniko](https://github.com/GoogleContainerTools/kaniko) - Build container images from a Dockerfile, inside a container or Kubernetes cluster -- `Golang`
- [kaim](https://github.com/uswitch/kiam) - Integrate AWS IAM with Kubernetes, associate IAM roles with pods -- `Golang`
- [Keda](https://keda.sh/) - The best autoscaler for k8s -- `Golang`
- [Keel](https://keel.sh) - Stateless, automated Kubernetes deployment updates -- `Golang`
- [Kind](https://kind.sigs.k8s.io/) - Run local Kubernetes clusters using Docker container “nodes", great for local development -- `Golang`
- [kops](https://github.com/kubernetes/kops) - CLI for managing, upgrading, maintaining, and creating Kubernetes clusters on AWS -- `Golang`
- [kubepug](https://github.com/rikatz/kubepug) - Kubernetes PreUpGrade (Checker) -- `Golang`
- [kube-applier](https://github.com/box/kube-applier) - service that enables continuous deployment of Kubernetes objects by applying declarative configuration files from a Git repository to a Kubernetes cluster -- `Golang`
- [kube-bench](https://github.com/aquasecurity/kube-bench) - Compliance checker for Kubernetes CIS benchmarks -- `Golang`
- [kube-hunter](https://github.com/aquasecurity/kube-hunter) - Hunt for security weaknesses in Kubernetes clusters -- `Python`
- [kube-prometheus](https://github.com/coreos/kube-prometheus) - Use Prometheus to monitor Kubernetes and applications running on Kubernetes -- `Golang`
- [kube-secrets-init](https://github.com/doitintl/kube-secrets-init) - Kubernetes mutating webhook for `secrets-init` injection -- `Golang`
- [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) - It is not focused on the health of the individual Kubernetes components, but rather on the health of the various objects inside, such as deployments, nodes and pods -- `Golang`
- [kube2iam](https://github.com/jtblin/kube2iam) - Provide IAM credentials to containers running inside a kubernetes cluster based on annotations -- `Golang`
- [kube2pulumi](https://www.pulumi.com/kube2pulumi/) - k8s yaml in, language of your choice out -- `Python`
- [Kubecost](https://github.com/kubecost/cost-model) - Creates cost future and past models so you can see and predict your spend -- `Golang`
- [kubectl-debug](https://github.com/aylei/kubectl-debug) - Debug your pod via a new container with every troubleshooting tools pre-installed -- `Golang`
- [kubectx](https://github.com/ahmetb/kubectx) - Easily switch between kubectl contexts and namespaces, also includes the kubens tool -- `Ruby`
- [kubed](https://github.com/appscode/kubed) - Perform periodic cluster snapshots, provide temp storage for deleted objects, automatic event forwarding, deliver notifications via various channels for Kubernetes -- `Golang`
- [KubeEdge](https://github.com/kubeedge/kubeedge) - CNCF project to run Kubernetes at edge -- `Golang`
- [KubeLinter](https://github.com/stackrox/kube-linter) - Supports k8s and Helm -- `Golang`
- [Kubernetes](https://kubernetes.io/) - Open source orchestration system for Docker containers, by Google -- `Golang`
- [kubernetes-cloudflare-sync](https://github.com/calebdoxsey/kubernetes-cloudflare-sync) - Run in your Kubernetes Cluster on GKE and sync DNS records on Cloudflare with your nodes IPs to avoid GCP LB fees -- `Golang`
- [kubernetes-deploy](https://github.com/Shopify/kubernetes-deploy) - tool that helps you ship changes to a Kubernetes namespace and understand the result, by Shopify -- `Ruby`
- [kubernetes-event-exporter](https://github.com/opsgenie/kubernetes-event-exporter) - Exports missed events, there are tons you don't know about -- `Golang`
- [kubernetes-external-secrets](https://github.com/external-secrets/kubernetes-external-secrets) - CRD to pull secrets from AWS Secrets Manager, AWS System Manager, Hashicorp Vault, Azure Key Vault, and Google Secret Manager -- `Golang`
- [Kubernetes IN Docker (KinD)](https://github.com/kubernetes-sigs/kind) - Tool for running local Kubernetes clusters using Docker container "nodes" -- `Golang`
- [Kubernetes Job/CronJob Notifier](https://github.com/sukeesh/k8s-job-notify) - Puts a message into Slack -- `Golang`
- [Kubernetes Network Policy Recipes](https://github.com/ahmetb/kubernetes-network-policy-recipes) - Example recipes for Kubernetes Network Policies that you can just copy paste -- `collection`
- [kubewatch](https://github.com/bitnami-labs/kubewatch) - Kubernetes event watcher and handler (currently only publishes to Slack channels, integrations wanted!) -- `Golang`
- [Kube Forwarder](https://kube-forwarder.pixelpoint.io/) - GUI Kubernetes port forwarding manager -- `JavaScript`
- [kustomize](https://github.com/kubernetes-sigs/kustomize) - The preferred templating tool, now built-in to kubectl, official -- `Golang`
- [Kyverno](https://kyverno.io/) - Policy engine for Kubernetes -- `Golang`
- [Lens](https://k8slens.dev/) - An IDE for Kubernetes -- `various lang`
- [linkerd2](https://github.com/linkerd/linkerd2) - The project formerly known as Conduit has been merged into this, a simpler altnernative to Istio if you only need a service mesh -- `Golang`
- [Lokomotive](https://github.com/kinvolk/lokomotive) - Kubernetes distribution with baked in multi-cloud and Terraform support, by Kinvolk -- `various lang`
- [MetalKube](https://github.com/metal3-io) - Bare metal provisioning for Kubernetes, by Red Hat -- `Golang`
- [MetalLB](https://github.com/google/metallb) - Load balancer for bare metal Kubernetes clusters, by Google -- `Golang`
- [Microk8s](https://microk8s.io/) - Alternative to minikube, by Canonical -- `shell`
- [minikube](https://kubernetes.io/docs/getting-started-guides/minikube/) - Kubernetes environments on your laptop -- `Golang`
- [missing-container-metrics](https://github.com/draganm/missing-container-metrics) - Exports container exit code, OOM kill status and number of restarts to Prometheus -- `Golang`
- [MKIT (Managed Kubernetes Inspection Tool)](https://github.com/darkbitio/mkit) - A quick way to assess several common misconfigurations in their Kubernetes environment (AKS, EKS, GKE) -- `Dockerfile`
- [Octant](https://octant.dev/) - Web based representation of a Kubernetes cluster, by VMware -- `various lang`
- [Open Cluster Management](https://github.com/open-cluster-management) - The upstream for Red Hat Advanced Cluster Management, OpenShift-centric -- `various lang`
- [Pixie](https://pixielabs.ai/) - Instant visibility by giving access to metrics, events, traces and logs without changing code (DaemonSets + eBPF) -- `Golang`
- [Prometheus Operator](https://github.com/coreos/prometheus-operator) - Creates/configures/manages Prometheus clusters atop Kubernetes -- `Golang`
- [pv-migrate](https://github.com/utkuozdemir/pv-migrate) - Tool for migrating PVCs -- `Golang`
- [Reloader](https://github.com/stakater/Reloader) - Reloader can watch changes in ConfigMap and Secret and do rolling upgrades on Pods -- `Golang`
- [Rook](https://rook.io/) - Self managing, self healing storage orchestrator for Kubernetes via an operator plugin, see also EdgeFS -- `Golang`
- [shell-operator](https://github.com/flant/shell-operator) - Integration layer between Kubernetes cluster events and shell scripts by treating scripts as hooks triggered by events -- `Golang`
- [skaffold](https://github.com/GoogleCloudPlatform/skaffold) - Easy and repeatable Kubernetes development, test locally then push to a cluster, by Google -- `Golang`
- [Sloop](https://github.com/salesforce/sloop) - Monitors Kubernetes, recording histories of events and resource state changes and providing visualizations to aid in debugging past events, by Salesforce -- `Golang`
- [Squash](https://github.com/solo-io/squash) - Debug applications from your terminal or IDE while they run in Kubernetes or OpenShift (locally or remotely) -- `Golang`
- [SuperGloo](https://github.com/solo-io/service-mesh-hub) - Service mesh management and orchtestration -- `Golang`
- [Telepresense](https://www.telepresence.io/) - Local development against a remote Kubernetes or OpenShift cluster -- `Python`
- [Teleport](https://gravitational.com/teleport/) - Auditing bastion host & middleman, now supports the Kubernetes apifserver protocol -- `Golang`
- [Typhoon](https://typhoon.psdn.io/) - Minimal and free Kubernetes distro, great for testing and learning on small systems -- `various lang`
- [Wormhole](https://github.com/gravitational/wormhole) - CNI plugin for Kubernetes that uses WireGuard for creating a full mesh encrypted network between each host in the Kubernetes cluster. The Kubernetes API is used to coordinate key exchange and configuration -- `Golang`
- [Vault Secrets Operator](https://github.com/ricoberger/vault-secrets-operator) - Kubernetes operator for Hashicorp Vault -- `Golang`
- [vcluster](https://www.vcluster.com/) - Virtual Kubernetes clusters - Each vcluster runs inside a namespace of the underlying k8s cluster. It's cheaper than creating separate full-blown clusters and it offers better multi-tenancy and isolation than regular namespaces -- `Golang`
- [Velero](https://github.com/heptio/velero) - Manage disaster recovery for your Kubernetes persistent volumes and cluster resources, formerly Heptio Ark -- `Golang`
- [version-checker](https://github.com/jetstack/version-checker) - Check image versions running in the cluster vs the newest and then alert via Prometheus when newer ones are available for evaluation -- `Golang`
- [virtual-kublet](https://github.com/virtual-kubelet/virtual-kubelet) - kublet implementation that masquerades as a kubelet for the purposes of connecting Kubernetes to other APIs (Fargate, ACI, IoT, Nomad, Azure, etc) -- `Golang`
- [Voyager](https://github.com/appscode/voyager) - HAProxy backed secure L7 and L4 ingress controller for Kubernetes -- `Golang`

---

## Live CD Tools

> Security, recovery, bootable USB/CD/DVD creation tools, diagnostics, and more - see also [Security Tools](#security-tools) and [Backups](#backups) and [Provisioning Tools](#provisioning-tools)

- [BlackArch Linux](https://blackarch.org/) - Penetration testing Linux distro, based off of Arch Linux -- `various lang`
- [CAINE (Computer Aided INvestigative Environment)](https://www.caine-live.net/) - Computer forensics on a live CD -- `various lang`
- [DBAN (Darik's Boot and Nuke)](https://www.dban.org/) - Spinning disk wiper -- `various lang`
- [Easy2Boot](http://www.easy2boot.com/) - Create multiple bootable Linux ISOs on the same USB drive -- `Windows`
- [GParted Live](https://gparted.org/livecd.php) - Small, bootable ISO that contains gparted - great for resizing a non-LVM root file system -- `C`
- [Hiren's Boot CD](https://www.hirensbootcd.org/download/) - Re-adding, updated after 6 long years -- `closed source`
- [Kali Linux](https://www.kali.org/) - Penetration testing Linux distro -- `various lang`
- [Network Security Toolkit (NST)](https://networksecuritytoolkit.org/nst/index.html) - Live CD that includes most tools in insecure.org's top 125 tools list -- `various lang`
- [NirLauncher](https://launcher.nirsoft.net/) - USB live distro that contains [all of the NirSoft utilities](https://launcher.nirsoft.net/utilities_list.html) and more, essential for Windows -- `closed source` `Windows`
- [PALADIN](https://sumuri.com/software/paladin/) - Easy to use Linux-based live CD for forensic analysis -- `various lang`
- [Rufus](https://rufus.akeo.ie/) - Create bootable USB flash drives -- `Windows`
- [Security Onion](https://securityonion.net/) - Linux distro for IDS, NSM, and log management -- `various lang`
- [Stresslinux](https://www.stresslinux.org/sl/) - Hardware burn-in and stress testing -- `various lang`
- [System Rescue CD](https://www.sysresccd.org/) - System recovery CD that focuses on Linux system recovery -- `various lang`
- [Tails](https://tails.boum.org/) - Aims at preserving your privacy and anonymity via Tor -- `various lang`
- [Ultimate Boot CD (UBCD)](https://www.ultimatebootcd.com) - Tons of x86 diagnostic and stress test tools on a single CD -- `closed source` `Windows`
- [UNetbootin](https://unetbootin.github.io/) - Create custom, bootable USB Linux CDs -- `Windows` `OS X`
- [YUMI](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/) - Multiboot USB creator, Linux and -- `Windows`

---

## Logging

> Log management, analysis, analytics, and collection from any source - see also [Data Visualization and Dashboards](#data-visualization-and-dashboards) and [Metrics and Time Series Data](#metrics-and-time-series-data) and [Monitoring and Alerting](#monitoring-and-alerting)

- [Adiscon LogAnalyzer](http://loganalyzer.adiscon.com/) - Slick web interface for syslog messages -- `PHP`
- [Countly](https://count.ly/) - Mobile and web analytics and marketing platform -- `JavaScript`
- [Elastalert](https://github.com/Yelp/elastalert) - Send alerts based on ElasticSearch logs (http 500 increase/spike, any custom string, etc) -- `Python`
- [ElasticDump](https://github.com/taskrabbit/elasticsearch-dump) - Import / export tools for Elasticsearch -- `JavaScript`
- [ElasticHQ](https://github.com/royrusso/elasticsearch-HQ) - Does not yet support ES 5.x -- `JavaScript`
- [Elasticsearch Exporter](https://github.com/mallocator/Elasticsearch-Exporter) - Script to import/export data from ElasticSearch to various other storage systems -- `JavaScript`
- [Errbit](https://github.com/errbit/errbit) - Self-hosted error catcher, Airbrake API compliant -- `Ruby`
- [Filebeat](https://www.elastic.co/products/beats/filebeat) - By Elastic, the next generation Logstash Forwarder -- `Golang`
- [fluentbit](https://github.com/fluent/fluent-bit) - Fast and lightweight log processor, part of the fluentd family -- `C`
- [Fluentd](https://www.fluentd.org/) - Unified logging layer, often used with Kubernetes / OpenShift / containers -- `Ruby gem`
- [Flume](https://flume.apache.org/) - Distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data -- `Java`
- [GoAccess](https://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal and/or dashboard -- `Windows` `OS X`
- [Graylog2](https://graylog.org/) - Log capture and analysis -- `various lang`
- [lnav](https://lnav.org/) - Advanced log file viewer for the small-scale, terminal/ncurses based -- `C++`
- [Log Courier](https://github.com/driskell/log-courier) - Enhanced fork of Logstash Forwarder -- `Ruby`
- [Logagent](https://github.com/sematext/logagent-js) - Lightweight log shipper, like Filebeat and Logstash in one without the JVM footprint -- `JavaScript`
- [Logplex](https://github.com/heroku/logplex) - Distributed syslog log router, uses Redis, by Heroku -- `Erlang`
- [logstash](https://www.elastic.co/products/logstash) - Collect, parse, and store logs. A component of the popular ELK stack -- `Ruby`
- [Logster](https://github.com/etsy/logster) - Utility for reading log files and generating metrics to configurable outputs by Etsy -- `Python`
- [Logwatch](https://sourceforge.net/projects/logwatch/) - Monitor logs and send an e-mail when event(s) occur -- `perl`
- [Mamomo](https://matomo.org/) - Web analytics platform with a killer UI, formerly PIWIK -- `PHP`
- [multilog](https://cr.yp.to/daemontools/multilog.html) - Reads a sequence of lines from stdin and appends selected lines to any number of logs -- `DJB`
- [multitail](https://www.vanheusden.com/multitail/) - Monitor multiple log files in a single terminal window -- `C`
- [netconsole](https://wiki.archlinux.org/index.php/Netconsole) - Kernel module that sends kernel log messages (dmesg, etc) to a remote system without using syslog -- `C`
- [NXLOG](https://nxlog.co/products/nxlog-community-edition) - Universal log collector and forwarder, supports many formats/platforms/sources including Windows -- `C` `Windows`
- [OpenSearch](https://github.com/opensearch-project/OpenSearch) - Derived from Elasticsearch 7.10.2, Apache 2.0 license, by Amazon - `Java`
- [Open Distro for ElasticSearch](https://opendistro.github.io/for-elasticsearch/) - Distro of ElasticSearch with all of the enterprise-grade features added in -- `Java`
- [Open Web Analytics (OWA)](http://www.openwebanalytics.com/) - Track and analyze how people use your websites and applications -- `PHP`
- [Promtail](https://grafana.com/docs/loki/latest/clients/promtail/) - Log shipper for Loki users -- `Golang`
- [Sentry](https://sentry.io) - Application exception logging -- `Python`
- [Snoopy Logger](https://github.com/a2o/snoopy) - Logs commands that are executed and saves the information to syslog -- `C`
- [Snowplow](https://github.com/snowplow/snowplow) - Web, mobile and event analytics -- `Scala`
- [swatch](https://linux.die.net/man/1/swatch) - Simple log watcher -- `built-in`

---

## Metrics and Time Series Data

> Collection, analysis, and storage of metrics, telemetry, and instrumentation data from almost any source - see also [Dashboards and Data Visualization](#dashboards-and-data-visualization) and [Monitoring and Alerting](#monitoring-and-alerting) and [Logging](#logging)

- [collectd](https://collectd.org/) - Collects system performance statistics -- `C`
- [collectd Related Sites](https://collectd.org/related.shtml) - Great tools that integrate with collectd -- `collection`
- [collectl](http://collectl.sourceforge.net/) - sar on steroids -- `C`
- [Cortex](https://github.com/weaveworks/cortex) - Multitenant, horizontally scalable Prometheus as a Service -- `Golang`
- [Diamond](https://github.com/python-diamond/Diamond) - Python daemon that collects system metrics and publishes them to Graphite (or similar), has an API -- `Python`
- [dim_STAT](http://dimitrik.free.fr/) - Collects almost everything and stores it in a MySQL database, produces reports too -- `C`
- [FastForward](https://github.com/spotify/ffwd) - Flexible system event and metric forwarding agent by Spotify -- `Ruby gem`
- [Ganglia](http://ganglia.info/) - Focused on HPC / distributed clusters, uses RRD -- `various lang`
- [Graphite](https://github.com/graphite-project/graphite-web) - Store numeric time-series data and render graphs of the data on demand -- `Python`
- [Graphite Tools](https://graphite.readthedocs.org/en/latest/tools.html) - Tools that work with Graphite -- `collection`
- [Heka / hekad](https://hekad.readthedocs.org/en/latest/) - Stream processing, can gather logs or performance metrics, by Mozilla, based on Borgmon -- `Golang`
- [InfluxDB](https://www.influxdata.com/) - Distributed time series database with no external dependencies -- `Golang`
- [jmxtrans](https://github.com/jmxtrans/jmxtrans) - Connector between speaking to a JVM via JMX and whatever stats / TSDB you use -- `Java`
- [KairosDB](https://github.com/kairosdb/kairosdb) - Time series DB written on top of Cassandra -- `Java`
- [m3](https://github.com/m3db/m3) - Distributed TSDB and query dngine, Prometheus sidecar and metrics platform by Uber -- `Golang`
- [Metricbeat](https://github.com/elastic/beats/tree/master/metricbeat) - fetches a set of metrics on a predefined interval from OS & services and ships them to Elasticsearch or Logstash -- `Golang`
- [Metrics](https://github.com/dropwizard/metrics) - Metrics and instrumentation at both the JVM and application level -- `Java`
- [Micrometer](https://micrometer.io/) - Provides a simple facade (fake interface) over the instrumentation clients for the most popular monitoring systems, allowing you to instrument your JVM-based application code without vendor lock-in -- `Java`
- [mtail](https://github.com/google/mtail) - Extract monitoring data from application logs for collection into a timeseries database, by Google -- `Golang`
- [OpenTSDB](http://opentsdb.net/) - Store and serve massive amounts of time series data without losing granularity -- `Java`
- [Prometheus](https://prometheus.io/) - Metrics collection and storage, can trigger alerts when thresholds are breached, based on Borgmon -- `Golang`
- [prometheus-am-executor](https://github.com/imgix/prometheus-am-executor) - HTTP server that receives alerts from the Prometheus Alertmanager and executes a given command with alert details set as environment variables -- `Golang`
- [Sensu Go](https://sensuapp.org/) - Open source monitoring framework, cloud-focused, dynamic, scalable - also does metrics collection -- `Ruby`
- [SNMPcollector](https://github.com/toni-moreno/snmpcollector) - SNMP collector that saves into InfluxDB for easy visualization -- `Golang` `JavaScript`
- [SNMP MIB Archive](https://github.com/hs-cx/snmp_mib_archive) - Massive archive of SMMP MIBs, please fork and contribute -- `collection`
- [StatsD](https://github.com/etsy/statsd/) - Network daemon that listens for stats/counters/metrics and sends them to backend services (TSDB, Graphite, etc), by Etsy -- `JavaScript`
- [Telegraf](https://github.com/influxdata/telegraf) - Agent for collecting, processing, aggregating, and writing metrics -- `Golang`
- [Thanos](https://github.com/improbable-eng/thanos) - Highly available Prometheus setup with long term storage capabilities -- `Golang`
- [TimescaleDB](https://github.com/timescale/timescaledb) - PostgreSQL extension for time series ingestion and queries via SQL -- `C`
- [Whisper](https://github.com/graphite-project/whisper) - Store time series info in regular file system files, a modern RRD -- `Python`

---

## Monitoring and Alerting

> Monitor stuff, send alerts, wake you up - see also [Metrics and Time Series Data](#metrics-and-time-series-data) and [Logging](#logging) and [Data Visualization and Dashboards](#data-visualization-and-dashboards)

- [Adagios](http://adagios.org/) - Web based Nagios configuration interface -- `HTML`
- [Alerta](https://alerta.io/) - Distributed and de-coupled, requires MongoDB -- `Python`
- [Bosun](https://bosun.org/) - Monitoring and alerting system written by Stack Exchange, based on Borgmon -- `Golang`
- [Cabot](https://github.com/arachnys/cabot) - Self-hosted, easily-deployable monitoring and alerts service - like a lightweight PagerDuty -- `Python`
- [check_mk](https://checkmk.com/) - New Open Monitoring Distro, extensions / plugins for Nagios -- `C`
- [Daemon Tools](https://cr.yp.to/daemontools.html) - Service monitoring and management tools -- `DJB`
- [FastForward (ffwd)](https://github.com/spotify/ffwd) - Flexible system event and metric forwarding agent by Spotify -- `Ruby gem`
- [health](https://github.com/dimiro1/health) - An easy to use, extensible health check library for Go applications -- `Golang`
- [Icinga](https://www.icinga.org/) - Nagios fork, updated frequently -- `various lang`
- [Icinga2](https://github.com/Icinga/icinga2) - Complete re-write of Icinga by the same folks -- `various lang`
- [LibreNMS](https://www.librenms.org/) - GPL fork of Observium -- `various lang`
- [Monit](https://mmonit.com/monit/) - Includes tools to automatically take action when certain conditions are met (eg: restart a process when it dies) -- `C`
- [Monitorix](https://www.monitorix.org/) - So lightweight that it can be used in mobile devices, aka Mikaku -- `perl`
- [Naemon](https://www.naemon.org/) - Modular Nagios fork -- `various lang`
- [Nagios](https://www.nagios.org/) - One of the most widely used OSS monitoring programs -- `various lang`
- [Nagios Exchange](https://exchange.nagios.org/) - Centralized repository of Nagios plugins, addons, extensions, etc -- `collection`
- [NetXMS](https://www.netxms.org/) - Monitoring for all types of devices across the entire data center (hosts + network devices) -- `C`
- [OpenNMS](https://www.opennms.org/) - Network monitoring, also supports configuration/asset management -- `various lang`
- [pmacct](http://www.pmacct.net/) - IP and network traffic accounting / monitoring -- `C`
- [PHP Server Monitor](http://www.phpservermonitor.org/) - Simple monitoring package that can use built-in public SMS gateways for notifications -- `PHP`
- [PRTG](https://www.paessler.com/prtg) - Commercial version of Nagios, AD integration, many plugins, excellent price, highly recommended -- `C`
- [Pynag](https://pypi.python.org/pypi/pynag) - Interface with Nagios via Python -- `Python pip`
- [Sensu Go](https://sensuapp.org/) - Open source monitoring framework, cloud-focused, dynamic, scalable - also does metrics collection -- `Ruby`
- [Sensu Plugins](https://github.com/sensu-plugins) - Official community site for Sensu plugins -- `various lang`
- [Shinken](http://www.shinken-monitoring.org/) - Nagios-compatible monitoring, supports high availability -- `Python`
- [SigNoz](https://github.com/SigNoz/signoz) - OSS alternative to New Relic and DataDog -- `Golang`
- [Statping](https://github.com/statping/statping) - THE BEST simple all in one monitoring solution, with mobile app, great for home/small networks -- `OMG`
- [Uptime](https://github.com/fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Twitter Bootstrap -- `JavaScript`
- [Xymon](https://www.xymon.com/) - Fork of Big Brother -- `C`
- [Zabbix](https://www.zabbix.com/) - Stores monitoring data in a DB, has agents for almost every OS, can be a virtual appliance -- `various lang`
- [Zenoss Core](https://www.zenoss.com/get-started) - Supports Nagios plug-in format, based on the Zope application server -- `Python`

---

## Networking Tools

> Hodge-podge of network tools - see also [Security Tools](#security-tools) and [Network Performance Analysis Tools](#network-performance-analysis-tools) and [Orchestration](#orchestration) for parallel SSH tools

- [2ping](https://www.finnie.org/software/2ping/) - Simple bi-directional ping utility, helps determine where packet loss occurs -- `Python`
- [aria2](https://aria2.github.io/) - CLI for downloading HTTP/HTTPS, FTP, SFTP, BitTorrent and Metalink -- `C` `Windows` `OS X`
- [ARIN WHOIS in JSON](http://irrexplorer.nlnog.net/static/dumps/arin-whois-originas.json.bz2) - Authoratative (official) info including CIDR and OriginAS, updated every 8h -- `collection`
- [arp-scan](https://linux.die.net/man/1/arp-scan) - Create and send ARP requests -- `C`
- [Awesome PCAP](https://github.com/caesar0301/awesome-pcaptools) - Huge list of tools that work with PCAP captures -- `collection`
- [bbcp](http://www.slac.stanford.edu/~abh/bbcp/) - Copies files using multiple TCP streams to greatly increase throughput -- `C`
- [BIRD Internet Routing Daemon (BIRD)](http://bird.network.cz/) - (Almost) fully functional IP routing daemon for Linux, supports tons of standard routing protocols -- `C`
- [BPF Tools](https://github.com/cloudflare/bpftools) - BSD Packet Filter (BPF) and pcap toolkit, by CloudFlare -- `Python`
- [CERT NetSA Security Suite](https://tools.netsa.cert.org/) - Network flow analysis tools -- `various lang`
- [Cyberduck](https://cyberduck.io/) - GUI FTP, SFTP, WebDAV, S3 & OpenStack Swift browser for Mac and Windows -- `itsaduck`
- [Data Plane Development Kit (DPDK)](http://dpdk.org/) - Data plane libraries and framework for fast packet processing -- `C`
- [dsniff](https://www.monkey.org/~dugsong/dsniff/) - Great for level 2 analysis or service spoofing -- `C`
- [ElastiFlow](https://github.com/robcowart/elastiflow) - Netflow collection and visualization using the ELK stack -- `various lang`
- [ExaBGP](https://github.com/Exa-Networks/exabgp) - The BGP swiss army knife of networking -- `Python pip`
- [Fast Data Transfer (FDT)](https://github.com/fast-data-transfer/fdt) - For writing at disk speed over WANs -- `Java`
- [FBOSS (FaceBook Open Switching System)](https://github.com/facebook/fboss) - FB's software stack for managing and controlling their internal switches -- `various lang`
- [FreeZTP (Zero Touch Provisioning)](https://github.com/PackeTsar/freeztp) - A Zero-Touch Provisioning system built for Cisco IOS -- `Python`
- [FRRouting](https://frrouting.org/) - Replacement for / fork of Quagga with more features -- `C`
- [ftptop](https://linux.die.net/man/1/ftptop) - Monitor FTP connections in real time -- `built-in`
- [Gas Mask](https://github.com/2ndalpha/gasmask) - Simple hosts file manager for Mac OS X, switch between host files easily -- `Objective C`
- [kcptun](https://github.com/xtaci/kcptun) - Secure and fast tunnel based on KCP -- `Golang`
- [ipcalc](https://linux.die.net/man/1/ipcalc) - CLI tool to calculate subnets, netmasks, IP ranges, broadcast addresses, and more -- `built-in`
- [iptstate](https://linux.die.net/man/8/iptstate) - A top-like display of IP Tables state table entries -- `built-in`
- [GridFTP](https://fasterdata.es.net/data-transfer-tools/gridftp/) - Supports parallel streams, optimized for WANs, part of the Globus Toolkit -- `C`
- [hosts](https://github.com/StevenBlack/hosts) - Consolidates several reputable hosts files and merges them into a unified hosts file with duplicates removed (ads, malware, gambling, porn, etc) -- `collection`
- [hping3](https://linux.die.net/man/8/hping3) - Create custom TCP/IP packets, very flexible -- `built-in`
- [joincap](https://github.com/assafmo/joincap) - Alternative to mergecap -- `Golang`
- [lftp](http://lftp.yar.ru/) - Supports many protocols (FTPS, HTTPS, SFTP), scheduling, bandwidth throttling, scripting, and more - feature-rich -- `C` `C++`
- [lldpd](https://github.com/vincentbernat/lldpd) - Daemon that can talk LLDP aka the open version of Cisco Discovery Protocol (CDP), handy for network + host mapping -- `C`
- [Manito Networks Flow Analyzer](https://gitlab.com/thart/flowanalyzer) - ELK stack netflow analyzer -- `Python`
- [moloch](https://github.com/aol/moloch) - Large scale IPv4 full PCAP capturing, indexing and database system -- `JavaScript`
- [mrsync (multicast remote sync)](https://sourceforge.net/projects/mrsync/) - Transfers from a master to many remote machines using Unix multicast sockets -- `C`
- [mTCP](http://shader.kaist.edu/mtcp/) - High-performance user-level TCP stack for multicore systems -- `C`
- [Multipath TCP Checker](http://amiusingmptcp.de/) - Multipath TCP client tester -- `in-browser`
- [My Looking Glass (myLG)](https://github.com/mehrdadrad/mylg) - All-in-one CLI network diagnostic tool -- `Golang`
- [NAPALM (Network Automation and Programmability Abstraction Layer with Multivendor support)](https://github.com/napalm-automation/napalm) -- Network automation and programmability abstraction layer, for both setting config and config validation -- `Python pip`
- [ncat](https://nmap.org/ncat/) - Improved netcat, written by the Nmap team -- `C`
- [Netconf](https://github.com/v1tal3/netconfig) - Web-based GUI for configuring API-less Cisco devices -- `Python`
- [netsniff-ng](http://netsniff-ng.org/) - High performance, zero-copy networking sniffer -- `C`
- [NETworkManager](https://github.com/BornToBeRoot/NETworkManager) - All in one network GUI (config, troubleshooting, etc), neat! -- `C Sharp`
- [ngrep](https://linux.die.net/man/8/ngrep) - Network grep -- `C` `built-in`
- [Nornir](https://github.com/nornir-automation/nornir) - Python automation framework without a DSL, alternative to managing network devices with Ansible -- `Python`
- [nping](https://nmap.org/nping/) - Create custom network packets -- `C`
- [OpenBGPD](http://www.openbgpd.org/) - Free implementation of BGP v4 -- `C`
- [OpenBMP](https://github.com/openbmp) - BGP Monitoring Protocol collector with real-time monitoring, looking glass, analytics, etc -- `various lang`
- [OpenOnload](http://openonload.org/) - User-land network stack that requires no modifications to applications to use by intercepting calls -- `C`
- [OpenWRT](https://openwrt.org/) - Full Linux distro for consumer-grade routers, allows for tons of non-vendor customization -- `various lang`
- [PFQ](http://www.pfq.io/) - Framework that allows efficient packets capture/transmission, in-kernel functional processing, and packets steering across sockets/end-points -- `C`
- [PowerAdmin](http://www.poweradmin.org/) - Simple Web UI for PowerDNS -- `PHP`
- [Quagga](http://www.nongnu.org/quagga/) - Routing software suite, supports most routing protocols -- `C`
- [SiLK (System for Internet-Level Knowledge)](https://tools.netsa.cert.org/silk/) - Tool suite supports the efficient collection, storage, and analysis of network flow data, enabling network security analysts to rapidly query large historical traffic data sets -- `C`
- [snabb](https://github.com/snabbco/snabb) - Worth seeing -- `various lang`
- [socat](http://www.dest-unreach.org/socat/) - netcat on steroids, supports serial devices -- `C`
- [sslh](http://www.rutschle.net/tech/sslh.shtml) - Protocol multiplexer, let multiple daemons listen on a single port -- `C`
- [tcpflow](https://github.com/simsong/tcpflow) - TCP demultiplexer, each flow is stored in it's own file -- `C++`
- [tcpreplay](http://tcpreplay.appneta.com/) - Capture, edit, and replay network traffic -- `C`
- [tracepath](https://linux.die.net/man/8/tracepath) - Traceroute that doesn't require root -- `C`
- [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable enterprise netflow collector with Kafka integration, by Verizon -- `Golang`
- [webterm appliance](https://www.gns3.com/marketplace/appliances/webterm) - Debian-based networking toolbox, runs in a Docker container + Firefox, by the GNS3 team -- `neat`
- [WireShark](https://www.wireshark.org/) - The classic network analyzer -- `C`
- [WireShark Tools](https://wiki.wireshark.org/Tools) - Superb list of network tools from the WireShark wiki -- `collection`
- [Zenmap](https://nmap.org/zenmap/) - Official GUI for Nmap -- `C` `Windows` `OS X`

---

## Network Performance Analysis Tools

> Load generation, benchmarking, profiling, and latency simulation tools for TCP/IP networks - see also [Web and HTTP Performance Analysis Tools](#web-and-http-performance-analysis-tools) and [Performance Analysis Tools](#performance-analysis-tools)

- [ARGUS (Audit Record Generation and Utilization System)](http://www.qosient.com/argus/) - Generates network activity reports -- `C`
- [bmon](https://github.com/tgraf/bmon/) - Console based network monitor -- `C`
- [clumsy](https://jagt.github.io/clumsy/) - Simulate poor network conditions on Windows -- `C` `Windows`
- [Comcast](https://github.com/tylertreat/Comcast) - Simulate crappy network connections -- `Golang` `OS X`
- [ESnet Fasterdata Knowledge Base](http://fasterdata.es.net/) - Provides proven, operationally sound methods for troubleshooting and solving performance issues -- `collection` `hpcwisdom`
- [EtherApe](http://etherape.sourceforge.net/) - Graphical network monitor, pretty output -- `various lang`
- [Flent](https://flent.org/) - Python wrapper to run mutliple netperf/iperf3/ping in parallel, formerly netperf-wrapper -- `Python`
- [Flowgrind](https://github.com/flowgrind/flowgrind) - Distributed TCP traffic generator -- `C`
- [iftop](http://www.ex-parrot.com/pdw/iftop/) - top for network interfaces -- `C`
- [iperf3](http://software.es.net/iperf/) - Supports tuning of various parameters related to timing, protocols, and buffers -- `C`
- [iptraf-ng](https://wiki.ipfire.org/addons/iptraf-ng/start) - Updated fork of iptraf -- `C`
- [jnettop](https://linux.die.net/man/8/jnettop) - Terminal / ncurses traffic visualizer -- `C`
- [mtr (my traceroute)](http://www.bitwizard.nl/mtr/) - Combines ping and traceroute into a single program -- `C`
- [Muxy](https://github.com/mefellows/muxy) - Muck with your system and application context layers 4-7 -- `Golang` `OS X`
- [namebench](https://github.com/google/namebench) - Hunts down the fastest DNS servers for your computer to use -- `Python` `Windows` `OS X`
- [netatop](https://www.atoptool.nl/netatop.php) - Kernel module for atop to watch and report on network packets -- `C`
- [netem](https://wiki.linuxfoundation.org/networking/netem) - Network emulator for testing variable delay, loss, duplication and re-ordering -- `C`
- [NetHogs](https://github.com/raboof/nethogs) - Displays per-process bandwidth usage -- `C` `C++`
- [Network Link Conditioner](http://nshipster.com/network-link-conditioner/) - Simulate bandwidth, latency, and packet loss, by Apple -- `closed source` `OS X`
- [nfdump](https://github.com/phaag/nfdump) - Captures network flows including sFlow, NetFlow, NetFlow v9, ipfix, etc -- `perl`
- [nicstat](https://sourceforge.net/projects/nicstat/) - vmstat for network interfaces -- `C`
- [nload](http://www.roland-riegel.de/nload/index.html) - Console application that monitors network traffic and bandwidth usage in real time, neat ASCII graphs -- `C++`
- [ntopng / ntop-ng](https://www.ntop.org/products/traffic-analysis/ntop/) - New version of the popular ntop tool -- `C`
- [netperf](https://github.com/HewlettPackard/netperf) - Network load generator, by HP -- `C`
- [Paris Traceroute](http://www.paris-traceroute.net/) - Shows proper network topology when load balancers and load-balanced routers are used -- `C`
- [Ruru](https://github.com/REANNZ/ruru) - Real-time TCP latency monitoring, utilises Intel DPDK for high speed packet processing with a Node.JS frontend for visualizing the data -- `various lang`
- [SmokePing](https://oss.oetiker.ch/smokeping/) - Network latency visualizer, written by the MRTG and RRDtool guy -- `perl`
- [ss](https://linux.die.net/man/8/ss) - Socket statistics, a modern netstat -- `built-in`
- [Stanford Linear Accelerator Center - Network Monitoring Tools](https://www.slac.stanford.edu/xorg/nmtf/nmtf-tools.html) - MASSIVE list of network monitoring tools -- `collection`
- [tc](https://linux.die.net/man/8/tc) - Built-in Linux kernel traffic control -- `built-in`
- [TCP Throughput Calculator](https://www.switch.ch/network/tools/tcp_throughput/) - See name -- `in-browser`
- [tcpdive](https://github.com/fastos/tcpdive) - TCP performance analysis tool, implemented as SystemTap scripts -- `C`
- [tcptrack](https://linux.die.net/man/1/tcptrack) - Console based connection tracker -- `built-in`
- [trickle](https://linux.die.net/man/1/trickle) - Userspace bandwidth shaper -- `built-in`
- [vnStat](http://humdi.net/vnstat/) - Console based traffic monitor, supports statistic collecting -- `C`
- [WinMTR](https://github.com/White-Tiger/WinMTR) - Windows GUI for MTR -- `C++`
- [Yconalyzer](http://yconalyzer.sourceforge.net/) - Monitor and analyze TCP connections -- `C++`

---

## Orchestration

> OS and VM level orchestration as well as parallel SSH tools - see also [Containers](#containers) and [Distributed Systems Tools](#distributed-systems-tools) for container orchestration and [Terminal Tools and SSH Clients](#terminal-tools-and-ssh-clients) for SSH clients and [SSH Tools](#ssh-tools) for misc SSH tools and [Provisioning Tools](#provisioning-tools)

- [Ansible](https://www.ansible.com) - CM and orchestration, also can do provisioning -- `Python`
- [Batou](https://batou.readthedocs.org/en/latest/) - Define and perform automated service deployments -- `Python pip`
- [Capistrano](http://capistranorb.com/) - Use Ruby to run scripts/commands and push software via SSH, uses a Rake DSL -- `Ruby gem`
- [ClusterSHISH](https://www.siftsoft.com/clustershish.html) - Cluster SSH for Windows, works with PuTTY and OpenSSH for Windows -- `closed source` `Windows`
- [ClusterSSH](https://github.com/duncs/clusterssh/) - Make a change on many servers at the same time -- `perl`
- [csshX](https://github.com/brockgr/csshx) - Cluster SSH for OS X -- `C`
- [KeyBox](https://sshkeybox.com/) - Web-based SSH console that executes commands on multiple shells simultaneously and supports terminal sharing -- `Java`
- [KeyBox-OpenShift](https://github.com/skavanagh/KeyBox-OpenShift) - KeyBox for OpenShift gears -- `Java`
- [Mass Parallel SSH (mpssh)](https://github.com/ndenev/mpssh) - Simple parallel SSH -- `C`
- [Multipass](https://github.com/CanonicalLtd/multipass) - Super light weight VM manager, easy way to get a fresh Ubuntu machine -- `C++`
- [OpenLMI (Open Linux Management Infrastructure)](http://www.openlmi.org/) - Manage, monitor, and configure servers via API calls (instead of SSH), included in RHEL 7 -- `various lang`
- [orgalorg](https://github.com/reconquest/orgalorg) - Next generation parallel SSH tool because most other major ones are no longer maintined -- `Golang`
- [parallel](https://www.gnu.org/software/parallel/) - Execute jobs in parallel using one or more computers -- `built-in`
- [parallel-ssh (pssh)](https://linux.die.net/man/1/pssh) - Parallel version of OpenSSH tools - comes with prsync, pscp, pnuke, and pslurp too -- `Python` `built-in`
- [Parallel Distributed Shell (pdsh)](https://github.com/chaos/pdsh) - Kick off many SSH sessions in parallel -- `C`
- [PyDSH](http://pydsh.sourceforge.net/) - Python Distributed Shell, parallel SSH -- `Python`
- [Rundeck](http://rundeck.org/) - Job scheduler and runbook automation, enable self-service access to existing scripts and tools -- `Groovy`
- [Salt / Saltstack](https://www.saltstack.com/) - Orchestration, server provisioning, and configuration management -- `Python`
- [Spacewalk](https://www.spacewalkproject.org/) - Remote commands/orchestration, patch management, and more - the upstream for Red Hat Satellite 5.x and earlier -- `various lang`
- [Teleport](https://gravitational.com/teleport/) - Front-end for teams, includes session capture and replay, auditing, 2FA, session sharing, and more -- `Golang`
- [tmux-cssh](https://github.com/dennishafemann/tmux-cssh) - Cluster SSH via tmux -- `shell`
- [xCAT (Extreme Cloud Administration Toolkit)](http://xcat.org/) - Complete all in one management solution (provisioning, orchestration, management, etc) supports almost every UNIX and next generation platform, by IBM -- `legit`

---

## Package Patch and Repository Tools

> Repos, RPM/APT packages, packaging guidelines, patching, and patch management - see also [Provisioning Tools](#provisioning-tools)

- [apt-dater](https://github.com/DE-IBH/apt-dater) - Simple ncurses frontend for package management via SSH, also supports yum -- `C`
- [aptly](https://www.aptly.info/) - Swiss army knife for Debian repository management, has the ability to take snapshots for easy rollback -- `C`
- [AutoPkg](https://autopkg.github.io/autopkg/) - Packaging and distribution for OS X, great for managing many laptops -- `Python` `OS X`
- [CentOS Errata for Spacewalk (CEFS)](http://cefs.steve-meier.de/) - Import errata information from CentOS-announce into Spacewalk -- `useit`
- [CentOS Repositories](https://wiki.centos.org/AdditionalResources/Repositories) - Large list of both official and unofficial CentOS software repositories -- `collection`
- [CentOS Software Collections (SCL)](https://wiki.centos.org/AdditionalResources/Repositories/SCL) - Use multiple versions of software on a system without disturbing the system default version -- `C`
- [Copr](https://pagure.io/copr/copr) - Automatic build system providing a package repository as its output, by Fedora -- `C`
- [cowbuilder](https://wiki.debian.org/cowbuilder) - Package builder that uses copy-on-write (COW) to speed up the build process -- `C`
- [DNF aka Dandified yum ](https://fedoraproject.org/wiki/Features/DNF) - yum v4 packaging system, added to upcoming Fedora/RHEL/CentOS 8 releases -- `article`
- [ELRepo](https://elrepo.org) - Repo that focuses on hardware related packages, supports RHEL and CentOS -- `repo`
- [Extra Packages for Enterprise Linux (EPEL)](https://fedoraproject.org/wiki/EPEL) - Supports CentOS, RHEL, Scientific Linux, and Oracle Linux -- `repo`
- [Extra Packaging Guidelines and Policies for EPEL](https://fedoraproject.org/wiki/EPEL/GuidelinesAndPolicies) - Packaging guidelines, great even if not creating EPEL stuff -- `readit`
- [Fedora Packaging Guidelines](https://docs.fedoraproject.org/en-US/packaging-guidelines/) - Excellent information that can be applied to CentOS & RHEL -- `readit`
- [fpm (Fucking Package Management)](https://github.com/jordansissel/fpm) - Build packages for multiple platforms (deb, rpm, etc) with great ease and sanity -- `Ruby gem`
- [fpm-cookery](https://github.com/bernd/fpm-cookery) - Tool for building software packages with FPM -- `Ruby gem`
- [Habitat](https://www.habitat.sh/) - Creates platform-independent build artifacts and provides built-in deployment and management capabilities -- `Golang`
- [Homebrew (aka brew)](https://brew.sh/) - Tons of packages for Mac -- `Ruby` `OS X`
- [Koji](https://fedoraproject.org/wiki/Koji) - Software that builds packages for Fedora, can be used for other stuff too, uses mock -- `C`
- [Mock](https://github.com/rpm-software-management/mock) - Build packages in a simple chroot so you don't blow up your system -- `C`
- [mrepo](http://dag.wiee.rs/home-made/mrepo/) - RPM repository management tool supporting ftp/http/sftp/rsync/rhn/you, formerly Yam -- `Python`
- [Munki](https://www.munki.org/munki/) - Managed software installation for OS X, great for managing laptops -- `Python` `OS X`
- [OStree](https://ostree.readthedocs.io/en/latest/) - Tool for managing bootable, immutable, versioned filesystem trees (not really a package manager but...) -- `thefuture` `C`
- [pkgr](http://crohr.me/pkgr/) - Made deb or RPM packages out of any Ruby, NodeJS, or Go app -- `Ruby`
- [Pulp](https://www.pulpproject.org/) - Next generation repository management, a component of Red Hat Satellite 6 -- `Python`
- [Red Hat Software Collections (SCL)](https://www.softwarecollections.org/) - Use multiple versions of software on a system without disturbing the system default version, use this to get the newest / latest versions of things -- `repo`
- [reposync](https://linux.die.net/man/1/reposync) - Synchronize yum repositories to a local directory -- `built-in`
- [rpm-ostree](https://github.com/projectatomic/rpm-ostree) - Hybrid image/package system with atomic upgrades and package layering -- `C` `thefuture`
- [RPM Fusion](https://rpmfusion.org/) - Provides software that the Fedora Project or Red Hat doesn't ship -- `repo`
- [schroot](https://linux.die.net/man/1/schroot) - Allow non-root users to create chroot environments, great for package testing -- `built-in`
- [Spacewalk](https://www.spacewalkproject.org/) - Patch management, remote commands, and more - the upstream for Red Hat Satellite -- `various lang`
- [Tito](https://github.com/dgoodwin/tito) - Tool for managing RPM based projects using git for their source code repository -- `Python`
- [yum-presto](https://fedoraproject.org/wiki/Features/Presto) - yum plugin that provides support for downloading package deltas -- `article`
- [yum-security](https://linux.die.net/man/8/yum-security) - Plugin to only install security updates -- `built-in`

---

## Performance Analysis Tools

> Non-specific and all-in-one performance monitoring tools - see also [web](#web-and-http-performance-analysis-tools), [network](#network-performance-analysis-tools), [storage](#storage-performance-analysis-tools), and [RDBMS](#rdbms-performance-analysis-tools) and [Tracing and Profiling](#tracing-and-profiling)

- [atop](https://www.atoptool.nl/) - Supports both real-time and historical performance monitoring -- `C`
- [bashtop](https://github.com/aristocratos/bashtop) - Real time resource monitor -- `Python`
- [Conky](https://github.com/brndnmtthws/conky) - Lightweight system monitor for X windows -- `C++`
- [Glances](https://nicolargo.github.io/glances/) - Real-time performance monitoring, written in curses and Python -- `Python`
- [hazelnut](https://github.com/mrsmn/hazelnut) - Python lib to parse /proc/meminfo -- `Python pip`
- [htop](http://hisham.hm/htop/) - top replacement, has a few additional features -- `C`
- [Linux Performance Observability Tools](http://www.brendangregg.com/Perf/linux_observability_tools.png) - Awesome graphic that shows you which tool to use, by Brendan Gregg -- `yells at drives`
- [mem_logger.sh](http://aarvik.dk/how-to-determine-which-process-is-highly-memory-consuming-over-time/) - Monitor a processes' memory usage over time -- `shell`
- [Munin](http://munin-monitoring.org/) - Historical performance monitoring to help determine when you server became "slow" -- `perl`
- [NetData](http://my-netdata.io/) - Real time performance visualization and dashboards -- `C`
- [nmon](http://nmon.sourceforge.net/pmwiki.php) - Provides both real-time and historical performance metrics -- `C`
- [NumaTOP](https://01.org/numatop) - top for NUMA systems, shows hotspots, call chains, etc -- `C`
- [PerfKit Benchmarker](https://github.com/GoogleCloudPlatform/PerfKitBenchmarker) - Open effort to define a canonical set of benchmarks to measure and compare cloud offerings (disk, network, CPU, etc) -- `various lang`
- [Phoronix Test Suite](https://www.phoronix-test-suite.com/) - Benchmarking and profiling suite, very feature-rich and versatile -- `PHP`
- [pidstat](https://linux.die.net/man/1/pidstat) - vmstat type output for CPU, disk I/O, page faults, and more on a per-process basis -- `built-in`
- [pmap](http://milianw.de/code-snippets/tracking-memory-consumption-using-pmap) - Shell scripts for tracking memory usage using "pmap" -- `shell`
- [PowerTOP](https://01.org/powertop) - Real-time power consumption on a per-process & per-thread basis, by Intel -- `C++`
- [ps_mem](https://github.com/pixelb/ps_mem) - Accurately reports core memory usage for a process -- `Python`
- [ptop](https://github.com/black-perl/ptop) - top/ntop-like task monitor written in Python -- `Python pip`
- [recap](https://github.com/rackerlabs/recap) - Collects info from various standard utilities (free, sar, vmstat, etc) at specified intervals, by Rackspace -- `various lang`
- [saidar](https://linux.die.net/man/1/saidar) - ncurses based program for viewing system statistics -- `built-in`
- [slabtop](https://www.toofishes.net/blog/linux-command-day-slabtop/) - Tutorial on how to use slabtop, useful when you have no idea on how your RAM is being used -- `article`
- [smem](https://www.selenic.com/smem/) - Reports memory usage based on proportional set size (PSS) instead of the usual resident set size (RSS) -- `C`
- [sysdig](https://www.sysdig.org/) - Linux system exploration and troubleshooting tool with first class support for containers -- `C++`
- [VMtouch](https://github.com/hoytech/vmtouch) - File system cache diagnostics and control -- `C`

---

## Provisioning Tools

> OS provisioning, image creation, installation, bootstrapping, and lifecycle management - see also [Package Patch and Repository Tools](#package=patch-and-repository-tools) and [Containers](#containers) and [Distributed Systems Tools](#distributed-systems-tools) and [Live CD Tools](#live-cd-tools)

- [Box-Cutter](https://github.com/boxcutter) - Hashicorp's community repo for Packer & Vagrant templates -- `Ruby`
- [Clonezilla](http://clonezilla.org/) - Disk image/cloning tool, supports most file system types -- `perl` `shell`
- [cloud-init](https://launchpad.net/cloud-init) - Configures settings the first time a system spins up (SSH keys, hostname, variables, etc), note NoCloud -- `C`
- [cookiecutter](https://github.com/cookiecutter/cookiecutter) - Creates projects from cookiecutters (project templates), many cookiecutters to choose from -- `Python pip`
- [Fog](https://www.fogproject.org/) - Computer / OS cloning tool, also has remote client management capabilities -- `C++`
- [Foreman](https://theforeman.org/) - Provisioning and life cycle management -- `Ruby` `Windows` `OS X`
- [iPXE](http://ipxe.org/) - GPL'ed version of PXE, official replacement for gPXE -- `C`
- [Kickstart](https://fedoraproject.org/wiki/Anaconda/Kickstart) - The classic Red Hat tool -- `various lang`
- [netboot.xyz](https://netboot.xyz/) - Simple iPXE menu and installer -- `shell`
- [Packer](https://www.packer.io/) - Automates VM creation for multiple platforms (VMware, AWS, etc) -- `Golang`
- [Vagrant](https://www.vagrantup.com/) - Quickly spin up environments for local testing and development -- `Ruby`
- [Vagrant Plugins](https://github.com/mitchellh/vagrant/wiki/Available-Vagrant-Plugins) - A list of Vagrant plugins on the official Hashicorp wiki -- `collection`
- [Vagrant Manager](http://vagrantmanager.com/) - GUI to manage Vagrant boxes -- `Windows` `OS X`
- [vagrant-cachier](http://fgrehm.viewdocs.io/vagrant-cachier/) - Cache BLOB downloads to reduce network usage -- `Ruby`
- [vagrant-host-shell](https://github.com/phinze/vagrant-host-shell) - Simple plugin to run commands on the VM when it boots (think cloud-init) -- `Ruby`
- [vagrant-hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater) - Plugin to add your own /etc/hosts to the VM -- `Ruby`
- [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) - Auto-install the latest VirtualBox tools at boot time (if necessary) -- `Ruby`
- [Salt / Saltstack](https://www.saltproject.io/) - Orchestration, server provisioning, and configuration management -- `Python`

---

## Python Tools and Resources

> Python stuff of note

- [argparse](https://docs.python.org/3/library/argparse.html) - Parser for command-line options, arguments and sub-commands -- `Python`
- [atexit](https://docs.python.org/3/library/atexit.html) - Exit handlers -- `Python`
- [Awesome Python](https://github.com/vinta/awesome-python) - Very large list of Python resources -- `collection`
- [bpython](https://bpython-interpreter.org/) - Killer interface for the Python interpreter -- `Python`
- [ciscoconfparse](https://github.com/mpenning/ciscoconfparse) - Parse, audit, query, build, and modify Cisco IOS-style configurations -- `Python pip`
- [exscript](https://github.com/knipknap/exscript) - Write less code using than either pure paramiko or netmiko -- `Python`
- [Fabric](http://www.fabfile.org/) - Uses paramiko to implement a higher-level API for performing commands over SSH, particularly for deployment sysadmin tasks -- `Python pip`
- [Faker](http://www.joke2k.net/faker/) - Generate fake data easily -- `Python pip`
- [Fire](https://pypi.org/project/fire/) - Turn any Python module, class, object, function, etc into a CLI -- `Python`
- [functools](https://docs.python.org/3/library/functools.html) - Higher-order functions and operations on callable objects -- `Python`
- [getpass](https://pymotw.com/3/getpass/) - Enter a password without echoing what they type to the console -- `Python`
- [inspect](https://docs.python.org/3/library/inspect.html) - Inspect live objects -- `Python`
- [IPython](https://ipython.org/) - Interactive Python shell and the kernel for Jupyter -- `Python`
- [Itertools](https://docs.python.org/3/library/itertools.html) - Functions creating iterators for efficient looping, iterator building blocks -- `Python`
- [Jinja2](http://jinja.pocoo.org/docs/dev/) - Templating language for Python -- `Python pip`
- [Jupyter](https://jupyter.org/) - The language-agnostic parts of IPython -- `Python`
- [Logging](https://docs.python.org/3/library/logging.html) - Flexible event logging system for applications and libraries for all modules and more -- `Python`
- [Mailer](https://pypi.org/project/mailer/) - The best e-mail module -- `Python`
- [more-itertools](https://pypi.org/project/more-itertools/) - More routines for operating on iterables, beyond itertools -- `Python pip`
- [netaddr](https://pypi.org/project/netaddr/) - A network address manipulation library for Python -- `Python`
- [netmiko](https://github.com/ktbyers/netmik) - Multi-vendor library to simplify Paramiko SSH connections to network devices -- `Python`
- [netminko_tools](https://github.com/ktbyers/netmiko_tools) - Command line tools built on Netmiko to simplify information gathering -- `Python`
- [os](https://docs.python.org/3/library/os.html) - Interact with the OS -- `Python`
- [paramiko](http://www.paramiko.org/) - SSH2 protocol library for Python, provides both client and server -- `Python pip`
- [pdb](https://docs.python.org/3/library/pdb.html) - Python debugger -- `Python`
- [pexpect](https://github.com/pexpect/pexpect) - Expect-like module -- `Python`
- [pycsco](https://github.com/jedelman8/pycsco) - Python modules to simplify the use of working with Cisco Nexus switches -- `Python`
- [PyEnv](https://github.com/pyenv/pyenv) - Simple Python version management that keeps everything within your home directory, virtualenv alternative -- `shell`
- [PyPI (Python Package Index)](https://pypi.python.org/pypi) - Software repo for Python packages, like Ruby gems or a RPM repo -- `collection`
- [PyPy](http://pypy.org/) - Python alternative with advance features (JIT compiles, sandboxing, etc) -- `Python`
- [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - Library for building interactive command lines -- `Python pip`
- [RadSSH](https://pypi.python.org/pypi/radssh) - Paramiko-based parallel SSH -- `Python pip`
- [Requests](http://docs.python-requests.org/en/latest/) - The best HTTP library -- `Python pip`
- [scapy](https://pypi.python.org/pypi/scapy) - Interactive packet manipulation for Python -- `Python pip`
- [selenium](https://pypi.org/project/selenium/) - Browser automation -- `Python`
- [sh](https://pypi.python.org/pypi/sh) - Library that allows you to call any program (shell command) as if it were a function -- `Python pip`
- [Subprocess](https://docs.python.org/3/library/subprocess.html) - Spawn subprocesse and collect their output -- `Python`
- [sys](https://docs.python.org/3/library/sys.html) - System-specific parameters and functions -- `Python`
- [tempfile](https://docs.python.org/3/library/tempfile.html) - Generate temporary files and directories -- `Python`
- [TextFSM](https://github.com/google/textfsm) - Create a pool of templates to parse text, then use TextFSM to parse useful information from a variety of sources -- `Python`
- [xlwings](https://xlwings.org/) - Replace your Excel VBA code with Python -- `Python pip`

---

## Python Programming Tutorials

> Tutorials, exercises, and challenges for learning Python. I have no idea how good/bad these are

- [500 Lines](https://github.com/aosabook/500lines) - Many full Python programs written in 500 lines or less, great for beginners
- [CheckiO](https://py.checkio.org/) - Challenges, shows all submitted solutions to a challenge and people vote for best - great way to see each POV -- `in-browser`
- [Codecademy](http://www.codecademy.com/tracks/python) - Codecademy's online Python course
- [CodingBat](http://codingbat.com/python) - Practice problems
- [Coursera](https://www.coursera.org/courses?orderby=upcoming&search=python) - Online Python courses at various institutions
- [Dive Into Python 3](http://getpython3.com/diveintopython3/) - Free ebook
- [edX](https://www.edx.org/course?search_query=python) - Python courses at edX
- [Google Python Class](https://developers.google.com/edu/python/) - By the GOOG
- [importpython's Python Book List](http://importpython.com/books/) - Includes both free and pay, ebooks and physical
- [Intermediate Python](http://book.pythontips.com/en/latest/) - Free ebook
- [Invent with Python](http://inventwithpython.com/) - Series of free ebooks, includes Automate the Boring Stuff with Python, recommended books
- [Learn Python, Break Python](http://learnpythonbreakpython.com/) - Free ebook
- [MIT Open Courseware - Introduction to Computer Science and Programming](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00sc-introduction-to-computer-science-and-programming-spring-2011/) - Focuses on Python
- [MIT Open Courseware - A Gentle Introduction to Programming Using Python](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/) - Final project is a Tetris game in Python
- [MIT Open Courseware - Objects in Python](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00sc-introduction-to-computer-science-and-programming-spring-2011/unit-1/lecture-5-objects-in-python/) - Python tuples, lists, and dictionaries, as well as the concept of mutability and how to avoid problems relating to it.
- [MIT Open Courseware - Python Tutorial](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/python-tutorial/) - Python tutorial for people familiar with basic programming concepts
- [New Coder](http://newcoder.io/tutorials/) - Python exercises
- [Online Python Tutor](http://pythontutor.com/) - 100% in-browser
- [Programming Praxis](https://programmingpraxis.com/) - Programming exercises, many posted solutions are in Python
- [Python Challenge](http://www.pythonchallenge.com/) - A riddle in Python
- [Python for Infomatcis](http://www.pythonlearn.com/book.php) - Free ebook
- [Python for You and Me](https://pymbook.readthedocs.org/en/py3/) - The 2.x version is linked on the main page
- [Python Practice Projects](http://pythonpracticeprojects.com/) - Several practice exercises
- [Python 2.x Tutorial](https://docs.python.org/2/tutorial/index.html) - For 2.x, part of the official documentation
- [Python 3.x Tutorial](https://docs.python.org/3/tutorial/index.html) - From the official documentation
- [Quiz and Learn Python](http://mobileicecube.com/quiz-learn-python/) - Designed for mobile devices
- [r/dailyprogrammer](https://www.reddit.com/r/dailyprogrammer) - Programming exercises, includes Python
- [r/learnpython](https://www.reddit.com/r/learnpython) - Subreddit for beginners, be sure to check the wiki too
- [Supporting Python 3](https://github.com/regebro/supporting-python-3) - Free ebook that focuses on porting to Python 3.x
- [Think Python: How to Think Like a Computer Scientist](http://www.greenteapress.com/thinkpython/html/index.html) - Awesome free ebook
- [Tutorials Point's Python Tutorial](https://www.tutorialspoint.com/python/index.htm) - Another one!

---

## RDBMS and SQL Tools

> Tools for interacting with and related to the major DBs and SQL

- [Adminer](https://www.adminer.org/) - GUI for database management in a single PHP, formerally phpMyAdmin -- `PHP`
- [CockroachDB](https://www.cockroachlabs.com/) - Open source version of Google's Spanner storage system -- `thefuture` `Golang`
- [DBeaver](https://dbeaver.io/) - OSS multi-platform GUI that supports almost every DB, built from Eclipse -- `Eclipse`
- [DB Browser for SQLite](http://sqlitebrowser.org/) - GUI database browser for SQLite instances -- `C++`
- [Flyway](https://flywaydb.org/) - Version control for DB schemas, supports most DBs -- `Java`
- [gh-ost](https://github.com/github/gh-ost) - Online schema migrations for MySQL, by GitHub -- `Golang`
- [HeidiSQL](https://www.heidisql.com/) - GUI SQL DB browser and editor -- `Windows` `OS X`
- [Liquibase](https://github.com/liquibase/liquibase) - Tracking, managing, and applying database schema changes, SVN for DBs -- `Java`
- [MaxScale](https://github.com/mariadb-corporation/MaxScale) - General purpose DB query proxy, router, and load balancer by MariaDB -- `C`
- [mycli](http://mycli.net/) - CLI for MySQL and derivates with auto-completion and syntax highlighting -- `Python`
- [mydumper (MySQL Data Dumper)](https://github.com/maxbube/mydumper) - Much better than mysqldump, works in parallel -- `perl`
- [MyRocks](http://myrocks.io/) - RocksDB with a MySQL front-end / interface -- `C++`
- [MySQL sys schema](https://github.com/MarkLeith/mysql-sys) - Collection of views, functions and procedures to help MySQL administrators get insight into MySQL usage -- `SQL`
- [MySQL Workbench](https://www.mysql.com/products/workbench/) - The official MySQL GUI for admins, devs, DBAs, and architects -- `various lang`
- [Oracle TPT Scripts](https://github.com/tanelpoder/tpt-oracle) - Tanel Poder's Troubleshooting & Performance Tools for Oracle Databases -- `SQL`
- [orchestrator](https://github.com/openark/orchestrator) - MySQL replication topology management and visualization tool, GUI -- `Golang`
- [Percona Toolkit for MySQL](https://www.percona.com/software/mysql-tools/percona-toolkit) - Percona's special toolkit -- `various lang`
- [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocomplete and syntax highlighting -- `Python`
- [pgloader](https://pgloader.io/) - Fast data loader for PostgreSQL -- `Lisp`
- [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL DB browser -- `Golang`
- [pg_repack](https://reorg.github.io/pg_repack/) - Remove bloat from tables and indexes without using an exclusive lock -- `C`
- [Phinx](https://phinx.org/) - Database migrations in SQL or PHP -- `PHP`
- [Postgres-XL](https://www.postgres-xl.org/) - Scale-out version of PostgresSQL -- `C`
- [Postgres.app](http://postgresapp.com/) - All-in-one version of Postgres for local testing on a laptop -- `C`
- [PostgREST](https://github.com/begriffs/postgrest) - Create a REST API for any Postgres DB -- `Haskell`
- [PostgreSQL GUI Tools](https://wiki.postgresql.org/wiki/Community_Guide_to_PostgreSQL_GUI_Tools) - A huge list on the official wiki -- `collection`
- [Presto](https://github.com/facebook/presto) - Distributed SQL query engine for big data, by Facebook -- `Java`
- [Sequel Pro](https://github.com/sequelpro/sequelpro) - MySQL management GUI for Mac -- `OS X`
- [shift](https://github.com/square/shift) - Schema migrations for MySQL, by Square -- `Ruby`
- [SQLite](https://sqlite.org/) - Self-contained, serverless, zero-configuration, transactional SQL database engine, great for testing -- `C`
- [sqlmap](http://sqlmap.org/) - Detect and exploit SQL injection flaws, pen testing tool -- `Python`
- [SQL Fiddle](http://sqlfiddle.com/) - Write and test SQL -- `in-browser`
- [wal-e](https://github.com/wal-e/wal-e) - Simple continuous archiving for PostgreSQL -- `Python`
- [wal-g](https://github.com/wal-g/wal-g) - Simple continuous archiving for PostgreSQL, successor to wal-e -- `Python`
- [WWW SQL Designer](https://github.com/ondras/wwwsqldesigner/) - Designing RDBMS schemas features saving, exporting to XML, and SQL script creation, free SaaS version [here](http://ondras.zarovi.cz/sql/demo/) -- `JavaScript`

---

## RDBMS Performance Analysis Tools

> Load generation, benchmarking, telemetry, and profiling for various RDBMS platforms - see also [Storage Performance Analysis Tools](#storage-performance-analysis-tools) and [Performance Analysis Tools](#performance-analysis-tools) and [Tracing and Profiling](#tracing-and-profiling) and [Network Performance Analysis Tools](#network-performance-analysis-tools) and [Metrics and Time Series Data](#metrics-and-time-series-data)

- [Awesome MySQL Performance](https://github.com/Releem/awesome-mysql-performance) - Collection -- `collection`
- [HammerDB](http://hammerora.sourceforge.net/) - Load testing and benchmark tool, supports most DBs -- `Tcl`
- [innotop](https://github.com/innotop/innotop) - "top" for MySQL -- NOTE: beware of exposing your password -- `perl`
- [MySQLtuner-perl](https://github.com/major/MySQLTuner-perl) - Analyzes a MySQL installation and provides suggestions to increase performance -- `perl`
- [MySQL Performance Analyzer](https://github.com/yahoo/mysql_perf_analyzer) - Open sourced by Yahoo -- `Java`
- [Open PostgreSQL Monitoring (OPM)](http://opm.io/) - Includes a web console, nice GUI -- `JavaScript`
- [Percona Toolkit for MySQL](https://www.percona.com/software/database-tools/percona-toolkit) - Percona's internal tools -- `various lang`
- [pg_activity](https://github.com/dalibo/pg_activity) - htop for PostgreSQL -- `Python`
- [pg_view](https://github.com/zalando/pg_view) - PostgreSQL monitoring, supports ncurses, console, and JSON output -- `Python pip`
- [pgBadger](https://dalibo.github.io/pgbadger/) - PostgreSQL log analyzer -- `perl`
- [PgHero](https://github.com/ankane/pghero) - A performance dashboard for Postgres - health checks, suggested indexes, and more -- `JavaScript`
- [PGObserver](https://zalando.github.io/PGObserver/) - Killer PostgreSQL monitor, includes dashboard -- `Python`
- [Silly Little Oracle Benchmark 2 (SLOB2)](https://kevinclosson.net/slob/) - Stresses and benchmarks Oracle DBs, works at the RDBMS layer -- `various lang`
- [Swingbench](http://www.dominicgiles.com/swingbench.html) - Oracle load generator -- `closed source`
- [SysBench](https://github.com/akopytov/sysbench) - Evaluates OS parameters that are important for DBs, does not require a DB to be installed -- `C`
- [Tsung](http://tsung.erlang-projects.org/) - Distributed stress tester, also supports stress testing DBs -- `Erlang`

---

## Regular Expressions

> regex checkers, creators, evaluators, debuggers, and tutorials - see also [Shell Scripting and Tools](#shell-scripting-and-tools) and [Software Development Tools](#software-development-tools)

- [Debuggex](https://www.debuggex.com/) - Online regex debugger -- `in-browser`
- [ExtendsClass](https://extendsclass.com/regex-tester.html) - Online visual regex tester -- `in-browser`
- [perlretut](http://perldoc.perl.org/perlretut.html) - perl-focused but very useful for all regex -- `article`
- [Refiddle](http://refiddle.com/) - Online, supports JavaScript, Ruby, and .NET only -- `in-browser`
- [regex101](https://regex101.com/) - Online regex tester and debugger, supports multiple languages -- `in-browser`
- [RegexOne](https://regexone.com/) - Learn regular expressions with simple, interactive examples -- `tutorial`
- [regexper](https://regexper.com/) - Regex visualizer using railroad diagrams, great for debugging -- `in-browser`
- [RegExr](https://www.regexr.com/) - Another online regex tool that includes cheat sheets, examples, and community-contributed expressions -- `collection`
- [RegularExpressions.info](https://www.regular-expressions.info/) - THE BEST regex site -- `collection`
- [Regular Expressions - A Gentle User Guide and Tutorial](http://www.zytrax.com/tech/web/regex.htm) - The easy way -- `tutorial`
- [RexV.2](http://www.rexv.org/) - Online Regex evaluator, supports multiple languages -- `in-browser`
- [Rubular](http://rubular.com/) - Online Ruby-only regex evaluator -- `in-browser`
- [txt2re](http://txt2re.com/) - Regex generator, recommended -- `in-browser`
- [txt2regex](http://aurelio.net/projects/txt2regex/) - Converts human sentences to regex, written in bash -- `shell`

---

## Secrets Management

> Password, private key, and API key storage and management tools - see also [Security Tools](#security-tools) and [SSL Tools](#ssl-tools) and [Two Factor Authentication](#two-factor-authentication) and [VPNs and Tunnels](#vpns-and-tunnels)

- [Bitwarden](https://bitwarden.com/) - The new hotness in password management -- `various lang`
- [blackbox](https://github.com/StackExchange/blackbox) - Safely store secrets in Git, by Stack Exchange -- `shell`
- [Diceware](http://world.std.com/~reinhold/diceware.html) - Neat IRL passphrase generator -- `doitirl`
- [encpass](https://github.com/plyint/encpass.sh) - Lightweight solution for using encrypted passwords in shell scripts -- `shell`
- [GPG (GNU Privacy Guard)](https://www.gnupg.org/) - The original! Store em in text files and encrypt -- `C` `pro`
- [GRC Password Generator](https://www.grc.com/passwords.htm) - Generates 63 bit passwords -- `in-browser`
- [Kee](https://www.kee.pm/) - Auto-fill website logins using KeePass as a source, like LastPass -- `C#` `Firefox`
- [Keybase](https://keybase.io/) - Upload your public key and find other people's public key via their social media user name(s) -- `in-browser`
- [KeePass](https://keepass.info/) - Lightweight, easy to use, GUI password manager, runs on most platforms -- `C#` `Windows`
- [Keepass2Android](https://github.com/PhilippC/keepass2android) - Compatible with KeePass 2.x -- `Android`
- [KeePassDroid](http://www.keepassdroid.com/) - Open source version of KeePass 1.x for Android -- `Android`
- [KeePassXC](https://keepassxc.org/) - Supports YubiKey and TOTP, forked becasue KeePassX is no longer being updated -- `C++`
- [KeeWeb](https://github.com/keeweb/keeweb) - Cross-platform password manager compatible with KeePass -- `JavaScript`
- [Keywhiz](https://square.github.io/keywhiz/) - A system for distributing and managing secrets (API keys, certificates, etc), by Square -- `Java`
- [kpcli](http://kpcli.sourceforge.net/) - Command line interface / CLI for KeePass -- `perl`
- [lastpass-cli](https://github.com/lastpass/lastpass-cli) - CLI for LastPass -- `C`
- [MacPass](https://github.com/mstarke/MacPass) - A free, open-source, KeePass-compatible password manager for macOS -- `Objective-C`
- [msktutil](https://linux.die.net/man/1/msktutil) - Keytab client for a Microsoft Active Directory environment -- `built-in`
- [One-Time Secret](https://github.com/onetimesecret/onetimesecret) - Create links that self-destruct after a single viewing, great for sharing passwords -- `Ruby`
- [pass (passwordstore)](https://www.passwordstore.org/) - Uses GPG at it's core, supports tracking password changes in git -- `shell`
- [passff](https://github.com/jvenant/passff) - Addon for interacting with the a pass aka passwordstore repository -- `Firefox`
- [Password Pusher](https://github.com/pglombardo/PasswordPusher) - Links to passwords expire after a certain number of views and/or time has passed, RoR app -- `Ruby`
- [Password Safe](https://pwsafe.org/) - Designed by Bruce Schneier himself -- `bam`
- [pwd.sh](https://github.com/drduh/pwd.sh) - Script to manage passwords in an encrypted file using GPG -- `shell`
- [pwgen](https://linux.die.net/man/1/pwgen) - Password generated, included in most Linux distros -- `built-in`
- [Secrets OPerationS (SOPS)](https://github.com/mozilla/sops) - Secrets management, by Mozilla -- `Python`
- [TeamPass](https://www.teampass.net/) - Collaborative password management using the LAMP stack -- `PHP`
- [Vault](https://www.vaultproject.io/) - Tool for storing secrets (API keys, passwords, certs, etc) by Hashicorp -- `Golang`

---

## Security Tools

> Misc security tools - see also [Live CD Tools](#live-cd-tools) and [Networking Tools](#networking-tools) and [Secrets Management](#secrets-management) and [SSL Tools](#ssl-tools) and [Two Factor Authentication](#two-factor-authentication) and [VPNs and Tunnels](#vpns-and-tunnels) and [Logging](#logging)

- [Advanced IP Scanner](https://www.advanced-ip-scanner.com/) - For Windows, recommended -- `closed source`
- [afl-fuzz (American Fuzzy Lop)](http://lcamtuf.coredump.cx/afl/) - One of the best fuzzers -- `C`
- [AIDE (Advanced Intrusion Detection Environment)](http://aide.sourceforge.net/) - File integrity checker, alternative to Tripwire -- `various lang`
- [Amass](https://github.com/OWASP/Amass) - Automatically obtains subdomain names in a variety of ways and uses that info to build maps of the target network, by OWASP -- `Golang`
- [Angry IP Scanner](http://angryip.org/) - GUI network scanner, supports plugins, -- `Java` `Windows` `OS X`
- [Armitage](http://www.fastandeasyhacking.com/) - GUI for Metasploit -- `Java`
- [asecurecloud](https://asecure.cloud/) - A free library of 400+ customizable AWS security configurations and best practices (CF, Terraform, and AWS CLI) -- `collection`
- [ATA Secure Erase](https://ata.wiki.kernel.org/index.php/ATA_Secure_Erase) - Send a signal to an ATA drive to perform a hardware-based erase, the ONLY way to wipe a SSD properly -- `article`
- [Attack Surface Analyzer 2.0](https://github.com/microsoft/AttackSurfaceAnalyzer) - See exactly what changed post-OS install or post-software install, by Microsoft -- `Windows`
- [auditd-attack](https://github.com/bfuzzy1/auditd-attack) - A Linux Auditd rule set mapped to MITRE's Attack Framework -- `collection`
- [authconv](https://github.com/authcov/authcov) - Web app authorization coverage scanning -- `JavaScript`
- [Awesome Honeypots](https://github.com/paralax/awesome-honeypots) - Curated collection of honepots and honeypot resources -- `collection`
- [bettercap](https://www.bettercap.org/) - Swiss Army knife for 802.11, BlueTooth, and Ethernet networks reconnaissance and attacks -- `Golang`
- [Brida](https://github.com/federicodotta/Brida) - Bridge between Burp Suite & Frida, lets you use and manipulate applications own methods while tampering the traffic exchanged between the applications and their back-end services/servers -- `various lang`
- [bro](https://github.com/bro/bro) - Framework for network analysis and security monitoring -- `C++`
- [CALDERA](https://github.com/mitre/caldera) - Automated adversary emulation system that performs post-compromise adversarial behavior within Windows Enterprise networks -- `Python`
- [Checkov](https://www.checkov.io/) - Scans cloud infrastructure provisioned using Terraform, Cloudformation or Kubernetes and detects security and compliance misconfigurations, similar to a sub-component of Twistlock -- `Golang`
- [cherrytree](https://www.giuspen.com/cherrytree/) - Hierarchical note taking application, excellent for red team / pentest notes -- `Python`
- [chkrootkit](http://www.chkrootkit.org/) - Rootkit checker, best used from a live CD -- `C`
- [CIS Linux Benchmarks](https://learn.cisecurity.org/benchmarks?category=benchmarks.os.linux) - Linux OS hardening guides, superb! -- `collection`
- [Common Vulnerability Scoring System Calculator](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator) - Version three -- `collection`
- [ConfigServer Security and Firewall (CSF)](https://configserver.com/cp/csf.html) - Stateful Packet Inspection (SPI) firewall, Login/Intrusion Detection and Security application for Linux servers -- `various lang`
- [Conftest](https://github.com/open-policy-agent/conftest) - Write tests against structured configuration data (Kuberetes, Terraform, Serverless, etc) -- `Golang`
- [CSP Evaluator](https://csp-evaluator.withgoogle.com/) - Check if a Content Security Policy (CSP) serves as a strong mitigation against cross-site scripting attacks, by Google -- `in-browser`
- [cuckoo](http://cuckoo.cert.ee/) - Feed in malware URL, it fires up VM, and provides a report about the actions the malware took -- `in-browser`
- [CyberChef](https://github.com/gchq/CyberChef) - A web app for encryption, encoding, compression and data analysis -- `in-browser` `JavaScript`
- [Cyber Security Transformation Chef](https://github.com/usdAG/cstc) - CyberChef as a Burp Suite extension -- `Java`
- [dcfldd](http://dcfldd.sourceforge.net/) - Enhanced dd with security and forensics features -- `C`
- [Dradis CE (Community Edition)](https://dradisframework.com/ce/) - Reporting framework for generating one-click reports (vuln scanning, pentest, etc) -- `Ruby`
- [Dshell](https://github.com/USArmyResearchLab/Dshell) - Network forensic analysis framework, written by the US Army -- `Python`
- [EncFS](https://vgough.github.io/encfs/) - Encrypted file system in user space via FUSE -- `C++`
- [fail2ban](https://www.fail2ban.org/) - Watches log files to ban IPs based on rules (too many failed logins, exploit attempts, brute force attacks, etc) -- `Python`
- [Forensics Acquisition of Websites (FAW)](http://en.fawproject.com/) - Download and save social media sites, paid version has more features -- `closed source` `Windows`
- [Forensics Wiki](http://www.forensicswiki.org/wiki/Main_Page) - Digital forensics wiki, tons of tools and information -- `wiki`
- [FTimes](https://sourceforge.net/projects/ftimes/) - System baselining and evidence collection tool -- `C`
- [fwknop (FireWall KNock OPerator)](http://www.cipherdyne.org/fwknop/) - Single Packet Authorization (SPA), authoriation packet from you opens firewall rules so only you can get in -- `various lang`
- [GGCR](https://github.com/google/ggrc-core) - GRC, by Google -- `Python`
- [Google Safe Browsing Site Status](https://transparencyreport.google.com/safe-browsing/search) - Use Google for site/URL malware analysis -- `in-browser`
- [GRR Rapid Response](https://github.com/google/grr) - Live forensics for incident response via a Python agent, dump memory, isolate host, snoop syscalls etc -- `Python`
- [hashcat](https://hashcat.net/hashcat/) - World's fastest CPU password cracker / password recovery -- `C`
- [Hybrid Analysis](https://www.hybrid-analysis.com/) - Dree malware analysis service that detects and analyzes unknown threats using a unique _Hybrid Analysis_ -- `in-browser`
- [icebreaker](https://github.com/DanMcInerney/icebreaker) - Automates internal network attacks against Active Directory to deliver you plaintext credentials -- `various lang`
- [Information Security Cheat Sheets and Checklists](https://zeltser.com/cheat-sheets/) - An assortment of IS checklists and cheat sheets, -- `collection`
- [Jenkins Pentesting](https://github.com/gquere/pwn_jenkins) - Title, please contribute -- `various lang`
- [Just the Basics (JTB) Investigator](https://github.com/Th3J0kr/jtb_investigator) - Simple menu & CLI to automate repetitive everyday tasks -- `Python`
- [geoiplookup](https://linux.die.net/man/1/geoiplookup) - Uses the GeoIP DB and library to determine which physical country an IP or host originates in, includes PAM library -- `built-in`
- [Hindsight](https://github.com/obsidianforensics/hindsight) - Internet history forensics for Google Chrome/Chromium -- `Python`
- [Jailkit](https://olivier.sessink.nl/jailkit/) - chroot toolkit -- `C`
- [Joe's Sandbox (Cloud Basic)](https://www.joesandbox.com/) - Deep automated malware analysis -- `in-browser`
- [Kali NetHunter Linux Root Toolkit (LRT)](https://github.com/offensive-security/nethunter-LRT) - Collection of bash scripts that setup and install Kali Linux NetHunter from a Linux/OSX environment onto a NetHunter supported device -- `shell`
- [LinEnum](https://github.com/rebootuser/LinEnum) - Enumerate a local Linux environment -- `shell`
- [Lynis](https://cisofy.com/lynis/) - Auditing and hardening tool, supports most Unix-like operating systems -- `shell`
- [Malcom](https://github.com/idaholab/Malcolm) - Easily deployable network analysis tool suite for full packet capture artifacts (PCAP files) and Zeek logs -- `various lang`
- [Massscan](https://github.com/robertdavidgraham/masscan) - Scans in parallel and async for the fastest scans around -- `C`
- [Metasploit](https://www.metasploit.com/) - Classic exploit framework -- `various lang`
- [MITRE ATT&CK](https://attack.mitre.org/) - Knowledge base of adversary tactics and techniques based on real-world observations, used for threat modeling -- `collection`
- [National Checklist Program](https://nvd.nist.gov/ncp/repository) - U.S. government repository of publicly available security checklists (or benchmarks) that provide detailed low level guidance on setting the security configuration of operating systems and applications -- `collection`
- [National Software Reference Library (NSRL)](https://www.nist.gov/software-quality-group/national-software-reference-library-nsrl) - Large collection of diskprints from various software and malware -- `collection`
- [National Vulnerability Database](https://nvd.nist.gov/) - Gotta catch em all -- `collection`
- [Nikto2](https://cirt.net/Nikto2) - Web & app server vulnerability scanner -- `perl`
- [nmap](https://nmap.org/) - Classic port scanner -- `various lang`
- [nmap_vulners](https://github.com/vulnersCom/nmap-vulners) - Emumerate and list vulnerabilities during an nmap scan similar to Nessus -- `collection`
- [nmap Scripting Engine (NSE)](https://nmap.org/nsedoc/index.html) - Tons of scripts for nmap -- `various lang`
- [oclHashcat](https://hashcat.net/oclhashcat/) - World's fastest CPU + GPU password cracker / recovery software -- `C`
- [OpenSCAP](https://www.open-scap.org/page/Main_Page) - NIST Certified SCAP 1.2 toolkit -- `C`
- [OpenVAS](http://www.openvas.org/) - Vulnerability scanner, forked from the now closed-source Nessus scanner -- `C`
- [Open Policy Agent](https://www.openpolicyagent.org/) - Unifies policy enforcement in the cloud, the new standard -- `Golang`
- [Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - Focus on web application security -- `organization`
- [Oracle Database Attacking Tool (ODAT)](https://github.com/quentinhardy/odat) - Open source penetration testing tool that tests the security of Oracle databases remotely -- `Python`
- [OS X Auditor](https://github.com/jipegit/OSXAuditor) - Forensics tool for Mac -- `OS X` `JavaScript`
- [OSSEC](http://www.ossec.net/) - Host based intrusion detection system (HIDS), supports most Unix-like OSes -- `C` `Windows` `OS X`
- [OWASP Cheat Sheet Series](https://github.com/OWASP/CheatSheetSeries) - Contains all OWASP cheat sheets, new v2 -- `collection`
- [PALADIN](https://sumuri.com/software/paladin/) - Easy to use Linux-based live CD for forensic analysis -- `various lang`
- [Penetration Testers Framework](https://github.com/trustedsec/ptf) - Script to pull down all the latest greatest tools -- `Python`
- [pfsense](https://www.pfsense.org/) - The best firewall software, supports appliances and live CDs -- `C`
- [preeny](https://github.com/zardus/preeny) - Some helpful preload libraries for pwning stuff -- `C`
- [Prey](https://preyproject.com/) - Open source anti-theft software for almost all platforms -- `shell` `Java` `mobile`
- [ProcDOT](http://www.procdot.com/) - All in one visual malware analysis and visualization, by CERN -- `closed source` `various lang`
- [Purple Team ATT&CK Automation](https://github.com/praetorian-code/purple-team-attack-automation) - Metasploit automation of MITRE ATT&CK TTPs -- `Ruby`
- [Qubes OS](https://www.qubes-os.org/) - A reasonably secure operating system -- `various lang`
- [Red October](https://github.com/cloudflare/redoctober) - Go server for two-man rule style file encryption and decryption -- `way cool`
- [Red Teaming Toolkit](https://github.com/infosecn1nja/Red-Teaming-Toolkit) - Collection of open source and commercial tools that aid in red team operations -- `collection`
- [Regshot](https://sourceforge.net/projects/regshot/) - Snapshot and compare the Windows Registry for before/after analysis -- `C`
- [Rootkit Hunter](http://rkhunter.sourceforge.net/) - Compares hashes of important files with known good hashes that are stored in online databases -- `perl` `shell`
- [SalSA (Salvaging Static Analysis)](https://github.com/deptofdefense/SalSA) - Windows PE file parsing in-browser, can be locally hosted, by the DoD -- `Python`
- [Samhain](https://www.la-samhna.de/samhain/) - HIDS, file integrity checker, rootkit detection, log file monitoring, and more -- `C`
- [scrub](https://linux.die.net/man/1/scrub) - Supports many disk-wiping standards including military / government grade wipes -- `built-in`
- [scrypt](https://en.wikipedia.org/wiki/Scrypt) - More secure against hardware brute-force attacks than alternatives such as PBKDF2 or bcrypt, key stretching -- `C`
- [SecLists](https://github.com/danielmiessler/SecLists) - Collection of multiple types of lists used during security assessments collected in one place -- `collection`
- [Security Onion](https://securityonion.net/) - Linux distro for IDS, NSM, and log management -- `various lang`
- [Security Technical Implementation Guide (STIG)](https://public.cyber.mil/stigs/) - Guides to securing almost every application, by the US military -- `collection`
- [SELKS](https://www.stamus-networks.com/open-source/) - Debian based based IDS/IPS with ELK stack, installable or live CD -- `various lang`
- [simplewall](https://github.com/henrypp/simplewall) - Simple app to configure Windows Filtering Platform (WFP), VERY powerful -- `Windows`
- [Snort](https://www.snort.org/) - The classic network intrusion prevention system (NIPS) -- `C`
- [SPARTA](https://sparta.secforce.com/) - GUI to simplify the scanning and enumeration phases -- `Python`
- [Spiderfoot](http://www.spiderfoot.net/) - Automate the process of gathering intelligence about a given target -- `Python`
- [SubBrute](https://github.com/TheRook/subbrute) - Subdomain enumeration tool for penetration testers -- `Python`
- [sudosh2](https://github.com/squash/sudosh2) - Records all keystrokes and output and can play back the session as just like a VCR -- `C`
- [SuperTokens](https://supertokens.io/) - OSS alternative to Auth0, Firebase Auth and AWS Cognito -- `Java`
- [SWORD Dropbox](https://medium.com/@tomac/a-15-openwrt-based-diy-pen-test-dropbox-26a98a5fa5e5) -- $15 OpenWRT + Pi based DIY disposable pen-test tool -- `various lang`
- [symon-config](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing -- `XML!!!!` `Windows`
- [terraform-compliance](https://terraform-compliance.com/) - Uses "negative testing" (not functional testing), similar to Hashicorp Sentinel, NOT for best practices, makes sure your code does what you think it does -- `Python pip`
- [tfsec](https://github.com/tfsec/tfsec) - Static code analysis for Terraform -- `Golang`
- [theZoo](https://github.com/ytisf/theZoo/tree/master/malwares/Binaries) - These are real and they are smarter than you, do not fuck around -- `collection`
- [tink](https://github.com/google/tink) - Smiple, small, secure crypto library by Google -- `C++`
- [Tripwire](https://github.com/Tripwire/tripwire-open-source) - File integrity checker and monitor, replacement for the now closed-source Tripwire -- `C`
- [URLquery](https://urlquery.net/) - Free service to scan a URL for web-based malware -- `in-browser`
- [urlscan.io](https://urlscan.io/) - Similar to URLquery -- `in-browser`
- [usbkill](https://github.com/hephaest0s/usbkill) - Kill switch that takes action when a USB device is connected -- `Python`
- [VeraCrypt](https://www.veracrypt.fr) - OSS successor to and fork of TrueCrypt, supports Linux, Windows, and Mac -- `C` `C++`
- [VirusTotal](https://www.virustotal.com/) - Allows you to upload a file and have it scanned by tons of virus scanners -- `in-browser`
- [tcpbin](https://github.com/ecx86/tcpbin) - A simple TCP dumping server/host for pentesting -- `Python`
- [Tomb](https://github.com/dyne/tomb) - zsh wrapper script for cryptsetup + gpg + LUKS volumes -- `shell`
- [URL Canary](https://urlcanary.com/) - Create canary URLs so you know if someone is inspecting the source code of your applications -- `in browser`
- [VulnHub](https://www.vulnhub.com/) - ISOs and more for hands-on security practice -- `collection`
- [w3af](https://github.com/andresriancho/w3af) - Web application attack and audit framework, OSS vun scanner -- `Python`
- [Zed Attack Proxy (ZAP)](https://www.owasp.org/index.php/ZAP) - Pen testing too that focues on web applications -- `Java`
- [ZMap](https://zmap.io/) - Scanner designed for large address spaces -- `in-browser`
- [zxcvbn](https://github.com/dropbox/zxcvbn) - Password strength estimator, written by Dropbox, operates in a browser window -- `CoffeeScript` `in-browser`
- [zzuf](https://github.com/samhocevar/zzuf) - Transparent application input fuzzer that works by intercepting file and network operations and changing random bits in the program's input -- `C`

---

## Shell Scripting and Tools

> Shell scripting tutorials, collections of note, Linux shells for Windows, and misc neat tools - see also [Terminal Tools and SSH Clients](#terminal-tools-and-ssh-clients) and [Orchestration](#orchestration) for parallel SSH tools and [Regular Expressions](#regular-expressions)

- [Advanced Bash-Scripting Guide](http://www.tldp.org/LDP/abs/html/) - By the Linux Documentation Project (LDP) -- `tutorial`
- [awk Tutorial](http://www.grymoire.com/Unix/Awk.html) - Easy to understand awk tutorial -- `tutorial`
- [Awesome dotfiles](https://github.com/webpro/awesome-dotfiles) - All kinds of . files -- `collection`
- [autojump](https://github.com/joelthelion/autojump) - Small database of directories that you visited in the past, used to quickly navigate complex directory structures -- `Python`
- [autoenv](https://github.com/inishchith/autoenv) - Autoruns a .env file in a directory when you cd into the directory -- `Python`
- [Awesome Shell](https://github.com/alebcay/awesome-shell) - Massive collection of shell tools -- `collection`
- [Babun](https://babun.github.io/) - Pre-configured Cygwin with many more features and a better design -- `various lang`
- [Bash-it](https://github.com/Bash-it/bash-it) - bash version of the oh-my-zsh shell environment -- `various lang`
- [BashGuide](http://mywiki.wooledge.org/BashGuide) - Targeted at beginners -- `wiki`
- [Bash Hackers Wiki](http://wiki.bash-hackers.org/start) - Human-readable bash documentation so you don't have to dig through the man page -- `wiki`
- [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - Common errors that bash programmers make -- `wiki`
- [cheat](https://github.com/cheat/cheat) - create and view interactive cheatsheets on the command-line -- `Python`
- [comm](https://linux.die.net/man/1/comm) - Display lines that two files have in common (eg: the opposite of diff) -- `built-in`
- [CommandlineFu](http://www.commandlinefu.com/commands/browse) - Killer code snippets -- `collection`
- [CRUSH (Custom Reporting Utilities for SHell)](https://github.com/google/crush-tools) - Killer toolset for working on delimited data, by Google -- `C`
- [Cygwin](https://www.cygwin.com/) - GNU shell and tools for Windows -- `C` `Windows`
- [dotfiles by Paul Miller](https://github.com/paulmillr/dotfiles) - Beautiful and flexible Mac terminal configuration files and utilities, ZSH-based -- `shell` `OS X` `hawt`
- [dotfiles](http://dotfiles.github.io/) - Unofficial guide to dotfiles on GitHub -- `collection`
- [Environment Modules](http://modules.sourceforge.net/) - Dynamic modification of your shell environment using modules -- `Tcl` `Windows`
- [fzf](https://github.com/junegunn/fzf) - Command line fuzzy finder, supports tmux/bash/zsh -- `Golang`
- [icdiff](https://www.jefftk.com/icdiff) - diff tool that highlights the differences -- `Python` `OS X`
- [moreutils](https://joeyh.name/code/moreutils/) - "Collection of the unix tools that nobody thought to write long ago when unix was young" -- `neat`
- [notify](https://mashlol.github.io/notify/) - Send a notification from your Linux system to an Android app on your phone, good for long running shell commands -- `JavaScript` `Android`
- [pigz](http://zlib.net/pigz/) - Parallel gzip for multi-processor/core systems -- `C`
- [pv](https://linux.die.net/man/1/pv) - Shows the progress of data as it flows through a pipe -- `built-in`
- [ShellCheck](https://www.shellcheck.net/) - Checks shell scripts for common mistakes, essentially a linter / static analysis -- `in-browser`
- [Shell Style Guide](https://google.github.io/styleguide/shell.xml) - By Google -- `collection`
- [tldr](https://github.com/tldr-pages/tldr) - Simplified and community-driven man pages, cuts out a lot of cruft -- `collection`
- [Unix Toolbox](http://cb.vu/unixtoolbox.xhtml) - A collection of Unix/Linux/BSD commands and tasks for advanced users -- `collection`

---

## Software Development Tools

> Build systems, stubs/mocks, CI/CD, cheat sheets, and other - see also [Git Tools](#git-tools) and [Collaboration Tools](#collaboration-tools) and [Editors](#editors) and [Shell Scripting and Tools](#shell-scripting-and-tools) and [Web and HTTP Tools](#web-and-http-tools) and [Tracing and Profiling](#tracing-and-profiling) and [Web and HTTP Performance Analysis Tools](#web-and-http-performance-analysis-tools)

- [ack2](https://beyondgrep.com/) - grep-like tool designed to search source code -- `perl`
- [afl-unicorn](https://github.com/njv299/afl-unicorn) - Fuzz any piece of binary that can be emulated by Unicorn Engine -- `C`
- [ag (aka The Silver Searcher)](https://github.com/ggreer/the_silver_searcher) - Source code searching tool, a better grep -- `C`
- [Bazel](https://bazel.build/) - Google's build system -- `Java`
- [Buildbot](https://buildbot.net/) - CI framework -- `Python`
- [cwrap](https://cwrap.org/) - Wrappers for creating test scenarios and faking behavior/ stubbing, mostly network focused, by the Samba guys -- `C`
- [dev-setup](https://github.com/donnemartin/dev-setup) - Automated setup scripts for laptop tools like Sublime Text, AWS, Spark, Android dev, and more -- `collection`
- [drone](https://github.com/drone/drone) - CI platform built on Docker / containers, can also deploy to Kubernetes -- `Golang`
- [dropwizard](http://www.dropwizard.io/) - Simple library for building production-ready RESTful web services -- `various lang`
- [Fossil](https://www.fossil-scm.org) - Simple all-in-one SCM -- `various lang`
- [fswatch](https://emcrisostomo.github.io/fswatch/) - Cross-platform for watching files and taking action when they change -- `C++`
- [gdb TUI](https://ftp.gnu.org/old-gnu/Manuals/gdb/html_chapter/gdb_19.html) - Curses / menu-based interface for GDB, much easier than REPL mode -- `C`
- [GoCI](https://www.gocd.org/) - Go continuous delivery platform by ThoughtWorks -- `Java`
- [Guard](https://github.com/guard/guard) - Flexible framework to take action on file system change event -- `Ruby gem`
- [Gulp](https://gulpjs.com/) - Built system / toolkit that helps you automate time-consuming tasks in your development workflow -- `JavaScript`
- [Jenkins](https://jenkins-ci.org/) - The most popular CI orchestration tool, supports a billion plugins -- `various lang`
- [jenkins-job-dsl (Jenkins Job DSL Plugin)](https://github.com/jenkinsci/job-dsl-plugin) - Groovy-based DSL for writing Jenkins jobs -- `Groovy`
- [Jenkins job-config-history Plugin](https://wiki.jenkins-ci.org/display/JENKINS/JobConfigHistory+Plugin) - Tracks changes to system and job configurations -- `Java`
- [Jenkins Job Builder](https://docs.openstack.org/infra/jenkins-job-builder/) - Takes simple descriptions of Jenkins jobs in YAML or JSON format and uses them to configure Jenkins -- `Python pip`
- [Jenkins Log Recorder](https://wiki.jenkins.io/display/JENKINS/Logging) - Helps you group relevant logs together while filtering out the noise -- `Java`
- [Jenkins Pipeline Mutlibranch Plugin](https://wiki.jenkins.io/display/JENKINS/Pipeline+Multibranch+Plugin) - Automatically creates a new Jenkins job whenever a new branch is pushed to a source code repository -- `Java`
- [Jenkins ThinBackup](https://github.com/jenkinsci/thin-backup-plugin) - Jenkins plugin that backups configurations (not workspaces or archives) -- `Java`
- [JSON Server](https://github.com/typicode/json-server) - Full fake REST API for quickly prototyping and mocking in 30 seconds -- `JavaScript`
- [Meld](http://meldmerge.org/) - Diff tool, recommended -- `Python`
- [MockServer](http://mock-server.com/) - Web server to remotely or locally mock HTTP/HTTPS and similar -- `Java`
- [mountebank](http://www.mbtest.org/) - Stub downstream resources for testing, supports HTTP HTTPS SMTP TCP -- `JavaScript` `Windows` `OS X`
- [Ninja](https://ninja-build.org/) - Small build system with a focus on speed -- `Python`
- [Pact](https://github.com/pact-foundation) - HTTP contract tests and without contract testing, the only way to ensure that applications will work correctly together is by using expensive and brittle integration tests -- `various lang`
- [PatchELF](https://github.com/NixOS/patchelf) - Simple utility for modifying existing ELF executables and libraries -- `C`
- [PEview](http://wjradburn.com/software/) - Easily and quickly view the structure and content of Windows EXE DDL LIB Portable Executable (PE) files -- `closed source`
- [PRoot](https://proot-me.github.io/) - chroot, mount --bind, and binfmt_misc without privilege/setup -- `C`
- [Proxygen](https://github.com/facebook/proxygen) - Modern C++ HTTP library, by Facebook -- `C++`
- [REST-assured](https://github.com/jayway/rest-assured) - Java DSL for testing of REST services -- `Java`
- [RocksDB](http://rocksdb.org/) - Library that provides an embeddable, persistent key-value store for fast storage - by Facebook -- `C++`
- [SonarQube](https://www.sonarqube.org/) - Platform and dashboard for managing code quality -- `Ruby` `Java`
- [Sonatype Nexus](http://www.sonatype.org/nexus/) - Software / binary artifact storage -- `Java`
- [SourceGraph](https://github.com/sourcegraph/sourcegraph) - Perhaps the best code search and navigation engine -- `Golang`
- [SymbolHound](http://symbolhound.com) - Search engine that doesn't ignore special characters, great for programming questions -- `try it`
- [watchman](https://github.com/facebook/watchman) - Watch files and take action when they change (eg: kick off the CI system), by Facebook -- `C`
- [WireMock](http://wiremock.org/) - Flexible stubbing and mocking services -- `Java`

---

## SSH Tools

> Misc SSH stuff - see also [Terminal Tools and SSH Clients](#terminal-tools-and-ssh-clients) for clients and [Orchestration](#orchestration) for parallel SSH tools and [Shell Scripting and Tools](#shell-scripting-and-tools)

- [autossh](http://www.harding.motd.ca/autossh/) - Automatically restart SSH sessions that stop passing traffic -- `C`
- [Corkscrew](https://github.com/bryanpkc/corkscrew) - Tunnel SSH through HTTP proxies -- `C`
- [Dropbear](https://matt.ucc.asn.au/dropbear/dropbear.html) - Small / minimal SSH client and server, often used in IoT and embedded devices -- `C`
- [Keychain](https://www.funtoo.org/Keychain) - Manage SSH and GPG keys, acts as a frontend to ssh-agent, only enter passphrase once per reboot -- `shell`
- [Match](https://linux.die.net/man/5/sshd_config) - Creates a conditional block, great for controlling actions on a per-user and/or per-host basis in sshd_config -- `built-in`
- [Mosh (Mobile Shell)](https://mosh.org/) - Remote shell that supports roaming (client IP address changes) and intermittent connectivity, by MIT -- `C++`
- [Shuttle](https://github.com/fitztrev/shuttle) - A simple SSH shortcut menu for macOS -- `Objective-C`
- [ssh-chat](https://github.com/shazow/ssh-chat) Instead of a shell you get a chat prompt -- `Golang`
- [ssh-ldap-helper](https://linux.die.net/man/8/ssh-ldap-helper) - Store public keys in LDAP -- `built-in`
- [SSHFS](https://linux.die.net/man/1/sshfs) - Mount remote file systems using a SSH tunnel -- `built-in`
- [sshmuxd](https://github.com/joushou/sshmuxd) - SSH jumphost style proxy -- `Golang`
- [sshttp](https://github.com/stealth/sshttp) - Port multiplexer that hides a SSH daesmon behind HTTP, HTTPS, or SMTP on a single port -- `C`
- [SSH Guard](https://www.sshguard.net/) - Think fail2ban for SSH -- `C`
- [SSH Power Tool (sshpt)](https://pypi.python.org/pypi/sshpt/) - Execute commands and upload files to many servers simultaneously via SSH without using pre-shared keys -- `Python pip`
- [storm](https://github.com/emre/storm) - CLI and GUI tool to manage your SSH connections (add, delete, list, search) -- `OS X`

---

## SSL Tools

> SSL, TLS, CAs, and similar tools for interacting with HTTPS and SSL certificates - see also [Web and HTTP Tools](#web-and-http-tools) and [Security Tools](#security-tools)

- [BadSSL.com](https://badssl.com/) - Test various clients (browsers, etc) against bad SSL configs -- `in-browser`
- [BoringSSL](https://boringssl.googlesource.com/boringssl/) - Google's fork of OpenSSL, does not guarantee API and ABI compatibility -- `C`
- [cfssl](https://github.com/cloudflare/cfssl) - PKI/TLS swiss army knife, has CLI and a HTTP API server for signing, verifying, and bundling TLS certificates -- `Golang`
- [cipherscan](https://github.com/jvehent/cipherscan) - Find out which SSL ciphersuites are supported by a target -- `Python`
- [Dogtag Certificate System](http://pki.fedoraproject.org/wiki/PKI_Main_Page) - PKI component of FreeIPA, by Fedora -- `C`
- [Fizz](https://github.com/facebookincubator/fizz) - C++14 implementation of the TLS-1.3 standard, by Facebook -- `C++`
- [HSTS (HTTP Strict Transport Secuirity)](https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security) - Forces browsers to interact with a site by only using HTTPS -- `article`
- [HSTS Preload Submission](https://hstspreload.org/) - Submit your site to be preloaded in major browsers -- `security`
- [Let's Encrypt](https://letsencrypt.org/) - Free SSL certs from a real CA -- `in-browser`
- [Mozilla Server Side TLS](https://wiki.mozilla.org/Security/Server_Side_TLS) - Mozilla's extensive server side TLS configuration guide -- `wiki`
- [Mozilla SSL Configuration Generator](https://mozilla.github.io/server-side-tls/ssl-config-generator/) - Generate SSL configs for Apache, Nginx, ELB, HAproxy and more -- `in-browser`
- [nogotofail](https://github.com/google/nogotofail) - Spot and fix weak TLS/SSL connections and sensitive cleartext traffic, by Google -- `Python`
- [Qualys SSL Server Test](https://www.ssllabs.com/ssltest/) - Evaluates and provides recommendations for the SSL settings of any web site -- `in-browser`
- [s2n](https://github.com/awslabs/s2n) - Amazon's implementation of the TLS/SSL protocols in C99 (simple, small, fast, secure) -- `C`
- [Server Name Indication (SNI)](https://wiki.apache.org/httpd/NameBasedSSLVHostsWithSNI) - Think vhosts for SSL -- `article`
- [sslconfig](https://github.com/cloudflare/sslconfig) - CloudFlare's Internet facing SSL cipher configuration, patches for Nginx and OpenSSL -- `C`
- [ssldump](https://github.com/adulau/ssldump) - The de-facto repo -- `C`
- [SSLsplit](https://www.roe.ch/SSLsplit) - Transparent and scalable SSL/TLS interception -- `C`
- [sslyze](https://github.com/nabla-c0d3/sslyze) - Fast and full-featured SSL scanner, written in Python -- `Python` `OS X`
- [stunnel](https://www.stunnel.org/index.html) - Create simple TLS tunnels for existing services (eg: telnet, nc, etc) -- `C`

---

## Storage Tools

> The storage junk drawer - see also [Backups](#backups) and [Cloud File Sync and Sharing](#cloud-file-sync-and-sharing) and [Live CD Tools](#live-cd-tools)

- [BeeGFS](https://www.beegfs.com/content/) - Parallel cluster file system, worth examining -- `C++`
- [CrystalDiskInfo](https://crystalmark.info/software/CrystalDiskInfo/index-e.html) - S.M.A.R.T. GUI tool for Windows -- `closed source` `Windows`
- [FlashCache](https://github.com/facebookarchive/flashcache) - General purpose, write-back block cache -- `C`
- [fs-cache](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Storage_Administration_Guide/ch-fscache.html) - Modern NFS client-side caching -- `built-in`
- [Linux-IO Target (LIO)](http://linux-iscsi.org/wiki/Main_Page) - Create and share iSCSI, Fibre Channel, FC over Ethernet, and other storage targets from Linux VMs -- `built-in`
- [Linux Journal - Linux Swap Space](https://www.linuxjournal.com/article/10678) - Superb article about Linux swap, includes some tuning parameters -- `article`
- [lsblk](https://linux.die.net/man/8/lsblk) - List block devices -- `built-in`
- [ncdu](https://linux.die.net/man/1/ncdu) - ncurses version of "du" -- `built-in`
- [Parted Magic](https://partedmagic.com/) - Resize, grow, shrink, clone, recovery, wiping, benchmarking, and more. Supports Linux and Windows file systems -- `Windows`
- [snapper](http://snapper.io/) - CLI tool to manage Btrfs snapshots, snapshot timelines, and more -- `various lang`
- [System Storage Manager (SSM)](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/7/html/Storage_Administration_Guide/ch-ssm.html) - Generic CLI for managing all types of storage (DM, LVM, multipath), added in RHEL 7 -- `built-in`

---

## Storage Performance Analysis Tools

> Grind your disks into dust - see also [Performance Analysis Tools](#performance-analysis-tools) and [Tracing and Profiling](#tracing-and-profiling)

- [Bonnie++](https://linux.die.net/man/8/bonnie++) - The classic, still updated -- `built-in`
- [Connectathon Test Suite](http://wiki.linux-nfs.org/wiki/index.php/Connectathon_test_suite) - NFS stress testing and benchmarking tools -- `various lang`
- [fio](https://github.com/axboe/fio) - Supports 19 different I/O engines (sync, mmap, libaio, posixaio, etc), very powerful -- `C`
- [Fnotifystat](http://kernel.ubuntu.com/~cking/fnotifystat/) - Dumps the file system activity in a given period of time -- `C`
- [ioping](https://github.com/koct9i/ioping) - Monitor I/O latency in real time -- `C`
- [iorate](https://sites.google.com/site/vwiorate/) - Originally written by EMC, now open source -- `C`
- [iotop](http://guichaz.free.fr/iotop/) - top for I/O requests, displays information on a per-process basis -- `Python`
- [IOzone](http://www.iozone.org/) - Supports NFS, still being updated! -- `C`
- [Threaded I/O Tester (tiobench)](https://github.com/mkuoppal/tiobench) - Threaded I/O tester, tiotest and tiobench -- `C`

---

## Terminal Tools and SSH Clients

> Fancy SSH clients, terminal sharing, and similar tools - see also [SSH Tools](#ssh-tools) and [Orchestration](#orchestration) for parallel SSH tools and [Shell Scripting and Tools](#shell-scripting-and-tools)

- [Bitvise SSH Client](https://www.bitvise.com/ssh-client) - Feature-rich SSH & SFTP client for Windows, free for individual use -- `closed source` `Windows`
- [Byobu](https://byobu.org) - An enhanced version of the "screen" utility -- `shell` `OS X`
- [ChromaTerm--](https://github.com/hSaria/ChromaTerm--) - Pipe stdin to this program which highlights based on user defined regexs in .conf file -- `C`
- [ConnectBot](https://play.google.com/store/apps/details?id=org.connectbot&hl=en) - Open source SSH client for Android -- `Java` `Android`
- [Guacamole](https://guacamole.apache.org/) - Clientless (in-browser) remote desktop gateway, supports VNC and RDP -- `various lang`
- [i2cssh](https://github.com/wouterdebie/i2cssh) - csshX like ssh tool for iTerm2 -- `Ruby`
- [iTerm2](https://www.iterm2.com/) - Killer terminal replacement for Mac -- `OS X` -- `Objective-C`
- [KiTTY](http://kitty.9bis.net/) - PuTTY fork with additional features -- `Windows`
- [MobaXterm](https://mobaxterm.mobatek.net/) - Tabbed SSH, VNC, and RDP client for Windows, free for personal use -- `closed source` `Windows`
- [mRemoteNG](http://www.mremoteng.org/) - Open source, tabbed, multi-protocol, remote connections manager -- `Windows`
- [MTPuTTY (Multi-Tabbed PuTTY)](http://ttyplus.com/multi-tabbed-putty/) - Multiple PuTTY sessions in a single window -- `Windows`
- [NoVNC](https://kanaka.github.io/noVNC/) - Client-less VNC in a web browser, uses HTML5 and WebSockets -- `in-browser`
- [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/) - The classic SSH client -- `Windows`
- [PuTTYtray](https://puttytray.goeswhere.com/) - PuTTY in the systray + additional features -- `C`
- [reptyr](https://github.com/nelhage/reptyr) - Reparent a running program to a new terminal -- `C`
- [screen](https://linux.die.net/man/1/screen) - Detatch and re-attach to shell sessions while they continue to run in the background -- `C`
- [SuperPutty](https://github.com/jimradford/superputty) - Allows the PuTTY SSH client to be opened in tabs -- `Windows`
- [tmate](https://tmate.io/) - Instant terminal sharing, a tmux fork -- `OS X`
- [tmux](https://github.com/tmux/tmux/wiki) - Alternative to GNU screen, also used for terminal sharing -- `C`
- [tmux Resurrect](https://github.com/tmux-plugins/tmux-resurrect) - Persists tmux environment across system restarts -- `shell`
- [Warp](https://github.com/spolu/warp) - Securely share your terminal, like handing a co-worker your keyboard -- `Golang`
- [WinSCP](https://winscp.net) - The well-known SCP client -- `C` `Windows`
- [x2go](https://wiki.x2go.org/doku.php) - One of the best remote-desktop-over-SSH clients -- `Windows` `OS X`
- [Xshell](https://www.netsarang.com/en/xshell/) - SSH client for Windows, free for personal use -- `closed source` `Windows`

---

## Tracing and Profiling

> OS kernel and process-level tracing and profiling tools - see also [Performance Analysis Tools](#performance-analysis-tools) and [Network Performance Analysis Tools](#network-performance-analysis-tools) and [Web and HTTP Performance Analysis Tools](#web-and-http-performance-analysis-tools) and [Metrics and Time Series Data](#metrics-and-time-series-data) and [RDBMS Performance Analysis Tools](#rdbms-performance-analysis-tools)

- [bcc](https://iovisor.github.io/bcc/) - Next generation, Linux 4.x kernel tracing tool suite, uses eBPF (Extended Berkeley Packet Filters) -- `C`
- [eBPF](http://www.brendangregg.com/ebpf.html) - DTrace + SystemTap, requires 4.x kernel, mostly uses bcc -- `various lang`
- [kdump](https://wiki.archlinux.org/index.php/Kdump) - Linux kernel dump facility (where to save it, what to save, etc) -- `C`
- [Linux Trace Toolkit - Next Generation (LLTng)](https://lttng.org/) - Linux kernel tracer and profiler, lower overhead than System Tap -- `C`
- [ltrace Tutorial](https://webcache.googleusercontent.com/search?q=cache:k388vTAv6tYJ:https://developers.redhat.com/blog/2014/07/10/ltrace-for-rhel-6-and-7/+&cd=1&hl=en&ct=clnk&gl=us&client=firefox-b-1-ab) - ltrace (library call tracer) tutorial by Red Hat -- `article`
- [lttng-analyses](https://github.com/lttng/lttng-analyses) - Official collection of LLTNG scripts and snippets -- `collection`
- [Mastif Visualizer](https://projects.kde.org/projects/extragear/sdk/massif-visualizer) - Visualizer for the Valgrind's Mastiff utility -- `C++`
- [OpenSnoop](http://www.brendangregg.com/blog/2014-07-25/opensnoop-for-linux.html) - Continually monitor for file opens -- `shell`
- [OProfile](http://oprofile.sourceforge.net/) - System-wide statistical profiling tool -- `C`
- [perf](https://perf.wiki.kernel.org/index.php/Tutorial) - User-land performance analysis tool, a sampling profiler -- `C`
- [perf-tools](https://github.com/brendangregg/perf-tools) - Uses perf and ftrace, includes iosnoop -- `Brendan Gregg`
- [pstore](https://lwn.net/Articles/434821/) - Save kernel crash info in a platform-specific persistent memory so data is not lost (eg: disks failed so write dump to NVRAM instead) -- `article`
- [Record and Replay (rr)](http://rr-project.org/) - Record the failure once, then debug the recording deterministically, supports C and C++, by Mozilla -- `C` `C++`
- [strace](https://linux.die.net/man/1/strace) - System call tracer for user space processes -- `built-in`
- [SystemTap (stap)](https://sourceware.org/systemtap/wiki/HomePage) - Linux kernel tracing and performance analysis tool -- `C` `C++`
- [Valgrind](http://valgrind.org/info/tools.html) - Tool suite that includes cache profilers, heap profiles, thread race condition checkers, and more - a CPU-level emulator -- `C`

---

## Two Factor Authentication

> [Universal 2nd Factor (U2F)](https://en.wikipedia.org/wiki/Universal_2nd_Factor) is the successor to two-factor authentication / TFA / 2FA and multi-factor authentication / MFA. Avoid using SMS if possible - see also [VPNs and Tunnels](#vpns-and-tunnels) and [Secrets Management](#secrets-management)

- [Authelia](https://github.com/clems4ever/authelia) - 2FA and SSO for your apps via Docker on Kubernetes, supports Yubikey, Google Authenticator, and e-mail based password reset -- `Golang`
- [CentOS 7 2FA VPN](https://github.com/rharmonson/richtech/wiki/CentOS-7-Minimal-&-Two-factor-Authentication-using-FreeRADIUS-3,-SSSD-1.12,-&-Google-Authenticator) - VPN with CentOS 7 + FreeRADIUS + FreeIPA + Google Authenticator -- `tutorial`
- [FreeOTP](https://freeotp.github.io/) - Open source fork of Google Authenticator, by Red Hat -- `C` `mobile`
- [Google Authenticator](https://github.com/google/google-authenticator) - Official project, supports Android, iOS, and has a PAM module for SSH 2FA -- `C`
- [Nitrokey](https://www.nitrokey.com/) - Open source thumb drive for authentication -- `various lang`
- [One Time Password](https://wiki.archlinux.org/index.php/One_Time_PassWord) - PAM module allowing single-use passwords to login to a system -- `C`
- [pam-u2f](https://developers.yubico.com/pam-u2f/) - PAM module for auth via U2F compatible devices, by YubiKey -- `C`
- [privacyIDEA](https://www.privacyidea.org/) - All in one solution for two-factor authentication across all your organization's devices such as OTP tokens, SMS, VPNs, SSH keys, Windows, keyfob, etc -- `various lang`
- [Titan Security Key](https://store.google.com/product/titan_security_key_kit) - Physical key for FIDO 2FA, unphishable (really) -- `physical`
- [W3C's Web Authentication](https://www.w3.org/TR/2018/CR-webauthn-20180320/) - Standards driven, supports various tokens and OTP generators -- `specification`
- [yubico-pam](https://developers.yubico.com/yubico-pam/) - PAM module for use with YubiKey devices -- `C`
- [yubikey-full-disk-encryption](https://github.com/agherzan/yubikey-full-disk-encryption) - Encrypt storage on a LUKS partition using a Yubikey -- `Shell`
- [YubiKey GPG & SSH Guide](https://github.com/drduh/YubiKey-Guide) - Guide to using YubiKey as a SmartCard for GPG and SSH -- `tutorial`

---

## Virtualization and SDN

> OS, network, and storage virtualization, emulation, and simulation including SDN, load balancers, and firewalls - see also [Containers](#containers) for container-only network meshes and [VMware Tools](#vmware-tools)

- [BlueStacks](https://www.bluestacks.com/) - Android emulator that you can run on Windows, run apps from the Play store, etc -- `various lang`
- [Boxedwine](https://github.com/danoon2/Boxedwine) - WINE that uses Emscripten (wasm and asm.js) to run in a browser -- `various lang`
- [BusyBox](https://busybox.net/) - Bootable Linux with tiny versions of many common UNIX utilities in a single small executable -- `C`
- [Calico](http://www.projectcalico.org/) - L3 fabric that runs a vRouter on each node, supports containers -- `Python`
- [DOSbox](https://www.dosbox.com/) - Open source DOS emulator, great for running old games or utilities -- `C` `C++`
- [Firecracker](https://firecracker-microvm.github.io/) - Micro-VM for serverless computing, by Amazon -- `Rust`
- [FreeNAS](http://www.freenas.org/) - BSD-based NAS, supports ZFS -- `C`
- [GitHub Load Balancer Director](https://github.com/github/glb-director) - Layer 4 load balancer -- `C`
- [GNS3](https://www.gns3.com/) - Cisco and other network simulator that runs in VirtualBox or Qemu/KVM -- `Python`
- [HAproxy](https://www.haproxy.org/) - Open source software load balancer -- `C`
- [haproxyctl](https://github.com/flores/haproxyctl) - Wrapper to talk to the HAProxy socket, as well as regular init (start stop restart) shit -- `Ruby gem`
- [Katran](https://github.com/facebookincubator/katran) - A high performance layer 4 load balancer library, by Facebook -- `C++`
- [KVM (Kernel Virtual Machine)](http://www.linux-kvm.org/page/Main_Page) - The one, the only -- `C`
- [kvm-tools](http://www.linux-kvm.org/page/Kvmtools) - CLI tools for managing qemu-kvm domains -- `C`
- [KVM Management Tools](http://www.linux-kvm.org/page/Management_Tools) - Great list of KVM management tools on the KVM wiki, updated frequently -- `collection`
- [libvirt](https://libvirt.org/) - Open source API, daemon and management tool, used with many virtualization solutions -- `C`
- [Linux-IO Target (LIO)](http://linux-iscsi.org/wiki/Main_Page) - Create and share iSCSI, Fibre Channel, FC over Ethernet, and other storage targets from Linux VMs -- `built-in`
- [LVS (Linux Virtual Server)](http://www.linuxvirtualserver.org/) - Linux-based load balancer, also includes the IPVS kernel module -- `C`
- [Mininet](http://mininet.org/) - Easily setup networks for testing on your laptop with VirutalBox -- `various lang`
- [Minio](https://github.com/minio/minio) - An open source object storage server compatible with Amazon S3 APIs -- `Golang`
- [ns-3](https://www.nsnam.org/) - Network simulator, mostly focuses on wireless IP such as Wi-Fi, WiMAX, or LTE and routing protocols such as OLSR and AODV -- `C`
- [Open vSwitch (OVS)](http://openvswitch.org/) - Production quality software switch -- `C`
- [OpenFiler](https://www.openfiler.com/) - Linux-based NAS, supports most protocols and storage types -- `C`
- [Oracle VM VirtualBox](https://www.virtualbox.org/) - Easy, simple virtualization -- `C` `C++` `Windows` `OS X`
- [oVirt](https://www.ovirt.org/Home) - Virtualization management platform, the upstream for Red Hat Enterprise Virtualization (RHEV) -- `Java`
- [Packet Tracer](https://www.netacad.com/courses/packet-tracer-download/) - Cisco network simulator, by Cisco -- `closed source` `Windows` `OS-X`
- [pfsense](https://www.pfsense.org/) - The best firewall software, supports appliances and live CDs -- `C`
- [phpVirtualBox](http://sourceforge.net/projects/phpvirtualbox/) - Web front-end for VirtualBox -- `PHP`
- [QEMU (Quick EMUlator)](https://wiki.qemu.org/Main_Page) - Also supports hardware emulation (SPARC, RISC, etc) -- `C`
- [Seesaw](https://github.com/google/seesaw) - Load balancer based on Linux Virtual Server (LVS), by Google -- `Golang`
- [Shadow](https://github.com/shadow/shadow) - Network simulator that runs real applications like Tor and distributed systems of thousands of nodes on a single machine -- `C`
- [Squid](http://www.squid-cache.org/) - Reverse proxy, caching server, web traffic filter, and more -- `C++`
- [Traefik](https://github.com/containous/traefik) - Modern HTTP reverse proxy and load balancer, supports many backends -- `Golang`
- [Unicorn Engine](https://github.com/unicorn-engine/unicorn) - CPU emulator framework (ARM, AArch64, M68K, Mips, Sparc, X86) via QEMU -- `various lang`
- [virt-manager](https://virt-manager.org/) - KVM / Xen / LXC GUI -- `Python`
- [WANem (Wide Area Network Emulator)](http://wanem.sourceforge.net/) - WAN emulator -- `C`
- [WINE](https://www.winehq.org/) - Compatibility layer for running Windows apps on POSIX-compliant OSes -- `C` `OS X`
- [Xen](https://www.xenproject.org/) - It's a hypervisor! -- `C`
- [XenServer](https://xenserver.org/) - Successor to Xen Cloud Platform (XCP) -- `C`
- [xhyve](https://github.com/machyve/xhyve) - Lightweight OS X virtualization based on bhyve -- `C` `OS X`
- [ZeroTier](https://github.com/zerotier/ZeroTierOne) - Cloud / provider-agnostic private network backplanes, network virtualization -- `C++` `all platforms`

---

## VMware Tools

> Mostly unofficial VMware tools and scripts - see also [Virtualization and SDN](#virtualization-and-sdn)

- [Compliance Checker for vSphere](https://www.vmware.com/download/eula/compliance_checker.html) - Provides detailed compliance checks against vSphere hardening guidelines, official tool -- `closed source`
- [FastSCP](https://www.veeam.com/vmware-esxi-fastscp.html) - Super fast SCP client for Windows for moving stuff around in a VMware environment (ISOs, VMDKs between data stores, etc) -- `closed source`
- [Flings](https://labs.vmware.com/flings) - Tons of very useful apps written by VMware engineers, worth exploring A++++ -- `closed source?` `various lang`
- [Onyx](https://communities.vmware.com/community/vmtn/automationtools/onyx) - Do something in vSphere and it will create a PowerCLI script to do that thing that you just did -- `closed source` `PowerShell` `Windows`
- [open-vm-tools](https://github.com/vmware/open-vm-tools) - OSS alternative to VMware Guest Tools -- `C`
- [PowerCLI](https://my.vmware.com/web/vmware/details?downloadGroup=PCLI650R1&productId=614M) - VMware's CLI -- `closed source`
- [RVtools](https://www.robware.net/rvtools/) - Killer GUI for viewing information about your VMware environment -- `closed source` `.NET` `Windows`
- [RVtools Export](https://github.com/Sneddo/Powershell/blob/master/VMware/Export-RVTools.ps1) - Wrapper script to save daily snapshots of your environment using RVtools -- `PowerShell`
- [Sexigraph](http://www.sexigraf.fr/) - Graphite-based visualization appliance for Sexilog -- `various lang`
- [Sexilog](http://www.sexilog.fr/) - ELK stack virtual appliance designed for vSphere / VMware ESXi logs -- `various lang`
- [vCheck](https://github.com/alanrenouf/vCheck-vSphere) - Get an overview of a new environment or check the health of an existing one -- `PowerShell`
- [vDisk Informer](http://read.virtualizeplanet.com/?p=366) - Check vDisks alignment and see if they have wasted space -- `closed source` `Windows`
- [vGhetto Script Repository](https://github.com/lamw/vghetto-scripts) - Various scripts from virtuallyGhetto -- `various lang`
- [VMware Community PowerPack](http://en.community.dell.com/techcenter/powergui/m/powerpacks/20438900) - A variety of scripts from Virtu-al.net and now other blogs such as ict-freak.nl and ntpro.nl -- `lost-to-the-internet` `PowerShell`
- [VMware on Github](https://github.com/vmware) - VMware's Github repos -- `various lang`
- [VMware Sample Exchange](https://code.vmware.com/samples) - Code samples & scripts by both VMware and the community -- `various lang`
- [vSphere Health Check Report](https://github.com/lamw/vghetto-scripts/blob/master/perl/vmwarevSphereHealthCheck.pl) - Reports a massive amount of information, run it on a schedule -- `closed source` `perl`
- [vSphere Mobile Watchlist](https://communities.vmware.com/community/vmtn/vsphere/vsphere-mobile) - Monitor VMs on your phone -- `closed source` `mobile`

---

## VPNs and Tunnels

> VPN client & servers, tunneling proxies, DNS tunneling, simple host-to-host tunnels, and related tools - see also [SSL Tools](#ssl-tools) and [SSH Tools](#ssh-tools) and [Virtualization and SDN](#virtualization-and-sdn)

- [Algo VPN](https://github.com/trailofbits/algo) - IKEv2 Ubuntu-based strongSwan VPN server deployed to any cloud via Ansible -- `Python`
- [AutoVPN](https://github.com/ttlequals0/autovpn) - Spin up and autoconfigure OpenVPN instances in AWS -- `Python`
- [BrowserLeaks](https://browserleaks.com/) - See if info is leaking from your browser (your real IP when you're behind a VPN, etc) -- `in-browser`
- [CentOS 7 2FA VPN](https://github.com/rharmonson/richtech/wiki/CentOS-7-Minimal-&-Two-factor-Authentication-using-FreeRADIUS-3,-SSSD-1.12,-&-Google-Authenticator) - VPN with CentOS 7 + FreeRADIUS + SSSD + Google Authenticator -- `stepbystep`
- [Corkscrew](https://github.com/bryanpkc/corkscrew) - Tunnel SSH through HTTP proxies -- `C`
- [DNS Leak Test](https://www.dnsleaktest.com/) - See if DNS queries are leaking outside of your VPN / secured network -- `in-browser`
- [dnscrypt-proxy](https://github.com/jedisct1/dnscrypt-proxy) - DNS proxy, with support for modern encrypted DNS protocols such as DNSCrypt v2 and DNS-over-HTTP/2 -- `Golang`
- [dnscrypt-wrapper](https://github.com/Cofyc/dnscrypt-wrapper) - Add dnscrypt support to any resolver, server-side dnscrypt proxy -- `C`
- [fwknop (FireWall KNock OPerator)](http://www.cipherdyne.org/fwknop/) - Single Packet Authorization (SPA), authoriation packet from you opens firewall rules so only you can get in -- `various lang`
- [IP Leak](https://ipleak.net/) - Test to see if your browser is leaking information -- `in-browser`
- [kcptun](https://github.com/xtaci/kcptun) - Secure and fast tunnel based on KCP, can increase throughput -- `Golang`
- [localtunnel](https://localtunnel.me/) - Share a HTTP/web service on your local development machine without messing with DNS and firewall settings -- `JavaScript` `Windows` `OS X`
- [MACsec aka 802.1AE](https://en.wikipedia.org/wiki/IEEE_802.1AE) - Use me for confidentiality and integrity at layer 2, useful for WAN links -- `standard`
- [Magic Wormhole](https://github.com/warner/magic-wormhole) - Safely and simply send arbitrary-sized files and directories (or short pieces of text) from one computer to another -- `Python`
- [n2n](https://github.com/ntop/n2n) - L2 over L3 VPN that uses a peer-to-peer architecture -- `C`
- [nipe](https://github.com/GouveaHeitor/nipe) - A script to make Tor Network your default gateway -- `perl BOOYA`
- [OpenConnect](http://www.infradead.org/openconnect/) - Supports Cisco's AnyConnect SSL VPN -- `C`
- [OpenVPN](https://openvpn.net/) - The one and only -- `C`
- [Pritunl](http://pritunl.com/) - Distributed enterprise VPN server built using the OpenVPN protocol, supports Google sign-in -- `Python`
- [Project V](https://github.com/v2fly/v2ray-core) - A set of network tools that helps you to build your own computer network. It secures your network connections and thus protects your privacy, a newer Shadowsocks -- `Golang`
- [Shadowsocks](https://github.com/shadowsocks) - A secure socks5 proxy, designed to protect your Internet traffic -- `various lang` `most platforms`
- [SoftEther](http://www.softether.org/) - Perhaps the best VPN software out there -- `C`
- [spiped](https://www.tarsnap.com/spiped.html) - Create encrypted pipes between socket addresses using pre-shared keys (PSKs), similar to ssh -L -- `C`
- [sshttp](https://github.com/stealth/sshttp) - Port multiplexer that hides a SSH daemon behind HTTP, HTTPS, or SMTP on a single port -- `C`
- [sshuttle](https://github.com/sshuttle/sshuttle) - Transparent proxy server / VPN, doesn't need admin, forwards over SSH, supports DNS tunneling -- `Python` `OS X`
- [SSH Through or Over Proxy](https://daniel.haxx.se/docs/sshproxy.html) - How to create a HTTP(s) tunnel for your SSH traffic -- `article`
- [Streisand](https://github.com/StreisandEffect/streisand) - Set up a server running a wide variety of privacy software, so easy that grandma can use it, Ansible-based -- `Python`
- [strongSwan](https://www.strongswan.org/) - IPsec-based -- `C`
- [stunnel](https://www.stunnel.org/index.html) - Create simple TLS tunnels for existing services (eg: telnet, nc, etc) -- `C`
- [tinc](http://www.tinc-vpn.org/) - Simple, multi-platform VPN -- `C`
- [WireGuard](https://www.wireguard.com/) - Performant in-kernel VPN server with DJB Crypto and very modern primitives -- `C`
- [Ubuntu IKEv2 VPN Setup](https://github.com/jawj/IKEv2-setup) - Simple script that sets up a IKEv2 VPN with strongSwan on Ubuntu -- `shell`

---

## Web and HTTP Tools

> RPC is dead, long live RPC - see also [SSL Tools](#ssl-tools) and [Networking Tools](#networking-tools)

- [API Blueprint](https://apiblueprint.org/) - Supports bindings/plugins for many APIs -- `various lang`
- [Caddy](https://caddyserver.com/) - Web server with automatic TLS and more -- `Golang`
- [Fiddler](https://www.telerik.com/fiddler) - HTTP/HTTPS debugging proxy for any browser, system or platform -- `closed source`
- [gRPC](https://www.grpc.io/) - High performance RPC via HTTP/2, by Google -- `C`
- [h2i](https://github.com/golang/net/tree/master/http2/h2i) - Go's interactive HTTP/2 console debugger, send raw frames, etc -- `Golang`
- [Hamms](https://github.com/kevinburke/hamms) - Simulate/create connection failures, malformed response data, slow servers, fat headers, and more! -- `Python`
- [htaccess Snippits](https://github.com/phanan/htaccess) - Huge collection of common and useful .htaccess snippets, please contribute -- `collection`
- [http-traceroute](https://digi.ninja/projects/http_traceroute.php) - Shows the entire route including cookies, redirects, and response codes -- `Ruby`
- [httpdiff](https://github.com/jgrahamc/httpdiff) - Perform the same reuqest against two HTTP servers and diff the results -- `Golang`
- [httpie](https://github.com/jakubroztocil/httpie) - curl replacement with many new features -- `Python`
- [httptoolkit](https://github.com/httptoolkit/httptoolkit-server) - Open-source HTTP(S) debugging proxy, analyzer & client -- `Typescript`
- [htty](https://htty.github.io/htty/) - A console application for interacting with web servers -- `Ruby gem`
- [Huginn](https://github.com/cantino/huginn) - Build agents that perform automated tasks/workflows for you online or locally, like IFTTT -- `Ruby`
- [Insomnia REST Client](https://insomnia.rest/) - An alternative to POSTman, additional features -- `Electron` `Windows` `OS X` `Linux`
- [Ionic Framework](https://ionicframework.com/) - Mobile UI kit that allows you to write multi-platform mobile apps in JS, Angular, Vue, or React - no Swift or Android knowledge needed -- `various lang`
- [JSON Server](https://github.com/typicode/json-server) - Full fake REST API for quickly prototyping and mocking in 30 seconds -- `JavaScript`
- [jq](https://stedolan.github.io/jq/) - Command line JSON processor and manipulator -- `C`
- [localtunnel](https://localtunnel.me/) - Share a HTTP/web service on your local development machine without messing with DNS and firewall settings -- `JavaScript` `Windows` `OS X`
- [mitmproxy](https://mitmproxy.org/) - Intercept, modify, replay and save HTTP/S traffic - even edit flows on the fly -- `Python pip`
- [mountebank](http://www.mbtest.org/) - Stub downstream resources for testing, supports HTTP HTTPS SMTP TCP -- `JavaScript` `Windows` `OS X`
- [Newman](https://github.com/postmanlabs/newman) - CLI companion for Postman -- `JavaScript`
- [nghttp](https://nghttp2.org/documentation/nghttp.1.html) - CLI HTTP/2 client, similar to curl/wget and more -- `C`
- [nginxconfig](https://nginxconfig.io/) - Web-based nginx config generator -- `in-browser`
- [ngrok](https://ngrok.com) - Reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service and captures & analyzes all traffic over the tunnel for later inspection and replay -- `rocks` `Golang`
- [OpenResty](https://openresty.org/) - Turn nginx into a non-blocking API server -- `C`
- [PageKite](https://pagekite.net/) - Makes HTTP servers or SSH publicly available on any server -- `Python`
- [POSTman](https://www.getpostman.com/) - Create and share API and HTTP requests, great for testing and sharing -- `Chrome`
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Provides a high-level API to control headless Chrome over the DevTools Protocol -- `JavaScript`
- [Pushpin](http://pushpin.org/) - Proxy server that adds WebSockets to existing request-response APIs -- `C++`
- [react-admin](https://github.com/marmelab/react-admin) - Add an React admin GUI to any RESTful API -- `JavaScript`
- [Redirect Detective](http://redirectdetective.com/) - See the complete path a redirected URL goes through -- `in-browser`
- [Repose](http://openrepose.org/) - REST proxy, solutions to API tasks such as auth, rate limiting, API validation, HTTP logging, and much more -- `Java`
- [Resty](https://github.com/micha/resty) - CLI REST client you can use in shell/bash/zsh pipes -- `shell`
- [SecurityHeaders.io](https://securityheaders.io) - Scan your web site's HTTP headers -- `in-browser`
- [Swagger](https://swagger.io/) - Popular API development library, now the OpenAPI standard -- `various lang`
- [tengine](https://github.com/alibaba/tengine) - A distribution of Nginx with some advanced features, by Alibaba -- `C`
- [tortilla](https://github.com/redodo/tortilla) - Easily wrap web APIs -- `Python pip`
- [Tyk](https://tyk.io/) - API gateway -- `Golang`
- [urlscan.io](https://urlscan.io/) - Displays tons of stats and info about any given URL -- `in-browser`
- [Varnish](https://www.varnish-cache.org/) - Caching HTTP accelerator -- `C`
- [vcr](https://github.com/vcr/vcr) - Record and play back HTTP sessions -- `Ruby gem`
- [webhook](https://github.com/adnanh/webhook/) - Super simple webhook server -- `Golang`
- [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection (menu-based) -- `Golang`

---

## Web and HTTP Performance Analysis Tools

> Load generation, debugging, benchmarking, and profiling for SaaS, webapps, and HTTP(S) - see also [Performance Analysis Tools](#performance-analysis-tools) and [Network Performance Analysis Tools](#network-performance-analysis-tools)

- [Awesome Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo) - Collection of web performance optimization (WPO) tools, articles, and more -- `collection`
- [Betwixt](https://github.com/kdzwinel/betwixt) - Web debugging proxy with a Chrome DevTools look -- `JavaScript`
- [Brotli](https://en.wikipedia.org/wiki/Brotli) - Modern alternative to gzip, better packing, performs well with HTTP/2, HTTPS only -- `zoooooom`
- [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar) - Panels that display profiling information about the current request/response -- `Python pip`
- [Chrome DevTools](https://developer.chrome.com/devtools) - Many built-in tools for performance analysis -- `mostly OSS`
- [Gatling](https://gatling.io/) - HTTP, JMS, and WebSocket load generator -- `Scala`
- [Google Web Tracer](http://www.gwtproject.org/) - Helps you identify and fix performance problems in your web applications, by Google -- `Chrome`
- [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) - A full list of built-in Firefox developer tools including performance tools -- `various lang`
- [h2load](https://nghttp2.org/documentation/h2load.1.html) - HTTP/2 and SPDY load generation tool, part of the nghttp2 suite -- `C`
- [HAR Analyzer](https://toolbox.googleapps.com/apps/har_analyzer/) - HTTP Archive analyzier for troubleshooting from a browser perspective, by Google -- `in-browser`
- [httping](http://www.vanheusden.com/httping/) - Simple program that "pings" a URL and shows response time -- `C`
- [Jaeger](https://github.com/jaegertracing/jaeger) - OpenTelemetry compatible distributed tracing system, works well with Istio and Envoy, by Uber -- `Golang`
- [JMeter](https://jmeter.apache.org/) - Designed to load test functional behavior and measure performance, written in Java -- `Java`
- [Locust](https://locust.io/) - Load generation tool written in Python that allows you to define user behavior -- `Python`
- [ngxtop](https://github.com/lebinh/ngxtop) - Real time top for nginx -- `Python`
- [OpenTelemetry](https://opentelemetry.io/) - Vendor-neutral distributed tracing, a merger of OpenTracing and OpenCensus -- `various lang`
- [OpenZipkin](https://zipkin.io/) - Distributed tracing systems for SaaS and webapps, by Twitter, based on Google's Dapper -- `Scala`
- [Packetbeat](https://www.elastic.co/products/beats) - Distributed packet monitoring system that can be used for application performance management -- `Golang`
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Analyzes the content of a web page, then generates suggestions to make that page faster, by Google -- `in-browser`
- [PageSpeed Module](https://developers.google.com/speed/pagespeed/module) - Open-source server modules that optimize your site automatically (nginx and Apache), by Google -- `various lang`
- [peep](https://github.com/evan/peep) - Heap inspector for live memcached instances -- `Ruby`
- [redis-faina](https://github.com/facebookarchive/redis-faina) - Query analyzer that parses Redis' MONITOR command for counter/timing stats about query patterns, by Facebook -- `Python`
- [Tsung](http://tsung.erlang-projects.org/) - Distributed stress tester, also supports stress testing DBs -- `Erlang`
- [Web Page Test](http://www.webpagetest.org/) - Free website speed test from multiple locations around the globe using real browsers (IE and Chrome) and at real consumer connection speeds -- `in-browser`
- [wrk](https://github.com/wg/wrk) - Multi-threaded CLI-based HTTP load generation tool -- `C`
- [wrk2](https://github.com/giltene/wrk2) - Fork of wrk that fixes the "coordinated omissions problem" -- `C`
- [UpTrends Uptime Checker](https://www.uptrends.com/tools/uptime) - Check a URL's response time from ~30 different sites around the globe -- `in-browser`
- [Varnish Dashboard](https://github.com/brandonwamboldt/varnish-dashboard) - Realtime dashboard for Varnish cache servers -- `JavaScript`

---

## Misc Tools of Note

> Everything else

- [Adblock Radio](https://github.com/adblockradio/adblockradio) - An adblocker for live radio streams and podcasts -- `various lang`
- [Anti-Ablock Killer](https://reek.github.io/anti-adblock-killer/) - Keep your ad-blocker active when pages take anti-blocking measures, requires Greasemonkey or similar -- `JavaScript`
- [AppLock](https://play.google.com/store/apps/details?id=com.sp.protector.free) - Lock individual apps on Android -- `Java`
- [Architecture Decision Record](https://github.com/joelparkerhenderson/architecture_decision_record) - Document that captures an important architectural decision made along with its context and consequences -- `template`
- [AutoIT](https://www.autoitscript.com/site/) - Scriptable GUI input for Windows (think AutoHotKey) but with a BASIC-like syntax -- `closed source`
- [Backstage](https://github.com/backstage/backstage) - Unifies all your infrastructure tooling, services, and documentation with a single, consistent UI so developers can easily provision and view their resources -- `various lang`
- [Bypass Paywalls](https://github.com/iamadamdev) - Shhh -- `Firefox` `Chrome`
- [Clone Wars](https://github.com/GorvGoyl/Clone-Wars) - Open-source clones of popular sites like Airbnb, Amazon, Instagram, Netflix, Tiktok, Spotify, Trello, Whatsapp, Youtube, etc -- `various lang`
- [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian) - Rules engine for managing public cloud accounts and resources via policies, by Capital One -- `various lang`
- [conserver](http://www.conserver.com/) - Virtual console server with many features (multi-user, console log history, etc) -- `C`
- [Cookie Autodelete](https://www.google.com/search?&q=cookie+autodelete) - Browser add-on that's essentially a cookie whitelist / grey list -- `Firefox` `Chrome`
- [CRIU (Checkpoint Restore in Userspace)](https://criu.org/Main_Page) - Freeze a process, save it to disk, then resume it later -- `insane`
- [crumbs](https://github.com/lucasepe/crumbs) - Simple mind maps with asterisks - great for brain dumping with little transcription overhead -- `Golang`
- [Dashkiosk](https://github.com/vincentbernat/dashkiosk) - Manage dashboards on multiple screens, simple and effective -- `JavaScript`
- [Domain Block List](https://oisd.nl/) - The only Pi Hole blocklist you'll need -- `collection`
- [Etcher](https://www.balena.io/etcher/) - SD card writing software, easy -- `various lang`
- [f.lux](https://justgetflux.com/) - Changes your screen from blue light to yellow light when the sun sets to tell your brain it's night time -- `closed source` `OS X` `Windows`
- [FigmaToCode](https://github.com/bernaferrari/FigmaToCode) - Outputs Figma objects to Tailwind, Flutter, or SwiftUI code -- `JavaScript`
- [Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/) - Cookies are separated by container, allowing you to use the web with multiple identities or accounts simultaneously -- `Firefox`
- [Fossor](https://github.com/linkedin/fossor) - Automate on-call investigation steps, by LinkedIn -- `Python pip`
- [Geocities-izer](http://www.wonder-tonic.com/geocitiesizer/) - Make any HTML web page look like a Geocities page -- `sweeeeeeet`
- [googler](https://github.com/jarun/googler) - Google search, news, and site search from the terminal, slick -- `Python`
- [Google Advanced Operators for Web Search](https://sites.google.com/site/gwebsearcheducation/advanced-operators) - Search modifiers for more accurate results, by Google -- `collection`
- [GoodRX](https://www.goodrx.com) - Coupons for prescriptions, vaccines, and more, can be used pre-deductible, USA-centric -- `ez savings`
- [gosu](https://github.com/tianon/gosu) - Simple Go-based setuid+setgid+setgroups+exec for stepping down privs, use me to avoid weird su and sudo TTY bugs -- `Golang`
- [Highlight This](https://chrome.google.com/webstore/detail/highlight-this-finds-and/fgmbnmjmbjenlhbefngfibmjkpbcljaj) - Multi-highlight, regex, all data local, tons of features -- `Chrome`
- [Homomorphic Encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption) - Allows data to be encrypted and out-sourced to 3rd parties for processing, all while encrypted (or remove HIPAA barriers) -- `article`
- [HTTPS Everywhere](https://www.eff.org/https-everywhere) - Uses client-side tricks to force misconfigured sites to use HTTPS all the time, by the EFF (donate) -- `Firefox` `Chrome`
- [Huginn](https://github.com/cantino/huginn) - Build agents that perform automated tasks/workflows for you online or locally, like IFTTT -- `Ruby`
- [ICANN Domain Lookup](https://lookup.icann.org/) - Use this when searching for a domain to buy because they cannot use your searches to jack up the price -- `in-browser`
- [inxi](https://github.com/smxi/inxi) - "a full featured system information script" (hardware info, etc) -- `shell`
- [IPTV](https://github.com/iptv-org/iptv) - Collection of 8000+ publicly available IPTV channels from all over the world -- screw off Bundesliga -- `collection`
- [Library Extension](https://www.libraryextension.com/) - Browser extension that shows you which Amazon books are available free at your local libraries, please donate -- `closed source`
- [Locast](https://www.locast.org/) - Watch your local broadcast TV for free on any device, USA geo-locked, **please donate** -- `all platforms!`
- [Mail Tester](https://www.mail-tester.com/) - Test the spammyness of your e-mails -- `in-browser`
- [maybe](https://github.com/p-e-w/maybe) - Allows a dry run of almost any Linux binary, see the files it will modify, calls made, etc -- `Python pip`
- [Maza](https://github.com/tanrax/maza-ad-blocking) - Like Pi-hole but local and using your operating system -- `shell`
- [Mjolnir](https://github.com/sdegutis/mjolnir) - Automation for OS X, think AutoHotKey for Mac -- `C` `OS X`
- [MultiRBL](http://multirbl.valli.org/) - SMTP blackhole lookup tools -- `in-browser`
- [MX Toolbox](https://mxtoolbox.com/) - SMTP blacklist lookup, header analysis, and more -- `in-browser`
- [Network UPS Tools (NUT)](http://www.networkupstools.org/) - Manage power devices from over 100 manufacturers using a single web interface -- `C` `Windows`
- [NoRoot Firewall](https://play.google.com/store/apps/details?id=app.greyshirts.firewall&hl=en_US) - Android app that logs connections to show overly chatty background apps and more -- `closed source`
- [NoScript](https://noscript.net/) - JavaScript, XSS, tracker, Flash blockers and more - your condom for the Internet -- `Firefox`
- [oauth2_proxy](https://github.com/pusher/oauth2_proxy) - A reverse proxy that provides authentication with Google, Github or other provider -- `Golang`
- [Omni Calculator](https://www.omnicalculator.com/) - 1500+ free calculators -- `collection`
- [oomd](https://github.com/facebookincubator/oomd) - Userspace OOM killer, highly configurable and much improved over the kernel's built in OOM killer -- `C++`
- [Open19](https://www.open19.org/) - Open data center hardware for standard size racks -- `neat`
- [OpenBMC](https://github.com/facebook/openbmc) - Framework to build a complete Linux image for a Board Management Controller (BMC), by Facebook -- `C`
- [OpenHaystack](https://github.com/seemoo-lab/openhaystack) - Framework for tracking personal Bluetooth devices via Apple's massive Find My network, build your own Airtags -- `various lang`
- [PeerTube](https://joinpeertube.org/) - P2P version of YouTube, don't let your videos get taken down, now supports live streaming -- `free as in freedom`
- [Pi-Hole](https://pi-hole.net/) - Ad and tracking blackhole that covers your entire network with a single device -- `hardware`
- [PineTime](https://www.pine64.org/pinetime/) - An open source smartwatch -- `hardware`
- [Popcorn Time](https://github.com/popcorn-official/popcorn-desktop) - Multi-platform, free software BitTorrent client that includes an integrated media player -- `various lang`
- [Privacy Badger](https://www.eff.org/privacybadger) - The best in-browser privacy and anti-tracking tool, by the EFF (donate) -- `Chrome` `Firefox`
- [PrivacyTools.io](https://www.privacytools.io/) - All in one collection, web site source is on GitHub -- `collection`
- [Puffer](https://puffer.stanford.edu/) - Re-transmits free over-the-air broadcast television signals received by an antenna located on the campus of Stanford University, USA geo-locked, by Stanford Platform Lab and many others -- `in-browser` `Android`
- [repl.it](https://repl.it/languages) - In-browser REPLs for a ton of languages -- `in-browser`
- [RISC-V](https://riscv.org/) - The open source CPU that can run at >5Ghz while using 1/100th the power of a Xeon E7 -- `hardware`
- [Rocky Linux](https://rockylinux.org/) - A replacement for CentOS which was discontinued in Dec 2020 by IBM in favor of CentOS Stream -- `operating system`
- [runwhen](http://code.dogmap.org/runwhen/) - Utilities for running commands at particular times, cron on steroids -- `C`
- [Say What](https://github.com/joshnewlan/say_what) - Using speech-to-text to fully check out during conference calls -- `Python`
- [scrcpy](https://github.com/Genymobile/scrcpy) - Remote display and control of Android devices connected on USB or TCP/IP -- `C`
- [Spectacle](https://www.spectacleapp.com/) - Control desktop windows via keyboard shortcuts -- `Objective C`
- [StackStorm](https://github.com/StackStorm/st2) - IFTTT for Ops -- `Python`
- [Steps Recorder (aka Problem Steps Recorder)](https://support.microsoft.com/en-us/help/22878/windows-10-record-steps) - Windows 7+, user records themselves reproducing a problem, they send video to you, you playback -- `closed source`
- [Twilight](https://play.google.com/store/apps/details?id=com.urbandroid.lux&hl=en) - F.lux for Android -- `closed source`
- [uBlock Origin](https://github.com/gorhill/uBlock) - Ad blocker, only use Origin, do not use another uBlock -- `Firefox` `Chrome`
- [unPaywall](https://unpaywall.org/) - When you view a paywalled scholarly article, Unpaywall automatically checks its open database of 28 million legal, open-access articles and tells you if you can get it elsewhere for free -- `JavaScript`
- [WhosHere](https://github.com/curtbraz/whoshere) - Monitor an area for WiFi and Bluetooth probe requests to see when people (devices) come and go, with web UI and IFTTT webhook integraiton for Slack/SMS pushes -- `PHP`

---

## Learning Resources

> Free learning resources and collections of note (DevOps/SRE, cloud, information security, Kubernetes, Docker/containers, Python, Golang)

- [30 Seconds of Code](https://www.30secondsofcode.org/) - Code snippets for tons of languages -- `collection`
- [4+1 architectural view model](https://en.wikipedia.org/wiki/4%2B1_architectural_view_model) - View model used for describing the architecture of software-intensive systems, based on the use of multiple, concurrent views (logical, physical, development, process) -- `article`
- [A Gentle Introduction to Kubernetes](https://github.com/eon01/kubernetes-workshop) - With more than just the basics -- `tutorial`
- [A giant list of Google Cloud resources](https://cloud.google.com/blog/topics/developers-practitioners/giant-list-google-cloud-resources) - From Google -- `collection`
- [A Practical Guide to (Correctly) Troubleshooting with Traceroute](https://www.nanog.org/sites/default/files/10_Roisman_Traceroute.pdf) - Presentation, really digs in -- `article`
- [A Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/) - Concise breakdown, by Red Hat -- `article`
- [A Visual Guide to Troubleshooting Kubernetes Deployments](https://learnk8s.io/troubleshooting-deployments) - With flowcharts -- `handy`
- [Algorithms, 4th Edition](https://algs4.cs.princeton.edu/home/) - 100% free high quality ebook from Princeton -- `book`
- [Amazon Builder's Library](https://aws.amazon.com/builders-library) - Amazon shares their learnings -- `articles`
- [An Illustrated Guide to Kubernetes Networking](https://morioh.com/p/ecb38c8342ba/an-illustrated-guide-to-kubernetes-networking) - See title -- `article`
- [An Introduction to Distributed Systems](https://github.com/aphyr/distsys-class) - by Aphyr -- `tutorial`
- [Ansible Examples](https://github.com/ansible/ansible-examples) - Shows features and how they work together, a great hands-on, official -- `tutorial`
- [Ansible for DevOps](https://www.ansiblefordevops.com/) - The recommended book to learn Ansible -- `book`
- [Ansible Interactive Tutorial](https://github.com/turkenh/ansible-interactive-tutorial) - Interactive tutorials for Ansible via Docker, super simple -- `tutorial`
- [Ansible Automation Platform Workshops](https://ansible.github.io/workshops/) - Workshops, training decks, and guides, by Red Hat -- `tutorials`
- [Application Layer Transport Security](https://cloud.google.com/security/encryption-in-transit/application-layer-transport-security/) - Use mutual TLS to secure RPC calls between entities, designed with containers and microservices in mind -- `article`
- [arc42 Documentation](https://arc42.org/documentation/) - Pragmatic, open source way to construct, communicate and document your software architecture -- `tutorial`
- [Architecture of Open Source Applications](http://www.aosabook.org/en/) - The authors of four dozen open source applications explain how their software is structured, and why -- `collection`
- [Archive.org aka The Internet Archive aka The Wayback Machine](https://archive.org/) - Yo donate, this is beyond important -- `the biggest collection`
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) - Exceptional -- `book`
- [Awesome](https://github.com/sindresorhus/awesome) - Top level list of awesome lists -- `collection`
- [Awesome AWS](https://github.com/donnemartin/awesome-aws) - Curated list of AWS resources -- `collection`
- [Awesome AWS Workshops](https://awesome-aws-workshops.com/) - Dozens of free interactive AWS workshops covering almost every major service (unofficial) -- `tutorial`
- [AutoHotKey](https://autohotkey.com/) - Automate input (desktop and web forms, data entry, keybinds, etc) -- `C++` `Windows`
- [Awesome AutoHotKey](https://github.com/ahkscript/awesome-AutoHotkey) - A collection of AutoHotKey scripts and libraries -- `various lang`
- [Awesome System Design](https://github.com/madd86/awesome-system-design) - System Designing articles, videos and resources for distributed computing -- `collection`
- [AWS Architecture Center](https://aws.amazon.com/architecture/) - Reference architecture diagrams, vetted architecture solutions, Well-Architected best practices, patterns, icons, and more -- `collection`
- [AWS Breaking Changes](https://github.com/SummitRoute/aws_breaking_changes) - List of changes announced for AWS that may break existing code -- `collection`
- [AWS CDK Workshop](https://cdkworkshop.com/) - AWS CDK workshop, official -- `tutorial`
- [AWS CLI Cheat Sheet](https://github.com/eon01/AWS-CheatSheet) - See name -- `tutorial`
- [AWS Hands-On Tutorials](https://aws.amazon.com/getting-started/hands-on/?awsf.getting-started-content-type=content-type%23hands-on) - From Amazon - `collection`
- [AWS - Overview of Amazon Web Services](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html) - Amazon's official guide, a few paragraphs for each -- `collection`
- [AWS Security Maturity Roadmap](https://summitroute.com/downloads/aws_security_maturity_roadmap-Summit_Route.pdf) - A series or actionable steps to improve the security of their AWS environments, updated annually -- `collection`
- [AWS Security Reference Architecture](https://docs.aws.amazon.com/prescriptive-guidance/latest/security-reference-architecture/architecture.html) - Updated mid-2021 -- `collection`
- [AWS Solutions Library](https://aws.amazon.com/solutions/) - Includes reference architectures -- `collection`
- [AWS Stash](https://awsstash.com/) - A collection of AWS related videos, podcasts, code repositories, whitepapers, and feature releases, all in a single, easy to search interface -- `collection`
- [AWS Video Catalog](https://www.awsvideocatalog.com/) - All official AWS videos cataloged and categorized (by topic, by year, etc) -- `collection`
- [AWS Well Architected Labs](https://wellarchitectedlabs.com/) - Hands on training and labs -- `collection`
- [AWS Workshops](https://workshops.aws/) - The official list of 100+ free AWS workshops -- `collection`
- [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/) - Guidance for architecting solutions on Azure using established patterns and practices -- `collection`
- [Azure DevOps Labs](https://azuredevopslabs.com/) - Self-paced -- `training`
- [Azure in Bullet Points](https://github.com/undergroundwires/Azure-in-bullet-points) - Super fast way to learn Azure and prep for certifications at the same time -- `collection`
- [Azure Master Class](https://www.youtube.com/playlist?list=PLlVtbbG169nGccbp8VSpAozu3w9xSQJoY) - Hands on free training by John Savill -- `training`
- [Azure Security Best Practices Checklist](https://nuvento.com/blog/top-100-azure-security-best-practices-checklist/) - A list of 100 items -- `collection`
- [Bandit](http://overthewire.org/wargames/bandit/) - A "wargame" that teaches the user how to use Linux -- `neat`
- [BBR NKOTB](https://blog.apnic.net/2017/05/09/bbr-new-kid-tcp-block/) - Excellent article that explains BBR and compares it to traditional TCP congestion and loss algorithms -- `article`
- [Beyond the 12 Factor App](https://tanzu.vmware.com/content/ebooks/beyond-the-12-factor-app) - Free ebook, by Pivotal -- `book`
- [blktrace how-to](https://old.reddit.com/r/sysadmin/comments/1ib3rl/beyond_iostat_storage_performance_analysis_with/) - `mount -t debugfs debugfs /sys/kernel/debug && blktrace -d /dev/md2 -o - | blkparse -i -` -- `article`
- [Bookshop.org](https://bookshop.org/) - Bookshop is an online bookstore with a mission to financially support local, independent bookstores - ditch Amazon! -- `check it`
- [Borg, Omega, and Kubernetes - Lessons Learned from 3 Container Management Systems Over a Decade](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44843.pdf) - Paper by Google -- `article`
- [Building Secure & Reliable Systems](https://static.googleusercontent.com/media/sre.google/en//static/pdf/building_secure_and_reliable_systems.pdf) - The third SRE book from Google, free -- `book`
- [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/) - Follow along -- `tutorial`
- [C4 Model](https://c4model.com/) - A modern approach for visualising software architecture -- `article`
- [Chaos Engineering](https://www.oreilly.com/webops-perf/free/chaos-engineering.csp) - Building confidence in system behavior through experiments, free book by Netflix -- `book`
- [Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/) - Useful for building reliable, scalable, secure applications in the cloud, by Microsoft -- `collection`
- [Cloud Native DevOps with Kubernetes](https://www.nginx.com/resources/library/cloud-native-devops-with-kubernetes/) - Full book -- `book`
- [Cloud Native Landscape](https://github.com/cncf/landscape) - A map that attempts to categorize most of the projects and product offerings in the cloud native space -- `collection`
- [Command Line Text Processing](https://github.com/learnbyexample/Command-line-text-processing) - awk grep sed etc - interactive tutorial for newbies -- `tutorial`
- [Common Python Mistakes](https://news.ycombinator.com/item?id=7715349) - Link and discussion on HN -- `article`
- [Comprehensive Python Cheatsheet](https://gto76.github.io/python-cheatsheet/) - Includes many modules -- `collection`
- [Computer Science Flash Cards](https://github.com/jwasham/computer-science-flash-cards) - As described, can be converted into an Anki deck -- `Python`
- [Container Training](https://container.training/intro-selfpaced.yml.html#1) - Self paced and interactive, formerly Intro to Docker -- `training`
- [Cool Store](https://github.com/vietnam-devs/coolstore-microservices) - An exercise to wire up small microservices into a larger application -- `tutorial`
- [curl Exercises](https://jvns.ca/blog/2019/08/27/curl-exercises/) - Exercises for the 'curl' command -- `tutorial`
- [Cybersecurity Canon](https://icdt.osu.edu/cybercanon) - A Rock & Roll Hall of Fame for cybersecurity books -- `collection`
- [Databases by Daniel Soper](https://www.youtube.com/watch?v=4Z9KEBexzcM&list=PL1LIXLIF50uXWJ9alDSXClzNCMynac38g&index=1) - From the ground up, personally recommended -- `tutorial`
- [Design Patterns](https://sourcemaking.com/design_patterns) - Wonderful collection of software development design patterns with examples, includes anti-patterns and refactoring guidelines -- `collection`
- [Design Patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans) - An ultra-simplified explanation of repeatable software design patterns -- `article`
- [Design Patterns in Python](https://refactoring.guru/design-patterns/python) - See title -- `article`
- [Designing Data Intensive Applications - Book Notes](https://hoanhan101.github.io/2020/07/05/design-data-intensive-apps) - The one you need -- `book`
- [DevDocs](https://devdocs.io/) - Documentation browser for almost every API -- `collection`
- [Devhints](https://devhints.io/) - Rico's dev & ops cheat sheets, nice little collection -- `collection`
- [DevOps Maturity Framework](https://github.com/adidas/adidas-devops-maturity-framework/blob/master/framework/devops_maturity_framework.md) - Categorized by crawl/walk/run, also Google terms like "DevOps maturity model" for similar ideas, by Adidas -- `tutorial`
- [DevOps Conferences](http://www.gotodevops.org/) - Add and remove via PR, please contribute -- `collection`
- [Discount for Student Dev](https://github.com/AchoArnold/discount-for-student-dev) - Programming and DevOps related discounts for .edu addresses, updated frequently, please contribute -- `collection`
- [Docker Curriculum](https://docker-curriculum.com/) - One-stop shop for getting your hands dirty with Docker -- `tutorial`
- [Docker Handbook](https://docker.farhan.info/) - Free book contributions welcome -- `book`
- [Docker Security Cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html) - By OWASP -- `tutorial`
- [Dog vs. Cat: Docker Swarm Stacks](https://github.com/BretFisher/dogvscat) - Examples for building full Swarm-based clusters including proxies, centralized logging, persistent storage, deployment pipelines, and more -- `tutorial`
- [Easy-Python](https://easy-python.readthedocs.org) - Collection of Python resources that "you didn't know you would need" -- `collection`
- [Effective Engineer](https://gist.github.com/rondy/af1dee1d28c02e9a225ae55da2674a6f) - Notes from the book The Effective Engineer -- `book`
- [EKS Best Practices](https://aws.github.io/aws-eks-best-practices/) - By Amazon, contributions welcome -- `collection`
- [Enterprise Architecture on a Page](http://eaonapage.com/) - One-page aggregated view of popular EA artifacts used in organizations with their most essential properties -- `tutorial`
- [Every Programmer Should Know...](https://github.com/mtdvio/every-programmer-should-know) - A collection of (mostly) technical things every software developer should know -- `collection`
- [Everything AWS](https://app.polymersearch.com/discover/aws) - The best way to browse the 6k+ AWS repos -- `collection`
- [Everything You Should Know About Certificates and PKI](https://smallstep.com/blog/everything-pki.html) - Easy to understand tutorial -- `tutorial`
- [Explain Shell](https://explainshell.com/) - Enter a command-line to see the help text that matches each argument -- `in-browser`
- [free-for.dev](https://free-for.dev/) - Massive list of services with free tiers -- `collection`
- [Free Programming Books](https://ebookfoundation.github.io/free-programming-books/) - Thousands -- `collection`
- [GKE Demo](https://github.com/ilya-lesikov/gke-demo) - Demonstration of complete, fully-featured CI/CD and cloud automation for microservices, done with GCP/GKE -- `various lang`
- [GlossaryTech](https://glossarytech.com/) - Browser addon to learn tech terms with easy to understand defintions -- `JavaScript`
- [go-perfbook](https://github.com/dgryski/go-perfbook) - Outlines best practices for writing high-performance Go code -- `article`
- [Go by Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs -- `tutorial`
- [Go Tooling In Action](https://github.com/campoy/go-tooling-workshop) - A workshop covering all the tools used in the day to day life of a Golang dev -- `tutorial`
- [Good Sleep, Good Learning, Good Life](http://super-memory.com/articles/sleep.htm) - Compiled knowledege about sleep with sources and citations -- `zzz`
- [Google Cloud Architecture Center](https://cloud.google.com/architecture) - Reference architectures, diagrams, design patterns, guidance, and best practices for building or migrating your workloads on Google Cloud -- `collection`
- [Google Cloud Microservices Demo](https://github.com/GoogleCloudPlatform/microservices-demo) - Sample cloud-native application with 10 microservices showcasing Kubernetes / GKE, Istio, gRPC and OpenCensus -- `various lang`
- [Google's Technical Development Guide](https://techdevguide.withgoogle.com/) - Hands on, free, self-paced courses to help you develop your programming skills -- `collection`
- [Gophercises](https://gophercises.com/) - Golang exercises -- `collection`
- [Hashicorp Learn](https://learn.hashicorp.com/) - Official training for Vault, Consul, Terraform, Vagrant, Packer, and Nomad -- `training`
- [HEAD](https://htmlhead.dev/) - A free guide to HTML5 <head> elements -- `collection`
- [High Performance Browser Networking](https://hpbn.co/) - What every web developer needs to know about the various types of networks (WiFi, 3G/4G), transport protocols (UDP, TCP, and TLS), application protocols (HTTP/1.1, HTTP/2), and APIs available in the browser (XHR, WebSocket, WebRTC, and more) -- `book`
- [Hoopla](https://www.hoopladigital.com/) - Digital movies, music and ebooks for USA public library members -- `explore yours today`
- [How Complex Systems Fail](https://how.complexsystems.fail/) - Paper by MIT, a great read for operations -- `article`
- [How They SRE](https://github.com/upgundecha/howtheysre) - A curated collection of publicly available resources on how technology and tech-savvy organizations around the world practice Site Reliability Engineering (SRE) -- `collection`
- [How to Ask Good Questions](https://jvns.ca/blog/good-questions/) - By Julia Evans -- `article`
- [How to Ask Questions the Smart Way](http://www.catb.org/esr/faqs/smart-questions.html) - By the ESR -- `article`
- [HTTP/3 Explained](https://daniel.haxx.se/http3-explained/) - QUIC = next generation TCP via UDP to bypass TCP's bad algos, used in HTTPv3 by haxx -- `book`
- [HTTP API Design Guide](https://geemus.gitbooks.io/http-api-design/content/en/index.html) - A good, consistent, well-documented way to design APIs, not necessarily the only/ideal way -- `book`
- [IF4IT SDLC](http://www.if4it.com/SYNTHESIZED/FRAMEWORKS/SDLC/sdlc_framework.html) - A more detailed and concise SDLC -- `tutorial`
- [In Defense of Swap](https://chrisdown.name/2018/01/02/in-defence-of-swap.html) - Well informed article about why you need some swap -- `article`
- [Interactive Coding Challenges](https://github.com/donnemartin/interactive-coding-challenges) - 120+ interactive Python coding interview challenges (algorithms and data structures), includes Anki flashcards -- `Python`
- [Interlibrary Loan](https://en.wikipedia.org/wiki/Interlibrary_loan) - If your local library doesn't have a book or DVD in their collection they can use this service to order it from another library so you can borrow it out -- `i'm learnding`
- [Introduction to Cloud Infrastructure Technologies](https://github.com/darshanime/notes/blob/master/cloud.org) - Notes from the superb course on edX -- `collection`
- [Introduction to Kubernetes](https://github.com/darshanime/notes/blob/master/kubernetes.org) - Notes from the Introduction to Kubernetes course on edX -- `collection`
- [Introduction to Linux](https://www.edx.org/course/introduction-to-linux) - Endorsed by Linus himself, via edX -- `course`
- [ITIL v4 Foundation Training](https://www.youtube.com/watch?v=Edn4-SAHT0Q&list=PLU0hwmH1hdn1kN22e6EW_W0uzVbJy11nR) - Learn it all in about 6 hours -- `tutorial`
- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - JavaScript based examples of many popular algorithms and data structures -- `JavaScript`
- [JVM Internals](http://blog.jamesdbloom.com/JVMInternals.html) - A superb explanation of how the Java JVM works in easy to understand terms -- `collection`
- [Kanopy](https://www.kanopystreaming.com/) - Streaming movies for USA public library members -- `explore yours today`
- [Katacoda](https://www.katacoda.com/learn) - In-browser labs and exercises with modern DevOps tools -- `way cool`
- [Kubernetes Academy](https://kubernetes.academy/) - k8s and containers tutorials as well as k8s certification preparation, by VMware -- `tutorial`
- [Kubernetes and Service Mesh Workshop](https://github.com/peterj/workshop-material) - 100% local, no need for cloud or additional hardware -- `tutorial`
- [Kubernetes by Example](http://kubernetesbyexample.com/) - By the RedHat OpenShift team -- `tutorial`
- [Kubernetes Clusters for the Hobbyist](https://github.com/hobby-kube/guide) - How to securely run Kubernetes on providers that don't have ELBs, private networking, or persistent distributed storage (Hetzner Cloud, DigitalOcean or Scaleway) -- `guide`
- [Kubernetes Failure Stories](https://k8s.af/) - Post mortems of Kubernetes outages, great way to learn -- `collection`
- [Kubernetes Patterns](https://www.redhat.com/cms/managed-files/cm-oreilly-kubernetes-patterns-ebook-f19824-201910-en.pdf) - Free ebook from Red Hat and O-Reilly -- `book`
- [Kubernetes Production Best Practices](https://learnk8s.io/production-best-practices) - Checklist -- `collection`
- [Kubernetes the Easy Way](https://github.com/jimangel/kubernetes-the-easy-way) - Spin up a self-managed k8s cluster on DigitalOcean for cheap learning -- `various lang`
- [Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) - Build Kubernetes from the ground up as a learning exercise, uses Google Cloud -- `tutorial`
- [Kubernetes the Hard Way Azure](https://github.com/salaxander/kubernetes-the-hard-way) - Ported to Azure -- `tutorial`
- [Kubernetes the Hard Way Vagrant](https://github.com/kinvolk/kubernetes-the-hard-way-vagrant) - A port of Kelsey Hightower's "Kubernetes the Hard Way" tutorial to Vagrant -- `tutorial`
- [Kubernetes the Hard Way VirtualBox](https://github.com/sgargel/kubernetes-the-hard-way-virtualbox) - Bootstrap Kubernetes the hard way on VirtualBox. No scripts. -- `tutorial`
- [Latency: A Primer](https://igor.io/latency/) - Web-app centric, defines all the terms you need to know then puts the knowledge together -- `article`
- [LearnXinYMinutes](https://learnxinyminutes.com/) - Super fast tutorials for almost every programming language -- `collection`
- [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests/) - Explore Golang by writing tests and learn TDD while you're at it -- `tutorial`
- [Libby](https://meet.libbyapp.com/) - App for ebooks and audio books for USA public library members, from OverDrive -- `explore yours today` `Android` `iOS` `Windows 10`
- [Library Extension](https://www.libraryextension.com/) - Browser extension that shows you which Amazon books are available free at your local libraries, please donate -- `closed source`
- [Linux Journey](https://www.linuxjourney.com) - ELI5 Linux training -- `tutorial`
- [Linux Network Performance Parameters](https://github.com/leandromoreira/linux-network-performance-parameters) - Tutorial, data flows, explinations and more -- `tutorial`
- [Linux Performance](http://www.brendangregg.com/linuxperf.html) - Centralized page for all of Brendan Gregg's Linux performance material (slides videos pages etc) -- `the man`
- [Linux Skillup Challenge](https://github.com/livialima/linuxupskillchallenge) - 20 lessons for new Linux server admins -- `tutorial`
- [Linux Tracing Workshop](https://github.com/goldshtn/linux-tracing-workshop) - Hands on exercises with perf, bcc, and similar tools -- `various lang`
- [Little Book of Python Anti-Patterns](https://docs.quantifiedcode.com/python-anti-patterns/) - See title -- `book`
- [Memory Management Reference](http://www.memorymanagement.org/index.html) - All in one reference for memory management and garbage collection -- `collection`
- [Microservices Design Patterns](https://microservices.io/patterns/index.html) - A great foundation -- `collection`
- [MIT Enterprise Architecture Guide](https://barsand.files.wordpress.com/2014/09/mit-enterprise-architecture-guide.pdf) - An excellent real-world example that you can borrow from -- `real world example`
- [MIT OpenCourseWare](https://ocw.mit.edu/about/) - MIT's real course materials from 2400+ courses -- `collection`
- [MySQL Performance Tuning Checklist](http://www.jonathanlevin.co.uk/2018/02/my-mysql-linux-tuning-checklist.html) - No bullshit list in about 15 bullet points -- `collection`
- [Networking Cheat Sheets](http://packetlife.net/library/cheat-sheets/) - Protocols, devices, ports, physical connectors, and more, by PacketLife -- `collection`
- [Open Guides: AWS](https://github.com/open-guides/og-aws) - Excellent summary of almost all services -- `collection`
- [Open Source Society University (OSSU)](https://github.com/ossu/computer-science) - A complete education in computer science using free online materials -- `collection`
- [OpenLibrary.org](https://openlibrary.org/) - From the good folks at Archive.org -- `collection`
- [OpenShift Interactive Learning Portal](https://learn.openshift.com/) - Learn OpenShift in your web browser, by Red Hat -- `tutorial`
- [OpenShift v4 Demo](https://www.openshift.com/try) - Give it a try -- `tutorial`
- [OpenShift v4 Training](https://github.com/openshift/training) - Official, requires AWS -- `tutorial`
- [OpenShift v4 Workshop](https://github.com/RedHatWorkshops/openshiftv4-workshop) - By Red Hat -- `tutorial`
- [OpenVim](http://www.openvim.com/tutorial.html) - In-browser vim tutorial -- `tutorial` `in-browser`
- [Open Security Training](https://opensecuritytraining.info/) - In the spirit of OpenCourseWare and the Khan Academy -- `tutorial`
- [Open Source Intelligence Techniques](https://inteltechniques.com/book1.html) - By the folks who wrote Buscador Investigative Operating System -- `book`
- [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/%7Eremzi/OSTEP/) - Probably the best OS book out there, free -- `book`
- [Outages.org Mailing List](https://puck.nether.net/mailman/listinfo/outages) - Report and discuss major outages, network status updates, etc -- `mailing list`
- [OverAPI](http://overapi.com/) - Large collection of cheat sheets for almost anything -- `collection`
- [OverDrive](https://www.overdrive.com/) - Ebooks and audio books for USA public library members -- `explore yours today`
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) - Contribute on GitHub -- `collection`
- [OWASP DevSecOps Maturity Model](https://dsomm.timo-pagel.de/) - Provides opportunities to harden DevOps strategies and shows how these can be prioritized -- `tutorial`
- [OWASP Secure Coding Practices - Quick Reference Guide](https://www.owasp.org/index.php/OWASP_Secure_Coding_Practices_-_Quick_Reference_Guide) -- Great cheat sheet, language-agnostic -- `collection`
- [Play with Docker](https://labs.play-with-docker.com/) - Docker playground that allows users to run Docker commands in a matter of seconds (Alpine + Docker in Docker (DIN)) -- `learning`
- [Play with Docker Classroom](https://training.play-with-docker.com/) - Interactive tutorials using Play with Docker (see above) -- `learning`
- [Play with Kubernetes](https://labs.play-with-k8s.com/) - A simple, interactive and fun playground to learn Kubernetes in your browser, by Docker -- `in-browser`
- [PowerShell Koans](https://github.com/vexx32/PSKoans) - Learn the PowerShell language through Pester unit testing -- `PowerShell`
- [Practical Go Lessons](https://www.practical-go-lessons.com/) - Free 700+ page ebook - `book`
- [Preparing a Google Kubernetes Engine Environment for Production](https://cloud.google.com/solutions/prep-kubernetes-engine-for-prod) - The best GKE summary, covers everything -- `collection`
- [Production Readiness Checklist](https://www.gruntwork.io/devops-checklist/) - Excellent checklist for pre-go-live, AWS-centric but great general advice -- `collection`
- [python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns and idioms in Python -- `collection`
- [Python Cheat Sheet](https://www.pythoncheatsheet.org/) - Mostly based on the book written by Al Sweigart, Automate the Boring Stuff with Python -- `collection`
- [Python Reference](https://github.com/rasbt/python_reference) - A collection of useful scripts, tutorials, and other Python-related things -- `collection`
- [Python Patterns](https://python-patterns.guide) - Python patterns by Brandon Rhodes -- `collection`
- [Python Style Guide](https://google.github.io/styleguide/pyguide.html) - Google's Python style guide -- `article`
- [PyVideo](https://pyvideo.org/) - Thousands of videos from hundreds of Python events and conferences, categorized by subject -- `collection`
- [SaaS CTO Security Checklist](https://www.sqreen.com/checklists/saas-cto-security-checklist) - Categorizes and prioritizes actions by funding round -- `collection`
- [Safari Books Online](https://www.oreilly.com/) - Non-student ACM members get a full year of access for $99 [buy a membership here](https://www.acm.org/membership/membership-options) -- `collection`
- [Scrum Guide](https://www.scrumguides.org/) - Explains Scrum in a concise and straightforward way in about 10 pages, by the creators -- `article`
- [Secure Messaging Apps](https://www.securemessagingapps.com/) - True comparison of the technical features and merits of various apps, which are TRULY secure? -- `collection`
- [Security 101 for SaaS Startups](https://github.com/forter/security-101-for-saas-startups) - Excellent checklist and guide in easy to understand terms for non-infrastructure people -- `collection`
- [Security Engineering 3rd Edition](https://www.cl.cam.ac.uk/~rja14/book.html) - Free concise ebook, updated 2020 -- `book`
- [Security Overview of AWS Lambda](https://d1.awsstatic.com/whitepapers/Overview-AWS-Lambda-Security.pdf) - From AWS -- `article`
- [Site Reliability Engineering (SRE) by Google](https://sre.google/sre-book/table-of-contents/) - Full, free, online version of the O'Reilly book -- `the best`
- [Site Reliability Workbook](https://sre.google/workbook/table-of-contents/) - Free, by Google -- `book`
- [Software Engineering at Google](https://www.seagnotes.com) - Notes from the book, by me -- `notes`
- [Stack on a Budget](https://github.com/255kb/stack-on-a-budget) - Collection of services with great free tiers for developers on a budget, excellent for learning -- `collection`
- [Step-by-Step Enterprise Architecture Tutorial with TOGAF](https://www.visual-paradigm.com/guide/enterprise-architecture/step-by-step-enterprise-architecture-tutorial-with-togaf-adm/) - An excellent summary -- `tutorial`
- [System Architecture](https://github.com/orrsella/soft-eng-interview-prep/blob/master/topics/system-architecture.md) - Great refresher, not so great for first time learners -- `collection`
- [System Design Primer](https://github.com/donnemartin/system-design-primer) - Learn how to design large-scale systems -- `article`
- [SymbolHound](http://symbolhound.com) - Search engine that doesn't ignore special characters, great for programming questions -- `try it`
- [Teach Yourself Computer Science](https://teachyourselfcs.com/) - 9 subjects, they choose the best free source to learn each subject and explain why that source is the best - they did the research for you -- `collection`
- [Team Topologies](https://danlebrero.com/2021/01/20/team-topologies-summary/) - Notes from the book -- `notes`
- [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/) - SWE / dev-centric -- `tutorial`
- [Technical Writing by Google](https://developers.google.com/tech-writing/one) - Technical writing, training by Google -- `tutorial`
- [Terraform Security Tool Comparison](https://github.com/iacsecurity/tool-compare) - Which Terraform code scanners provide the most comprehensive coverage - click to find out -- `collection`
- [Test Your Sysadmin Skills](https://github.com/trimstray/test-your-sysadmin-skills) - A great little quiz, if you can answer these then you know Linux -- `collection`
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - The BEST interactive Linux tutorial, newbie focused -- `learn it`
- [The Early Security Engineer’s First 90 Days Checklist](https://www.sqreen.com/checklists/security-engineer-checklist) - Aims to help security engineers and CISOs in early stage companies to prioritize their efforts in the first months of their new job -- `list`
- [The Illustrated TLS Connection](https://tls.ulfheim.net/) - Every byte of a TLS connection explained and reproduced -- `article`
- [The Little Go Book](https://www.openmymind.net/The-Little-Go-Book/) - Free book, available in various formats - `book`
- [The Manager's Path](https://github.com/keyvanakbary/learning-notes/blob/master/books/the-managers-path.md) - Concise notes from the book -- `notes`
- [Tiny Python Notebook](https://github.com/mattharrison/Tiny-Python-3.8-Notebook) - One of the best syntax cheat sheets -- `article`
- [Twelve-Factor App](https://12factor.net/) - Language-independent rules for codebase, dependencies, build/release/run, dev and prod, logs, etc for a cloud/web-centric app -- `collection`
- [Two Factor Auth (2FA)](https://2fa.directory/) - Web sites that do and don't support 2FA, organized by category, submit PRs for changes -- `collection`
- [Understanding OAuth2 and OpenID Connect](https://www.polarsparc.com/xhtml/OAuth2-OIDC.html) - THE BEST article -- `article`
- [Unix Rosetta Stone](http://bhami.com/rosetta.html) - The one and only resource for a mixed Linux/Unix environment -- `translator`
- [USE Method](http://www.brendangregg.com/USEmethod/use-rosetta.html) - Brendan Gregg's rosetta stone for performance analysis and tuning -- `article`
- [Use the Index, Luke](https://use-the-index-luke.com/) - SQL indexing and tuning for developers -- `collection`
- [USENIX Video Archive](https://www.youtube.com/playlist?list=UU4-GrpQBx6WCGwmwozP744Q) - 4000+ videos from LISA and related events -- `collection`
- [Vim Adventures](https://vim-adventures.com/) - A game to learn vi / vim using your browser -- `in-browser` `tutorial`
- [Web Security Academy](https://portswigger.net/web-security) - Free online training for the creators of Burp Suite -- `tutorial`
- [Weird Behaviors in S3 Bucket Policies](https://github.com/elfakyn/knowledge/blob/master/src/cloud/aws/services/s3_bucket_policy_weird_behaviors.md) - Documented weirdness of S3 buckets -- `collection`
- [What Happens When... Kubernetes Edition](https://github.com/jamiehannaford/what-happens-when-k8s) - Walks through what happens behind the scenes when you do a kubectl run -- `tutorial`
- [wtfpython](https://github.com/satwikkansal/wtfpython) - A collection of surprising Python snippets and lesser-known features -- `collection`
