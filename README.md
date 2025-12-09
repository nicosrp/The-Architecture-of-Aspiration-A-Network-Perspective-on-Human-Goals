# The Architecture of Aspiration: A Network Perspective on Human Goals

The primary objective of this project is to map the "landscape of human ambition" by analyzing digital trace data from the DayZero platform. Unlike previous psychological research that relied on theoretical models or small-scale surveys, this project aims to construct a larger-scale co-occurrence network to reveal the global topology and interconnectivity of goals. Ultimately, this analysis intends to demonstrate that human aspirations are not compartmentalized, but rather form a cohesive, deeply interlinked small-world network.

## The DayZero Project
The Day Zero Project is a digital platform and online community dedicated to goal setting, specifically popularized by the "101 things in 1001 days" challenge. Users register to create lists of aspirations from "Travel" to "Creative" pursuits, generating digital trace data through their actions & interactions. The platform features robust social networking elements; users can follow one another, track progress (marking goals as "done" or "in progress"), and comment on achievements. While the platform does not provide a public overview of all data, it allows for the scraping of user profiles and goal descriptions to analyze patterns in what the platform claims is the "largest community of goal setters in the world".

## Suitability Of The Topic For Social Network Analysis
The DayZero dataset is uniquely suited for graph analysis because it allows for the construction of a network where nodes represent specific goals and edges represent co-occurrence on a user's list. This structure transforms individual lists into a global "interest graph" that exhibits distinct small-world properties, characterized by high clustering coefficients and short path lengths. Beyond simple topology, the dataset supports weighted network analysis, where edge weights derived from co-occurrence frequency reveal the varying intensities of collective human desire rather than just binary connections. Furthermore, the availability of rich textual descriptions for the goals used enables a hybrid analysis that layers semantic data onto the physical graph, allowing researchers to calculate metrics like "attribute assortativity" to test whether semantically similar goals actually cluster together structurally. Ultimately, this rich combination of relational and attribute data offers a rare opportunity to empirically map the 'architecture of aspiration,' shifting the study of human motivation from small-scale surveys to a global, data-driven social network perspective.


## Statement of AI Use
Large Language Models (LLMs) were utilized as productivity tools during the development of this project. Specifically, AI assistance was employed for:
- Code Development: Assisting with the generation, optimization, and debugging of scripts to improve computational efficiency.
- Visualization: Refining the code used to generate figures and charts.
- Editorial Support: Suggestions for improving the conciseness and clarity of the texts.

We declare that the research topic, conceptualization, and all narrative text in the submitted paper are the original work of the authors. AI tools were strictly limited to technical support and improvement of conciseness of the writing.
