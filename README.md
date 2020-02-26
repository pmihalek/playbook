# playbook

Play |	Description |	Results |	Best Practices
--- | --- | --- | ---
Microservice Architecture | Breaks a monolithic application into self-contained microservices |	Results in easier to develop and maintain applications, autonomous and cross-functional teams, flexibility in using technologies and scalability| Loose Coupling, Stateless Application, Containerization
Cloud-Native Services | Design architecture with Cloud-Native services in mind | Results in reduced operations Cost, Elasticity, Scalability and Fault-Tolerant Applications| Infrastructure-as-Code (IaC), Immutable Infrastructure, Dev-Prod Parity
API-First Development | Treats APIs as first-class citizens when a product or service is designed and provides a contract |	Results in Parallel development teams, reusability of the developed services, good developer experience, and reduced risk of failure. |	OpenAPI Specification, Hypermedia as the Engine of Application State (HATEOAS), API Contracts
Data-Driven Solutions | Design your solution to be optimal to the problems that the data will have at scale	| Results in optimized response time, scalability, maximum value from the data | Event Storming, Domain Driven Design (DDD), Decoupled Persistence, Intelligent Search
Shift-Left Security | Security should not be an afterthought and should be built into the development process. | Results in rapid ATO, easier to resolve security issues, and reduced risk of failures | Security Scans, Encryption In-Transition and At-Rest, Penetration Testing
Automation Everywhere | Build a development pipeline that provides automation for developers and allows for rapid development	| Results in fast delivery, reduced risk of failure, measurable progress, version control	| Automated CI/CD pipeline, Automated Testing, Automated Monitoring/Alerts, Autoscaling
Built-in Quality | Quality should be part of the process and not a separate activity |	Results in lower costs, fewer bugs, increasing returns, and stakeholders confidence	| Test Driven Development (TDD), Behavior Driven Development (BDD), Unit/Integration/End-to-End/Load, Quality Gates | Human-Centered Design	Provide an approach that makes for a better user experience, including making information accessible to all constituents | Results in customer-driven solutions, maximum accessibility, good user experience	| Best practices include 508 compliance, United States web design system, code scaffolding, complete documentation

# reference architecture

![alt text](https://github.com/USPTO/playbook/blob/master/refarch.png "Reference Architecture")

# technology toolbox

Hierarchy |	Technology | Tools
--- | --- | --- 
Agile |	Code Repository |	GitHub, GitLabs
Agile |	Collaboration |	Sharepoint
Agile |	Communicatio |	Microsoft Teams
Agile |	Project Management (APM) |	Rally
Data |	Caching |	Redis, MemcacheD, AWS ElastiCache (For Redis)
Data |  CDN | AWS CloudFront
Data |	Cluster |	Hadoop, Spark, Ambari
Data |	Data Science |	Jupyter Notebook, Python, R Lang, Julia, Apache Zepplin
Data |	Content Management |	Alfresco
Data |	DB - Document |	MongoDB
Data |	DB - Graph |	Neo4J
Data |	DB - Relational |	Percona MySQL, Oracle, AWS Aurora (MySQL/Postgres), AWS RDS (Oracle)
Data |	ETL |	Apache NiFi, Alteryx, AWS Glue
Data |	Queue & Streaming | Kafka, Jboss AMQ, AWS Kinesis Data Streams (Kafka), AWS Kinesis Firehose (Kafka), AWS SNS & SQS
Data |	Search |	Elasticsearch, Solr
Data |	Schema Version Control |	Liquibase
Data |	Visualization |	Tableau, Kibana, Azure PowerBI, AWS QuickSight
Development |	API |	Swagger, OpenAPI
Development |	Authentication/Authorization | Okta, Oracle IAM, AWS IAM, Azure AD
Development |	Frameworks |	Spring Framework
Development |	Backend |	Spring Boot, Node.js
Development |	Build |	Maven, NPM, Webpack, Angular CLI, Bower, Gulp, AWS CodeBuild
Development |	Frontend |	Angular, Vue
Development |	IDE |	Eclipse, Sublime, IntelliJ, R Studio, VS Code, Ananconda
Development |	Languages |	Java, JavaScript, TypeScript
Development |	ORM | 	Hibernate, Sequelize
Development |	Style |	USWDS, Bootstrap, HTML5, CSS3, SASS, USPTO Design Library
Infrastructure |	API Gateway |	AWS API Gateway, Zuul, Mulesoft, Kong
Infrastructure |	Service Mesh |	Istio, Eureka, Mulesoft, Kong
Infrastructure |	Cloud |	AWS, Azure, GCP
Infrastructure |	Container |	Docker
Infrastructure |	IaC |	Terraform, AWS Cloud Development Kit (CDK)
Infrastructure |	Orchestration |	Kubernetes, AWS ECS
Infrastructure |	Pipeline |	Jenkins, AWS CodeDeploy
Infrastructure |	Platform |	OpenShift
Infrastructure |	Repository Manager |	Nexus
Operations |	Dashboards |	Grafana, Kibana
Operations |	Metrics |	Prometheus, Logstash
Operations |	Monitoring |	Splunk
Operations |	APM |	AppDynamics
Testing |	Accessibility/508 |	Pa11y, ANDI, Wave Plug-In for Chrome by Webaim
Testing |	Integration |	Selenium, Protractor, Cucumber
Testing |	Penetration |	OWASP ZAP, Fortify, WebInspect
Testing |	Performance |	JMeter, Gatling
Testing |	Static Code Analysis |	SonarQube
Testing |	Unit |	JUnit, Jest, Jasmine
