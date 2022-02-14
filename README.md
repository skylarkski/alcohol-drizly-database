## This repo is a work in progress!
# An Alcohol Dataset - Find what suits you!
*Note, this dataset is currently primarely Beers, although in the future I have plans to expand the alcohol selection with Wine and Liquor*

An alcohol dataset created by scraping <a href="https://drizly.com/">Drizly</a>, an alcohol retail and delivery company.

## Current Progress

<ul>
 	<li>Data scraped one of the largest alcohol delivery websites, <a href="https://drizly.com/"><b>Drizly</b></a>, using Python's libraries <em>BeautifulSoup4</em> and <em>Cloudscraper</em></li>
 	<li>Performed extensive data cleaning using <em>Excel</em> and <em>SQL</em> in <em>BigQuery</em>, insuring completeness and accuracy of gathered data</li>
 	<li>Found outliers in the data by graphing, using <em>Tableau</em> and R's <em>ggplot2</em>, which lead to more data cleaning</li>
 	<li><i>To be continued...</i></li>
</ul>

# Tools Used
<ul>
	<li><a href="https://pypi.org/project/beautifulsoup4/">BeautifulSoup4</a></li>
	<li><a href="https://github.com/VeNoMouS/cloudscraper">Cloudscraper</a></li>
	<li><a href="https://pandas.pydata.org/">Pandas</a></li>
	<li><a href="https://docs.python.org/3/library/json.html">JSON</a></li>
</ul>

  


# The 5 Ws
<ol>
	<li><strong>Why</strong> - Many alcohol datasets already exist, and they range from pop media Top 10 lists to expansive datasets on Breweries and Brands. Most projects lack the most essential atribute according to the youngest legal beer enthusiast demographic, <b>Price</b>. As with any product we enjoy, knowing the price of an item can factor greatly into the decisions made when purchasing alcohol.</li>
	<li><strong>What</strong> – I chose Drizly to gather data, because as well as having an astoudingly vast selection of beer, every item has a price. Some of the data gathered from Drizly lacked some metrics and atributes desirable for a dataset of this type, like most notably thorough ratings. With that being said, I still found it perfect for the use of this project, as the dataset created from Drizly's inventory provided an insight on what is commerically available nationwide, rather than making an expansive dataset of products excellent yet unobtainable. I believe that the merge of data of a mainstream service such as Drizly and an indie style alcohol critique forum such as <a href="https://untappd.com/">Untappd</a> or <a href="https://www.beeradvocate.com/">BeerAdvocate</a> is a match made in heaven.</li>
	<li><strong>Who</strong> – I am creating this dataset for those who need a more in depth look at the pricing of the beer industry, acording to Drizly's rates.</li>
	<li><strong>When</strong> – Now</li>
	<li><strong>Where</strong> – I am posting the project on Kaggle as a Jupiter notebook and on Github</li>
</ol>
