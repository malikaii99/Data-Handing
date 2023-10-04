# Data-Handling
<h1>Description</h1>

In this activity, I will assess the outcomes of a data risk evaluation. My task is to ascertain whether efficient processes for managing data are being put into practice to safeguard the confidentiality of information.

Data represents one of the most invaluable assets in the contemporary world. From intellectual property to guest WiFi networks, it is imperative to safeguard this data through a comprehensive blend of technical, operational, and managerial safeguards. It is crucial to emphasize that adhering to the principle of least privilege is vital in ensuring the preservation of information privacy.


<h2>Scenario</h2>

Review the scenario below.

You work for an educational technology company that developed an application to help teachers automatically grade assignments. The application handles a wide range of data that it collects from academic institutions, instructors, parents, and students.

Your team was alerted to a data leak of internal business plans on social media. An investigation by the team discovered that an employee accidentally shared those confidential documents with a customer. An audit into the leak is underway to determine how similar incidents can be avoided.

A supervisor provided you with information regarding the leak. It appears that the principle of least privilege was not observed by employees at the company during a sales meeting. You have been asked to analyze the situation and find ways to prevent it from happening again.

First, you'll need to evaluate the details of the incident. Then, you'll review the controls in place to prevent data leaks. Next, you'll identify ways to improve information privacy at the company. Finally, you'll justify why you think your recommendations will make data handling at the company more secure.


<h3>Handling Report</h3>

Access to the internal folder, which contained sensitive promotional information, was not appropriately restricted solely to the sales team and the manager, as it should have been. Inadvertently, access privileges were extended to a business partner who, ideally, should not have been granted permission to disseminate this confidential promotional content on social media platforms. This oversight in access control measures raised concerns regarding the unauthorized sharing of critical business information, potentially impacting data security and the integrity of the promotional campaign.

NIST SP 800-53: AC-6 directly focuses on adhering to the Principle of Least Privilege, necessitating that organizations provide individuals and processes with only the essential permissions required for fulfilling their designated duties. The practice of granting excessive or redundant privileges should be actively discouraged and minimized.

To prevent a data leak, you can consider the following two control enhancements:
- AC-6 (1) - Automated Roles: Implement automated role-based access control (RBAC) systems to assign and manage user permissions based on their specific roles and responsibilities within the organization.
- AC-6 (2) - Just-in-Time Access: Implement just-in-time (JIT) access provisioning and deprovisioning procedures to grant users temporary access privileges only when needed.

The implementation of these essential enhancements is a strategic measure taken to fortify our organization's data security posture. By adopting these practices, users are meticulously granted access solely to the resources and data that are directly pertinent to their specific job functions. This discerning approach serves the dual purpose of significantly diminishing the potential for unauthorized access and mitigating the risk of data leaks that could compromise the integrity of our sensitive information.

Furthermore, these enhancements go beyond mere access control; they strategically minimize the window of opportunity for any unauthorized access attempts. This proactive stance ensures that individuals are furnished with access privileges exclusively during the precise periods when their active work responsibilities necessitate such access. In doing so, we not only bolster the safeguarding of our critical data but also demonstrate a commitment to adhering to the principles of least privilege, thereby enhancing our overall data governance and risk management efforts.
