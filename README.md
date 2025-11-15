# Project Portfolio: Descriptions & Links

<!-- Descriptions and external links organized by language and date -->

This repository contains descriptions of my projects, organized by programming language. Within each section, the projects are listed in chronological order, starting with the most recent.
<h2 id="Table-of-Contents">Table of Contents</h2>

<ul>
    <li><a href="#MATLAB">MATLAB</a></li>
    <ul>
        <li>Modeling the continuous-perceptual-report task - German Primate Center</li>
        <li>Engineering Humans' choices - NeuroBridges Summer Program</li>
        <li>Intertrial correlations in sequential decision-making tasks - University of Houston</li>
        <li>Human Guided Machine Vision for Road Detection - Institute for Mathematics and its Applications</li>
        <li>Sensory feedback in a bump attractor model of path integration - University of Houston</li>
    </ul>
    <li><a href="#Python">Python</a></li>
    <ul>
        <li>Deep Learning for Anti-Money Laundering: Detecting Suspicious Transactions - The Erdős Institute</li>
        <li>Addressing Membership Challenges: Insights and Strategies for Amour Beauty Box - The Erdős Institute</li>
        <li>Nook Café's Transformation: Bridging Coffee Culture and Nightlife - The Erdős Institute</li>
        <li>MarketMind: Unveiling Stock Trends with Machine Learning - The Erdős Institute</li>
        <li>Imputing missing data from stock time series - The Erdős Institute</li>
        <li>Monte Carlo Simulations of Crystallization in Pentomino Fluids - University of Texas at Dallas</li>
    </ul>
    <li><a href="#SQL">SQL</a> </li>
    <ul>
        <li>Real-Time Agent Assignment System - Independent Project</li>
    </ul>
    <li><a href="#Others">Others</a> </li>
    <ul>
        <li>From Browsing to Buying: A Behavioral Study for Merci's - The Erdős Institute</li>
        <li>The Bathtub of the Future: Backed by Science - Institute for Mathematics and its Applications</li>
    </ul>
</ul>


---

<h3 id="MATLAB">MATLAB</h3>

<h4>Modeling the continuous-perceptual-report task - German Primate Center (DPZ) - 2020-2022</h4>

<i>Key words: two-dimensional leaky integrator, ARMA models, Granger causality, transfer entropy, numerical simulation, MATLAB</i>

<li>DPZ was among the first groups globally to design experiments studying continuous decision-making, requiring new modeling approaches. For example, drivers continuously monitor obstacles and other vehicles to steer accordingly. I developed a two-dimensional leaky integrator as an ideal subject for solo continuous tasks. In social settings, I implemented an Auto-regressive Moving Average model and computed Granger Causality to analyze information flow between two subjects. Simulations accurately predicted human behavior, achieving MSE values of 0.19 - 0.46 for easy and intermediate tasks. The model also captured reaction time delays (329–407 msec) and individual information loss rates (16–50.71 units/msec) across 13 subjects.

<h4>Engineering Humans' choices - NeuroBridges Summer Program	- 2019</h4>

<i>Key words: experimental design, reward schedules, quantitative modeling, MATLAB</i>

<li>I was interested in quantitative model to shape people's choices. I designed a binary task with 25% reward was given in such a way that oblivious human subjects picked our preferred choices. I acquired data from other attendees and did the analysis using Python. My reward schedule was able to engineer subjects' choices. We found that the first reward choice may shape subject's beliefs on "correct" choice.
</li>

<h4>Intertrial correlations in sequential decision-making tasks - University of Houston	- 2017-2020</h4>

<i>Key words: stochastic modeling, Bayesian inference, decision-making processes, probabilistic feedback, numerical simulation, MATLAB</i>

<li>I was interested in strategies that humans and animals used to adjust their behaviors in a changing world with uncertain feedback. I considered a stochastic model of an ideal observer presented with a sequence of decision-making trials, in which the correct choice switches between trials. On subsequent trials, I quantified the observer's bias based on the previous decision, and on how likely the true choice is switches between trials. When no feedback was present, the best strategy was to spend more time on the first trial, so the observer profited from the bias collected on later trials. When feedback was provided as probabilistic signals, the observer should spend time to consider options and increased certainty as rewards were based on correct choices. When feedback was in form of probabilistic reward, the best strategy was to make immediate decisions to save time for more trials as accuracy was less important. <a href="https://github.com/kpnguyen21/sequential">[GIT]</a>, <a href="https://doi.org/10.1016/j.jmp.2018.11.001">[PAPER]</a>
</li>

<h4>Human Guided Machine Vision for Road Detection - Institute for Mathematics and its Applications	- 2016</h4>

<i>Key words: Image Processing Toolbox, interface design, satellite imagery, road detection, MATLAB</i>

<li>The goal for this project was to create an interface using MATLAB Image Processing Toolbox that allowed users to detect roads from satellite images. From a variety of satellite images from Google Earth, I first converted the images into pixel intensity value, then detected edges and filtered the images, and finally segmented the images based on connectivity. The algorithm worked well for simple highway connections and isolated roads. For more difficult images, such as roads with heavy traffic, using a local filtering and tracking system could improve the results. <a href="https://drive.google.com/file/d/1BujspAgZGKxV-pdFAXQV9h8zl0Cibx9s/view?usp=sharing">[SLIDES]</a>
</li>

