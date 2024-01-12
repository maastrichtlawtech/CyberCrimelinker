# CyberCrimelinker: Connecting Illegal Vendors on Darknet markets: Responsible Authorship Attribution to Link and Connect online Cybercrimes

In this tutorial, we address the significant challenge law enforcement agencies face in uncovering illegal markets and their connections due to the anonymity on these platforms. Perpetrators often remain undetected by adopting multiple aliases or frequently shifting between markets. To tackle this issue, we demonstrate the responsible application of the Authorship Attribution (AA) approaches **([1,2])** within Natural Language Processing (NLP).

AA approaches in NLP involve determining a text's likely author or source based on linguistic features and patterns. These approaches are particularly useful in identifying and linking written content to specific individuals, which can be valuable in various applications, including forensic analysis, plagiarism detection, and tracking activities on online platforms. This workshop aims to develop methods that enable law enforcement to connect the dots and establish relationships between illegal Darknet markets and their vendors. We employ advanced NLP techniques to unveil the distinctive linguistic fingerprints that individual authors leave in their writings. These fingerprints may include syntactic structures, vocabulary choices, writing style, and other linguistic nuances that can be extracted and analyzed. Through a responsible application of AA approaches, investigators can trace and link these linguistic patterns to specific vendors, thus uncovering their identities and affiliations within the illegal markets.

The tutorial will explore the difficulties of implementing these AA techniques, providing practical insights and methodologies for effectively identifying and connecting unique vendor accounts across various text advertisements of the Agora Darknet Market. By understanding and leveraging the distinctive writing patterns of individuals, law enforcement agencies can enhance their capabilities in tracking and combating illicit activities on the Darknet.

# Workshop Content(*)

1. **Introduction**:
   1. Who are we, and what do we do? 
   2. Current Trends in NLP; the rise of Transformer models
   3. Darknet Markets
   4. Authorship Attribution Approaches in NLP
      1. Authorship Identification
      2. Authorship Verification

2. **Responsible Authorship Attribution**:
      1. Privacy & Data Protection
      2. Discrimination & Unintended Biases
      3. Transparency & Fairness
      4. Societal Impact

3. **Hands-on session: Getting started**
   1. Setting up the [Google Colab](https://colab.google/) notebook
   2. Creating the environment and Installing the dependencies
   3. Data Analysis of Agora Marketplace
   4. Responsible Data-preprocessing 
   5. Sanity Check: Performing stylometric analysis

4. **Hands-on session: Authorship Identification; A closed-set multi-class Classification Task**
   1. Statistical Models
   2. Traditional  NNs
   3. Transformers-based models
   4. Explainability frameworks

5.  **Hands-on session: Authorship Verification; An open-set Retrieval Task**
      1. Extracting text representations
      2. FAISS

6. **Conclusion**
      1. Where do we stand?
      2. Limitations
      3. Future Work

**(*) Disclaimer:** Due to time constraints, our exploration of the Python code will be limited, with most functionalities encapsulated within functions and classes. The primary goal of this workshop is not to delve into the intricacies of text classification and retrieval in NLP. Instead, our focus is on demonstrating how AA approaches can be applied responsibly to identify and connect criminal entities within illegal online markets. We aim to showcase the application of these techniques rather than providing an in-depth tutorial. Any questions are welcome during the break time or after the workshop.

# Dataset

[Agora Darknet Market](https://www.kaggle.com/datasets/philipjames11/dark-net-marketplace-drug-data-agora-20142015): The Agora Darknet market, operational on the Tor network, was launched in 2013 and gained prominence as a leading platform after the closure of Evolution in March 2015. Operating until August 2015, Agora distinguished itself by surviving Operation Onymous, which targeted various darknet websites in November 2014. Administrators announced the market's closure in response to potential threats and suspicions of server de-anonymization. An art exhibition in Switzerland, titled "The Darknet: From Memes to Onionland," featured an exploration of darknet culture, including purchases made by the automated shopping bot, Random Darknet Shopper, on Agora. Despite its resilience, vulnerabilities in the Tor Hidden Services protocol were revealed, prompting Agora's administrators to suspend operations temporarily. The closure led to a shift in activity to AlphaBay until its shutdown by law enforcement in July 2017. To read more about the Agora darknet market, please take a look at [Wikipidia](https://en.wikipedia.org/wiki/Agora_(online_marketplace)).

# Good to know:

1. [Complete Google Colab Tutorial](https://www.youtube.com/watch?v=agj3AxNPDWU&list=PLA83b1JHN4ly56Y7o6vDAT8Szxc3_EdRH)
2. [Scikit-Learn Python Tutorial | Machine Learning with Scikit-learn](https://www.youtube.com/watch?v=2WztaC6kyLs&list=PLS1QulWo1RIa7ha9SewcZlsTQVwL7n7oq)
3. [PyTorch Lightning Tutorials](https://www.youtube.com/watch?v=XbIN9LaQycQ&list=PLhhyoLH6IjfyL740PTuXef4TstxAK6nGP)

# Presenters

1. [Vageesh Saxena](https://www.maastrichtuniversity.nl/vk-saxena)
2. [Ass. prof. Aurelia Tamo](https://www.maastrichtuniversity.nl/tamo-larrieux)
3. [Prof. Gijs Van Dijck](https://www.maastrichtuniversity.nl/nl/g-van-dijck)
4. [Ass. prof. Gerasimos Spanakis](https://dke.maastrichtuniversity.nl/jerry.spanakis/)

# Publications

1. [VendorLink: An NLP approach for Identifying & Linking Vendor Migrants & Potential Aliases on Darknet Markets - ACL, 2023](https://aclanthology.org/2023.acl-long.481/)
2. [IDTraffickers: An Authorship Attribution Dataset to link and connect Potential Human-Trafficking Operations on Text Escort Advertisements - EMNLP, 2023](https://aclanthology.org/2023.emnlp-main.524/)

