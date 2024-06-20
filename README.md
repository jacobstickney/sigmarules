[Sigma](https://github.com/SigmaHQ/sigma) is a generic and open signature format that allows you to describe relevant log events in a straightforward manner. The rule format is very flexible, easy to write and applicable to any type of log file. The main purpose of the Sigma project is to provide a structured form in which researchers or analysts can describe their once developed detection methods and make them shareable with others.

SIGMA rules are valuable in detection engineering as they provide a generic, open standard for defining security detection rules in a structured and scalable manner. They allow for the creation of rules that can be shared across different systems, reducing the effort required to create custom rules for each system. This promotes consistency in detection and improves the overall efficiency of the security operations center (SOC). Furthermore, by using SIGMA, organizations can leverage the collective wisdom of the security community, benefiting from rules created by others who have encountered similar threats.

Leveraging existing SIGMA rules prior to creating your own may often offer the highest return on investment for a couple key reasons:

- These rules are already well-documented, facilitating easy reference and knowledge sharing. This means less time spent on documentation and more time on actual threat detection.
- Existing SIGMA rules make use of available data sources which can save considerable time and effort in data collection.

However, it's important to note that there may be instances when creating custom SIGMA rules is necessary. This could be due to specific needs or unique aspects of a client's environment that are not addressed by the existing rules. In such cases, although the initial investment might be higher due to the need for custom rule creation, the return could be substantial if it results in more effective threat detection and response.
