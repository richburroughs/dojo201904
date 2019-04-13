theme: Zurich, 3


# Learning Through Failure

Rich Burroughs
Community Manager
Gremlin, Inc.
@richburroughs

---

#Improving the lives of software engineers and operators

---

![100%](images/dream_of_the_90s.png)

^I started off in the industry in the mid 90s, working for an Internet Provider in Portland

---

![100%](images/dog_day.jpg)

^Was in oncall rotations for about 20 years of my career
^Thousand yard stare

---

#Complexity is constantly increasing

^Virtualization
^Microservices
^Cloud
^Containers
^Kubernetes
^Service meshes

---

![fit](images/webmd.png)


^My next job was at a site you might have spent some panicked moments on
^Very high traffic site on the Internet
^Taking out Super Bowl Ads

---

##Image of WebMD architecture: 3 web servers, load balancer, DB

^This is what the architecture looked like
^Before horizontal scaling
^Used to deploy the site
^Take one server out of farm, run scripts, put it back in service

---

![100%](images/netflix-microservices-diagram-bruce-wong.jpg)

---

![fit](images/how_complex_systems_fail.png)

^How Complex Systems Fail by Richard Cook
^18 points, here are a few

---

#"Catastrophe is always just around the corner"
^Failure is inevitable

---

#"Change introduces new forms of failure"

^New technologies may have bigger failure modes

---

#"All practitioner actions are gambles"

^Uncertainty

---

![150%](images/soylent_green.jpg)

^People specialize and have different areas of expertise

---

#Mental models

^Allspaw tweet

---

#S3 outage

---

#What are some ways we can learn about systems?

---

#Docs

^Internal docs like Wikis
^External docs for open source and proprietary software
^Wikis get stale
^What you drew on the white board may not really be how the system works

---

![fit](images/logan_mcdonald.png)

^Optimizing through learning
^Studying systems with tools like flash cards

---

#RPG

^D&D for SRE

---

#Chaos Engineering

---

##"The science of performing intentional experimentation on a system by injecting precise and measured amounts of harm to observe how the system responds for the purpose of improving the system’s resilience."

^Injecting failure

---

![fit](images/chaos_monkey.png)

^Created in 2010 for move into AWS
^Shut down random hosts
^Amazon and Google had both done failure testing

---

![fit](images/ce_history_principles_practice.png)

---

#Who is doing Chaos Engineering?

---

#Prerequisites
- Observability
- Blameless Culture

^logging, monitoring, alerting and metrics
^How we see what is happening with the system
^People need to feel like they won't get fired for making a mistake

---

#Scientific Method
- Ask a question
- Research
- Form a hypothesis
- Experiment to test the hypothesis
- Analyze data and draw a conclusion
- Share the results

^Sharing externally, or at least internally
^At least everyone working on the system and stakeholders

---

#Blast Radius

^The service
^Number of host
^Environment (production or staging)

---

#The goal is to experiment in Production

^No other environment will be exactly like it

---

#Types of attacks
- Shutdown
- CPU
- Memory
- Network Latency
- Packet Loss

---

#Don't experiment on things you know are broken

---

![fit](images/chaos_experiment_card.png)

^Abort conditions - big red button

---

#Example experiment

---

#Game Days

^Onboarding

---

#Other things you can do
- Validate post-incident remediation
- Validate monitoring/observability

---

#Continuous Chaos

---

