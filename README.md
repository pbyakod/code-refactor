## Marketing Optimization

### Short Description

This project aims to refactor the html code provided by a marketing agency. The idea of refactoring involves restructuring the existing html and css code without altering the websites browser design. By doing so, the company can present a structured code design that is more accesible and easier to implement on various search engines.  

### Task Outline

During this project, I will be overlooking the existing html and css files and continually altering the anatomy of the code. Most of the changes made to the code follow a certain guideline, that increases the code's accesibility to other web developers. The guidline includes implementing semantic html elements, ensuring that the code follows logical structuring, applying accesible alt attributes, and making sure that both the header and footer tags are properly organized. 

### Implementing Semantic Elements

The first thing noticeable about the html code is that there's a lot of unnecesary div classes implemented. The div class = "header" tag, for example, can be replaced by just a header tag, a semantic html element that describes its functionality. Since the initial code had a div class = "header", the css code had corresponding .header functions. To ensure that the external webpage remains the same, the css functions got changed from .header to header. The same changes are also made to the div class = "footer" tag. 

Furthermore, div tags in the body, which aren't semantic, can be replaced by more semantic elements such as section. Those replacements are also implemented in the refactoring. 