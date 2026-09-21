## Rosemary Akpovi

**Applied AI Engineer | Energy and Logistics | MSc AI and Data Science**

I spent over a decade running petroleum product distribution in Nigeria. My own trucks kept losing hours at the terminal, and those delays landed on my customers as late deliveries. Fuel queues. Plants running short. Production stopping. I went looking for a way to cut turnaround time, and that search led me to machine learning.

That order matters. I know what a delayed tanker costs, what dirty ERP data looks like, and why a model that ignores how the depot actually works gets ignored by the people who run it.

Now I build ML systems for the operational problems I used to solve by hand. Based in the UK, an MSc graduate of the University of Hull.

---

## Selected work

### [Classifying HuffPost News Categories](https://github.com/owoye124/huffpost-news-classification)

Four models compared on 209,527 articles across 14 editorially ambiguous categories. Fine-tuned DistilBERT reached 0.715 macro F1 against a 0.021 majority baseline. K-Means came in below the baseline, and the write-up keeps that result in, because a model failing on overlapping vocabulary says something real about the data.

Stack: PyTorch, Hugging Face Transformers, scikit-learn

### [Big Data and Data Mining](https://github.com/owoye124/big-data-data-mining)

Two studies. UK road accident data from the Department for Transport: association rule mining on severity, K-Means and DBSCAN hotspot clustering across West Yorkshire, Holt-Winters forecasting for three police forces. Then social network analysis of a 4,039-node Facebook graph, including edge betweenness and community detection.

Stack: pandas, scikit-learn, NetworkX, statsmodels

### [Census Data Analysis](https://github.com/owoye124/census-data-analysis)

A council has one plot of land and a limited budget. From a census of 7,773 residents, the answer is a train station: 79.2% of adults are likely commuters and the town sits between two cities joined by a single motorway. Most of the work was in the cleaning, inferring 1,813 missing marital statuses and 474 missing household relationships from household structure rather than dropping rows.

Stack: pandas, NumPy, Matplotlib, Seaborn

### [Vehicle Damage Classification](https://github.com/owoye124/vehicle-damage-classification-cnn)

CNN pipeline for automating insurance damage assessment from images, with per-class evaluation that surfaces where class imbalance hurts.

Stack: TensorFlow, Keras

### [Sales Forecasting for Supply Chain](https://github.com/owoye124/Sales-Forecasting-Using-Time-Series-Modeling)

Demand forecasting on supply chain data, framed around the planning decisions the forecast is meant to support.

Stack: pandas, statsmodels

---

## Research

**A Machine Learning Framework for Turnaround Time Prediction and Delay Reduction in Petroleum Terminals**

MSc dissertation, University of Hull. Supervised by Dr Julius Mboli.

60,012 cleaned truck-level delivery records from a petroleum distribution terminal's ERP system, covering 2015 to 2023. Random Forest predicted delay risk at 0.789 AUC, confirmed against Gradient Boosting by paired bootstrap and five-fold cross-validation. Feeding those predictions into a discrete-event simulation of the loading bay cut mean truck wait from 243.6 minutes under first-come-first-served to 78.0 minutes under ML-based priority scheduling. A 68% reduction, from a change to queue order alone.

Presented at the Green STEM Symposium 2026, University of Abuja, August 2026. Two publications in preparation.

---

## Background

**Education.** MSc Artificial Intelligence and Data Science, University of Hull.

**Before that.** B.Eng Petroleum Engineering. Ten years downstream oil and gas in Nigeria.

**Also.** Founder and MD, Havilah Oleum Global Services Ltd, petroleum product supply and distribution, Lagos.

---

## Working with

Python, SQL. PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers. pandas, NumPy, statsmodels, NetworkX. SimPy for discrete-event simulation. Git, Jupyter.

Interested in ML engineering roles in energy, logistics, supply chain and commodity trading. The operational context is the part most models get wrong, and it's the part I already know.

[LinkedIn](https://www.linkedin.com/in/akpovi-rosemary-owoye/)
