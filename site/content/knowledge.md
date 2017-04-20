+++
date = "2017-04-20T15:05:08+08:00"
title = "knowledge"

+++

### Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.
Stripe has wonderful documentation for implementation. The content is organized into understandable categories. The documentation for different code is organzied into tabs rather than listing. 

### Why do you think SSL/HTTPS is important?
In the past, SSL/HTTPS are only implemented in payment and log in where sensitive information is transfer. As we become more focus on data mining and interpretation, personal information can be compiled from the list of HTTP webpages. By studying a person's web trend, a data scientist can provide companies with our age, marital status and much more. We are in an era where all data is considered sensitive.


### Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users
I've ran into issue where the client failed to differentiate between name and hosting server. DNS records are used to mask the IP address assigned to each website. www.sample.com is only a friendly URL for an IP such as 125.342.12.21.

CName and A records are also terminology that is frightening for less-technical users. The two record work cohesively to redirect visitors to the correct section of the server. Aside from the webpages, the site may have a mail server, sub-sites that uses sample.com as the base web address. While A record identifies the IP address to the site, CName provides the system with a direction to the specific session of the site.
