# Working with Web ACLs<a name="classic-web-acl-working-with"></a>

**Note**  
This is **AWS WAF Classic** documentation\. If you created AWS WAF resources, like rules and web ACLs, in AWS WAF prior to November, 2019, and you have not migrated your web ACLs over yet, you need to use AWS WAF Classic to access those resources\. Otherwise, do not use this version\.  
**For the latest version of AWS WAF**, see [AWS WAF](waf-chapter.md)\. 

When you add rules to a web ACL, you specify whether you want AWS WAF Classic to allow or block requests based on the conditions in the rules\. If you add more than one rule to a web ACL, AWS WAF Classic evaluates each request against the rules in the order that you list them in the web ACL\. When a web request matches all the conditions in a rule, AWS WAF Classic immediately takes the corresponding action—allow or block—and doesn't evaluate the request against the remaining rules in the web ACL, if any\. 

If a web request doesn't match any of the rules in a web ACL, AWS WAF Classic takes the default action that you specified for the web ACL\. For more information, see [Deciding on the Default Action for a Web ACL](classic-web-acl-default-action.md)\.

If you want to test a rule before you start using it to allow or block requests, you can configure AWS WAF Classic to count the web requests that match the conditions in the rule\. For more information, see [Testing Web ACLs](classic-web-acl-testing.md)\.

**Topics**
+ [Deciding on the Default Action for a Web ACL](classic-web-acl-default-action.md)
+ [Creating a Web ACL](classic-web-acl-creating.md)
+ [Associating or Disassociating a Web ACL with an Amazon API Gateway API, a CloudFront Distribution or an Application Load Balancer](classic-web-acl-associating-cloudfront-distribution.md)
+ [Editing a Web ACL](classic-web-acl-editing.md)
+ [Deleting a Web ACL](classic-web-acl-deleting.md)
+ [Testing Web ACLs](classic-web-acl-testing.md)