<h4>Sensory feedback in a bump attractor model of path integration - University of Houston - 2013-2015</h4>

<i>Key words: PDE modeling, spatial navigation, neural networks, numerical simulation, MATLAB</i>

<li>I wanted to explore the influence connection architecture on the robustness of persistent activity in neural networks responsible for spatial navigation. The hypothesis was that input from the visual system served as feedback control to that sensory stimuli can improve the robustness of positional memory. I analyzed PDE model of the neural activity that represents an animal's position in physical space and implemented numerical simulations that demonstrated how noise impacts the network's memory of the spatial position. My analysis and simulations showed that our hypothesis was correct. <a href="http://link.springer.com/article/10.1007/s10827-015-0588-y">[PAPER]</a>
</li>

---

<h3 id="Python">Python</h3>

<h4>Deep Learning for Anti-Money Laundering: Detecting Suspicious Transactions - The Erdős Institute - 2025</h4>

<i>Key words: Deep Learning, Anti-Money Laundering (AML), XGBoost, Tabular Transformer, Temporal Graph Neural Network, Python</i>

<li>Money laundering accounts for 2-5% of global GDP ($800B–$2T), with detection especially difficult during the layering stage. To address this, I analyzed 9.5M transactions with 11 original features and engineered 24 temporal and graph-based features using Polars for speed and memory efficiency. Baseline XGBoost achieved high precision (0.887) but low recall (0.413), missing many suspicious cases. A Tabular Transformer improved recall (0.5993) with moderate precision (0.6492), while a Temporal Graph Neural Network outperformed both (precision: 0.812, recall: 0.814), highlighting the value of graph-based modeling for AML. These results lay a strong foundation for scalable, real-world AML systems. Future work will explore hybrid architectures, temporal graph modeling, and real-time inference.
</li>

<h4>Addressing Membership Challenges: Insights and Strategies for Amour Beauty Box - The Erdős Institute - 2025</h4>

<i>Key words: UX research, A/B testing, customer surveys, Mann-Whitney U test, Python</i>

<li>I investigated declining membership sign-ups for Amour Beauty Box despite minimal cancellations. Through a survey of 312 website visitors, I identified visibility issues with the "Join Now" button. To assess the impact of repositioning the button, I designed and conducted a 20-day A/B experiment, collecting and analyzing 10,000 data points. Using the Mann-Whitney U Test on non-normal data, I found p-values of 0.598 and 0.602 for conversion rate and revenue, respectively. The results confirmed that the change had no significant effect on sign-ups or revenue. <a href="https://www.erdosinstitute.org/certificates/spring-2025/ux-research-boot-camp/khanh-nguyen/968ce7b0-acfc-4bed-9bc4-b0e0701677f4">[LINK]</a>, <a href="https://github.com/kpnguyen21/erdos-AB-testing/">[GIT]</a>, <a href="https://github.com/kpnguyen21/erdos-AB-testing/blob/main/Proposal.pdf">[PROPOSAL]</a>, <a href="https://github.com/kpnguyen21/erdos-AB-testing/blob/main/Executive%20Summary.pdf">[EXECUTIVE SUMMARY]</a>
</li>

<h4>Nook Café's Transformation: Bridging Coffee Culture and Nightlife - The Erdős Institute - 2025</h4>

<i>Key words: UX research, market analysis, population forecasting, Python</i>

<li>In this project, I analyzed market demand, market size, and competition for Nook Café, a coffee shop on the University of Houston campus, to assess whether extending evening hours to include alcoholic beverages would boost revenue. I examined student and faculty population trends from 2014 to 2024, considering factors such as race and sex to forecast potential customers for Nook Café over the next three years (2025–2027). These insights helped Nook Café determine the optimal proportion of alcoholic beverages—spirits, beer, and wine—to stock. While extending hours carried certain risks, my findings suggested that it would likely generate greater revenue over the next two years.   
<a href="https://www.erdosinstitute.org/certificates/spring-2025/ux-research-boot-camp/khanh-nguyen/968ce7b0-acfc-4bed-9bc4-b0e0701677f4">[LINK]</a>, <a href="https://github.com/kpnguyen21/erdos-coffee-bar">[GIT]</a>, <a href="https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/proposal.pdf">[PROPOSAL]</a>, <a href="https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/Executive_Summary.pdf">[EXECUTIVE SUMMARY]</a>
</li>

<h4>MarketMind: Unveiling Stock Trends with Machine Learning - The Erdős Institute - 2024</h4>

<i>Key words: machine learning, time series analysis, regression, classification, backtesting, VAR, simulation, trading decision forecasting, Granger causality, Python</i>

