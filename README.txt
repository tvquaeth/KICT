(I've worked with conda venv)

THREE Python notebooks (just RUN cells):

1) Web Scraping (BeautifulSoup + Regex): scraping documents/course information
	Dependencies:
			pip install beautifulsoup4
			pip install google-cloud-translate
			pip install tika

2) Indexing (Whoosh): Creating index based on SCHEMA and documents
	Dependencies:
			pip install Whoosh
			pip install ortools

3) Erasmus Platform (Whoosh query + Knapsack + ipywidgets): Query over documents and show in interactive application
	Dependencies:		
			pip install Whoosh	
			pip install ortools
			pip install ipywidgets
			pip install appmode

TWO Directories:
1) courses: contains all documents (course information) -> constructed in 'Web Scraping'
2) indexdir: contains index on documents 		      -> constructed in 'Indexing'

TWO Files:
1) environment.yml -> for mybinder (dependencies to be installed)
2) lexicons.txt -> terms searchable in index per field (constructed in 'Indexing')

GoogleTranslateCredentials.json -> NOT INCLUDED ..