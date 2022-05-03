## 10 Guidelines for the Human-Centered AI practice at Ventera


![alt_text](images/image1.png "framework image")


**Know thy Customers' Goals.** We start by designing a model with concrete goals for fairness and inclusion during the strategy and research phase: We work with you to understand your definition of fairness for production ML and conduct ethics reviews where applicable and engage with our data ethics experts to understand and account for various perspectives.

**Lean on what we do best.** We leverage Ventera’s best-in class human-centered design approach: We design models with appropriate disclosure built-in and incorporate feedback from the testers before deployment.

**Be data inspired.** For EDA, Data & ML Engineering we identify multiple metrics including baseline heuristics to assess training and monitoring: We use different metrics appropriate for the task to understand the tradeoffs between different errors and experiences. These metrics can be feedback from the consumers, false positive and false negative rates, etc.

**Garbage in garbage out.** We conduct continuous review of raw data if possible before, during and after model development: An AI model reflects the data being used to train the model. We aim to have balanced, debiased, and fair data.

**Debias where applicable.** For applicable use-cases, we check for fairness and bias: As a diverse team we get the unit tests inputs from a diverse background of testers to identify which group of people might be affected by the model.

**Understand a model's limitations.** A model trained to detect correlations does not necessarily help make causal interfaces. 

**Test all the things.** By conducting rigorous unit tests to determine faults in the model.

**Improve what we measure.** We continue monitoring and updating the model after deployment: Deployment isn’t the end of the journey, we ingest user feedback and update the model based on that regularly after deployment.

**Make it compliant.** We use representative datasets to train and test the model: We synthesize your definition of fairness to assess the fairness of your data. For example we look for prejudicial or discriminatory correlations between features and labels.

**Make the call.** For audits, monitoring and compliance performance analysis is baked into our approach by design: We take different metrics into account and communicate with our customer how improvement in one metric might hurt another metric’s performance e.g. bias vs impact on perf.