<li>I classified trading decisions for Ford’s stock by analyzing 26 directly and indirectly connected companies. I identified six highly correlated firms that Granger-caused Ford’s stock movements. I collected five years of data from Yahoo Finance, training models on three years (up to October 2024) and reserving two years for backtesting. I validated models through trades on the Investopedia Simulation platform. While regression (82.9% accuracy), SVM (85.7% accuracy), and XGBoost (86.6% accuracy) performed well on backtesting, regression and SVM ranked highest on the Investopedia platform. 
 <a href="https://www.erdosinstitute.org/certificates/fall-2024/data-science-boot-camp/khanh-nguyen/ca368ce5-6cb3-41d0-b74a-1f3a050b9c44">[LINK]</a>, <a href="https://github.com/kpnguyen21/equity-vs-commodity">[GIT]</a>, <a href="https://www.erdosinstitute.org/_files/ugd/eda2b9_5fd77770327b46a48407f0648b8b59b6.pdf">[SLIDES]</a>
</li>

<h4>Imputing missing data from stock time series - The Erdős Institute - 2024</h4>

<i>Key words: machine learning, time series analysis, data imputation, linear interpolation, VAR, Granger causality, Python</i>

<li>I addressed missing data in Apple’s 2023 stock time series from Yahoo Finance. Tested imputation methods, including linear interpolation as baseline model, KNN, linear regression, and VAR. I computed relative MSE against baseline model, finding forward-backward ARIMA performed best (relative MSE between 1.09 and 1.35), while VAR was the worst (relative MSE between 1.83 and 4.7). I concluded that linear interpolation remained the most effective method. <a href="https://www.erdosinstitute.org/certificates/may-summer-2024/data-science-boot-camp/khanh-nguyen">[LINK]</a>, <a href="https://github.com/bootstrapM/erdos-may-2024-imputing-data/">[GIT]</a>, <a href="https://www.erdosinstitute.org/_files/ugd/eda2b9_479d0ca1ce454cf3950447646f2e832a.pdf">[SLIDES]</a>
</li>

<h4>Monte Carlo Simulations of Crystallization in Pentomino Fluids - University of Texas at Dallas - 2013</h4>

<i>Key words: Monte Carlo simulation, computational modeling, nanotechnology, Python</i>

<li>My goal was to understand the self-assembly of molecules adsorbed on surface, which was an important process in nanotechnology. Earlier work suggested that the fluid we were studying underwent a phase transition to a crystalline state at a chemical potential near 4.0. My project was to investigate the appearance and growth of crystals during this phase transition using a simple lattice model and Monte Carlo simulations. I found that the average and maximum sizes of the crystals increased, while the number of crystals decreased over time. <a href="https://drive.google.com/file/d/1b2hSQn9VZh9Os-JxeiTPyDuocDGokBBk/view">[POSTER]</a>
</li>

---

<h3 id="SQL">SQL</h3>

<h4>Real-Time Agent Assignment System - Independent Project - 2025</h4>

<i>Key words: dynamic algorithms, matching algorithms, SQL</i>

I proposed a dynamic SQL-based algorithm that matches incoming customers to the most suitable available travel agent, updated each agent's workload, and adjusted their availability ranking accordingly. Agent suitability was determined using a multi-criteria ranking system that prioritized agents with the fewest active assignments, followed by those with the most years of service and the highest average customer satisfaction scores. To validate the algorithm, I tested two operational scenarios: (1) when an agent's workload increased by assisting new customers, and (2) when an agent's workload decreased as existing customer cancelled their booking. In both cases, the algorithm consistently identified the best-matched agent, updated their load assignment, and refreshed the agent ranking table to reflect real-time availability. <a href="https://github.com/kpnguyen21/space-challenge">[GIT]</a>

---

<h3 id="Others">Others</h3>

<h4>From Browsing to Buying: A Behavioral Study for Merci's - The Erdős Institute - 2025</h4>

<i>Key words: UX research, cluster random sampling, simple random sampling, user personas, wireframing</i>

<li>I assisted Merci's, a high-end online apparel store, tackle cart abandonment issues by conducting two rounds of user interviews in New York City, where most of its customers are based. The first round involved five groups of ten users selected through cluster random sampling. Sixteen users were then chosen through simple random sampling for the second round, where they answered six questions to identify checkout pain points. I distilled findings into three user personas, capturing distinct characteristics, behavioral patterns, and challenges. I designed a wireframe using these personas to improve the app’s navigation and address customer frustrations. <a href="https://www.erdosinstitute.org/certificates/spring-2025/ux-research-boot-camp/khanh-nguyen/968ce7b0-acfc-4bed-9bc4-b0e0701677f4">[LINK]</a>, <a href="https://my.visme.co/view/dm4dgezk-merci-s-customer-persona">[PERSONA]</a>, <a href="https://my.visme.co/view/31xq411r-merci-revision#s1">[WIREFRAME]</a>
</li>

<h4>The Bathtub of the Future: Backed by Science - Institute for Mathematics and its Applications - 2016</h4>         

<i>Key words: bathtub design, heat equation modeling, COMSOL Multiphysics</i>

<li>I was assigned to design a bathtub that conserved water and energy. I considered three features of a bathtub: dimensions/shapes, thickness of wall, and location of jets. I applied standard fluid flow and heat transfer equations using COMSOL Multiphysics. I found that a deeper bathtub with a constant flow rate while the drain and faucet were far apart would satisfy the conservative conditions.</li>
