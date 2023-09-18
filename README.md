# US-RSE-conference-2023

### Abstract (not on poster)
Researchers are increasingly using web applications to promote their work in an accessible and engaging format. By leveraging interactive visualizations and intuitive interfaces, researchers can effectively share their data and code within the scientific community. RSEs may be interested in working with researchers to build web applications that have the potential to improve code and data reuse. Despite the value of these communication tools, maintaining them eventually falls to the researchers who are not incentivized to learn new tools and technologies.  We present a network analysis visualization tool that is demonstrative of how an existing research workflow in a Jupyter Notebook can be transformed into complex web applications without leaving the JupyterLab development environment. This application uses Jupyter widgets (ipywidgets) to add interactive components - such as sliders, dropdown menus, etc. - and a network visualization widget (ipycytoscape) to visually explore and analyze a large citation network. Voila strips away code cells, leaving behind only interactive browser components, resulting in a fully-fledged user interface. By adapting existing workflows, researchers working with RSEs can benefit from the familiarity of the codebase and the development environment. This helps them maintain the application beyond the period of collaboration. Based on our experience, we recommend that researchers and RSEs consider the adoption of Jupyter Notebook and Jupyter widgets to transform existing workflows into intuitive, interactive, and aesthetic web applications that can effectively communicate their research findings. 

### Introduction
- Researchers are increasingly using web applications to promote their work in an accessible and engaging format to share their  data and code within the scientific community via interactive visualizations and intuitive interfaces. RSEs may be interested in working with researchers to build web applications that have the potential to improve code and data reuse. Despite the value of these communication tools, maintaining them eventually falls to the researchers who are not incentivized to learn new tools and technologies. 

### Our problem 
- The dataset is a meticulously curated collection of 7000 articles related to agent-based modeling. These articles span diverse domains such as historical, economics, agriculture, and more, showcasing the versatility and impact of agent-based modeling.
- We need a method in which we are able to visualize and observe important properties of this dataset. 

### Our solulu
- We present a network analysis visualization tool we built which is able to stay within the existing research workflow and achieve insightful information about the dataset in a dynamic manner.
- This interactive tool provides a dynamic way to explore and analyze code sharing and model documentation practices in individual-based and agent-based models. This tool allows users to explore the properties of and relationships among 7500 hand-picked articles describing IBMs or ABMs across a wide range of research domains up to the year 2018.

### Methods
- This application uses Jupyter widgets (ipywidgets) to add interactive components - such as sliders, dropdown menus, etc.
- A network visualization widget (ipycytoscape) to visually explore and analyze a large citation network.
- Voila strips away code cells, leaving behind only interactive browser components, resulting in a fully-fledged user interface.

### Conclusions
- Based on our experience, we recommend that researchers and RSEs consider the adoption of Jupyter Notebook and Jupyter widgets to transform existing workflows into intuitive, interactive, and aesthetic web applications that can effectively communicate their research findings.
- JupyterLab offers many such widgets and extensions that allow you to adapt your workflow to the required task at hand, just as we did. 
- By adapting existing workflows, researchers working with RSEs can benefit from the familiarity of the codebase and the development environment. This helps them maintain the application beyond the period of collaboration.  

### Acknowledgments
![Better Scientific Software]((https://bssw.io/assets/bssw-78ff90ae191cabb76ede7766c2b78362ed487d78f12356638c14d6fe939f3d86.png))
I'd like to thank Nicole Brewer, David Costello and the rest of the Digital Innovation Group for their continued support of my outreach work in this area.

This work was supported by the Better Scientific Software Fellowship Program, funded by the Exascale Computing Project (17-SC-20-SC), a collaborative effort of the U.S. Department of Energy (DOE) Office of Science and the National Nuclear Security Administration; and by the National Science Foundation (NSF) under Grant No. 2154495. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the DOE or NSF.
