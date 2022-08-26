# SETechAssessment

Cloud Native infrastructure encompasses many, many things these days. We do not expect anyone to be an expert in everything--that is impossible! Rather, we look for key traits:

**GRIT** - We are a scale-up. It's fun, challenging, and demanding. GRIT is the number one trait we look for when finding someone who we believe will be successful, contributing to a world class organization.  Learn more about GRIT: https://angeladuckworth.com/grit-book/

**Creativity** - Successful individuals are those that think outside the box. They are willing to question the norms and speak up about their thoughts and ideas in an effort to make everyone better.

**Coachable** - We want people who want to be better, learn from their peers, and educate them selves. This space evolves fast, we must evolve with it.

**Mentors** - In order to be successful we have to mentor each other. Again, this space is vast, no one person can know it all. We expect everyone to contribute their knowledge back to their peers. Some people will be more knowledgeable in some areas, that's not only great, it's expected. You need to be willing to coach your peers to raise everybody up.

**Cultural Contribution** - We have a lot of fun, everyone supports each other and lifts each other up, and we work hard to help everyone be as successful as they can be. Many of us come from different backgrounds and we're stronger for that. We don't tolerate negative behaviour and we encourage collaboration and team ethic. This isn't just about technical knowledge, but also professional experiences.

# The Project

To get a handle on who you are, what your drive is, and how we can best support your success we have a few asks.  **Disclaimer**, we live in the age of Google, and that's OK! It's totally fine to look things up as you go. Get as far as you can, and be honest with yourself about your time. We're happy to give you more if you need it, just communicate with us when you're ready! At a high level, we'd like you to attempt the following:

1. Create an EKS cluster.
    - (Note: A node with 4cpu and 8 gigs of ram should be fine to run the Sysdig agent on)
    - If you're building in the cloud, and you're new to the cloud, learn about security and billing alerts!
    - Turn off or scale down your cluster when you're not using it, but don't destroy it!
3. Signup for a Sysdig Platform Trial (https://sysdig.com/company/free-trial-platform/)
4. Install the Sysdig Agent(s) using the *Getting Started* interface
5. Install the classic *voting app* into your K8s cluster (https://github.com/dockersamples/example-voting-app)
6. Get Creative and build some stuff in Sysdig.
    - Scan the images being loaded, what do the results mean?
    - Posture? What's up with those?
    - Enable Runtime Policies, generate some noise (how might you do that?)
    - Activity audit! Why's that valuable?
    - Build a PromQL query using the query builder in the explore section of Sysdig Monitor using metrics from the Voting App (bonus points if you use StatsD metrics in a PromQL query)
    - Build a dashboard with your query + static metrics from Sysdig that relate multipule things together
    - Add views to the dashboard that might be interesting to a user
7. Don't destroy your cluster! We'd like to look at it with you.
    - Hit some buttons and nav around things
    - Show off your namespaces
    - Pull some logs
8. Feedback? 
    - How can we get better? 
    - How did you experience with Sysdig differ from your experience of any other similar solutions?
    - What suggestions do you have on this process? 
    - What tasks could be different or better?
