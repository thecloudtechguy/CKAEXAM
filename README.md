# CKAEXAM
This post will discuss the two most important certificates of Kubernetes. CKA which stands for Certified Kubernetes Administrator and CKAD which stands for Certified Kubernetes Application Developer. We will start by discussing what is common in these two exams followed by how they both are different and how you can prepare to clear these exams. So, without any delay let’s get started.

Become a Certified Kubernetes Administrator (CKA)!

What is common in both the exams?

The cost of both the certifications is $300 USD.
Both the exams have around a dozen practical tasks that you need to complete over a specific amount of time. Some tasks are difficult; some are easy. The score you get after completing each task depends on how complex it is.
Don’t be sad if you don’t get the desired score in the exam. You get one free retake per exam.
Moreover, in both the exam you can open an additional tab with the documentation located on kubernetes.io and github.com/kubernetes for the reference during the exam.
Difference between both the exams:

The purpose of CKA(Certified Kubernetes Administrator) is to assure the applicant must have the skill, knowledge and competency to perform the responsibilities of Kubernetes administrators whereas CKAD is only about concepts such as deployments, DaemonSets, Pods and other API primitives. We can call CKAD as a lighter version of the CKA exam.

CKAD exams make sure that the applicant can design, build, configure and expose native cloud applications for Kubernetes whereas CKA exam requires knowledge of Kubernetes internals such as etcd, tls bootstrap, and kubelet.


 
We can’t call CKAD easy because it doesn’t have topics related to cluster administration. Duration of CKA exam is 2 hours whereas the CKAD exam allows 3 hours.

If your organization is having three or more CKA’s is a requirement to become a Kubernetes Certified Service Provider. CKAD doesn’t count towards this requirement. So, if your company is willing to become a Kubernetes Certified Service Provider — the CKA exam is your choice.

Let’s check how you can prepare for this exam?

The estimated time you can take to prepare for these exams is around three months considering both the exam has a significant overlap of the course content. I am sharing the few important resources which can be beneficial for your preparation.

The Cloud Native Computing Foundation designed a curriculum that outlines the knowledge and skills that both Certified Kubernetes Administrators(CKA) and Certified Kubernetes Developers(CKAD) are expected to demonstrate. You can find them on GitHub.
If you can complete any of these tasks without using Google you are good to go. Feel free to schedule your exam. As a side note, I’d advise going through the complete documentation instead of memorizing everything because you can still use official documentation during the test.
The Kubernatus Slack has two dedicated channels for the preparation of CKA and CKAD. If you are stuck somewhere feel free to post your questions on those channels you will more likely get some help or suggestions.
You can also check “Introduction to Kubernetes” course on edx.org and if you are completely new to Kubernetes this course from Linux Foundation will be a good start point. You will learn basic concepts, the architecture of the system, and get a better understanding of problems it solves.
Linux Academy also provides a paid course which covers theoretical aspects and one practical task at the end of each module. They are not that comprehensive but if you already have a subscription of a Linux academy then it’s a good replacement of edx.
If you are more of a book person then you can learn all the necessary theoretical concepts from “Kubernetes in Action” by Marko Luksa.
And at last, if you are more focussed on the CKA exam you need to learn about configuring Kubernetes without using any automated tools. Read this guide carefully, go through the tasks, and make sure you can reproduce everything without the book.

Some helpful tips to consider

Always use kubectl auto-completion. Not having to copy\paste pod and deployment names will save you a lot of time.
Get comfortable with vim and terminal. The exam environment is within a Linux terminal, so there is no GUI. It’s very important that you feel comfortable in this environment. Kubectl edit uses vim, and at the very least, basic commands shouldn’t be a problem for you (switch modes, save, copy/paste).
Use as much documentation as possible. Don’t try to memorize the YAML syntax of Kubernetes objects. For each concept — there is a page with code snippets. You can copy small amounts of code directly from the documentation – it’s a very powerful capability.
Hope, this helps you to prepare for both the exams.
