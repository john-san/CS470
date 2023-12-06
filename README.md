# 8-1 Assignment: CS470 Final Reflection
# YouTube video link: https://youtu.be/yiQ1IYuBlBI 
##	Experiences and Strengths: Explain how this course will help you in reaching your professional goals.
###	What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
- I've acquired skills in Docker for container management. I have also learned about serverless technologies, enabling me to deploy applications to the cloud.

###	Describe your strengths as a software developer.
- I have several strengths as a software developer including programming skills, database skills, Linux, and cloud knowledge.

###	Identify the types of roles you are prepared to assume in a new job.
- I am flexible to work as a cloud developer or cloud admin. Ideally, I’d like to work as a cloud developer and work towards becoming a cloud engineer.

##	Planning for Growth: Synthesize the knowledge you have gathered about cloud services.
###	Identify various ways that microservices or serverless may be used to produce efficiencies of management and scale in your web application in the future. Consider the following:
####	How would you handle scale and error handling?
- To handle scale, I'd use AWS Lambda for serverless functions and Amazon ECS for containerized microservices, both of which support automatic scaling based on demand. For error handling, I'd use Amazon CloudWatch for monitoring and integrate retry mechanisms within AWS Step Functions. Additionally, Amazon S3's event-driven computing would provide fallback strategies to ensure continuous service during component failures.

####	How would you predict the cost?
- To predict the cost, I'd use the AWS Cost Explorer to analyze past spending trends and forecast future expenses. I would also use the AWS Pricing Calculator to estimate the costs of specific services based on anticipated usage. Last but not least, I’d set up budget alarms using AWS Budgets so I can keep costs within expected limits.

####	What is more cost predictable, containers or serverless?
- This is a bit of a trick question. While serverless architectures like AWS Lambda offer cost predictability for fluctuating workloads since you pay only for the compute time used, containers on platforms like Amazon ECS or Kubernetes might incur costs even during idle times. Yet, for steady, high-volume tasks, containers can offer clearer cost predictability. The best choice for cost-effectiveness depends on the particular workload and its patterns. 

### Explain several pros and cons that would be deciding factors in plans for expansion.
- Cloud expansion offers scalability, enabling businesses to handle increased traffic or workloads without substantial upfront investments. Additionally, cloud platforms provide flexibility, allowing businesses to quickly adopt new services or adjust existing configurations to meet changing requirements. Furthermore, the pay-as-you-go model inherent to cloud services often results in cost efficiency, ensuring that businesses only pay for the resources they use.

- However, there are challenges to consider. Cost overruns can be a significant issue. Without diligent management and monitoring, cloud expenses can quickly escalate. Data security is another concern; entrusting sensitive information to off-site servers is a risk, especially when considering potential data breaches and the complexities of regulatory compliance. Lastly, cloud services can sometimes lead to limited control over one's infrastructure compared to traditional on-premises setups. This means businesses might not have the same level of customization or oversight that they're used to.
### What roles do elasticity and pay-for-service play in decision making for planned future growth?
- Elasticity and pay-for-service play important roles in decision-making for future growth. Elasticity ensures that as demand fluctuates, infrastructure can scale as necessary, enabling businesses to handle increased workloads without incurring unnecessary overhead during slow periods. Meanwhile, the pay-for-service model offers financial predictability and efficiency, allowing companies to only pay for the resources they use. Together, these factors promote flexibility and cost-effectiveness, making them essential considerations for strategic growth planning.