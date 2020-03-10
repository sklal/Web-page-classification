# Web-page-classification

Classification of Web page content is vital to many tasks in Web information retrieval such as maintaining Web directories and focused crawling which is used to selectively seek out web pages that are relevant to a pre-defined set of topics.

Why do we need Web Page Classification?
As an example, collecting and mining personal content on patients’ experiences with respect to disease symptoms and progression, treatment management, side effects and effectivenes can be very helpful in understanding a disease better.

The understanding attainable through mining this voluntarily contributed web content would be extremely expensive and time-consuming to capture via web queries. For example, a general query such as ‘breast cancer stories’ would pull up over 182 million results using Google web search.

However, if we can build an accurate classifier to pinpoint the right web pages that precisely contains patients' experiences using the URLs and page content, it can save a lot of time and compute for collecting this information.

# Problem Statement
In this project, we are provided with URLs from 53000+ web pages. The objective is to build a classifier that can classify the web pages into their respective classes and Each web page can belong to only 1 class.

Basically given the complete url, predict the tag a web page belongs to out of 9 predefined tags as given below:

People profile
Conferences/Congress
Forums
News article
Clinical trials
Publication
Thesis
Guidelines
Others
# Data Description
The dataset contains the following features:

web page_ID: Unique ID for the web page (1,2,3.... )
Domain: Domain of the web page (Example: www.fiercepharma.com)
Url: Complete URL of the web page (Example: http://www.fiercepharma.com/marketing/tecfidera-gilenya-and-aubagio-s-3-way-battle-for-ms-share-about-to-get-more-interesting)
Tag: (Target) Tag (class) of the web page
The objective here is to predict the class of the web page from the above mentioned 9 classes.
