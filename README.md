
### Hi there!!! I'm Sivaram Rasathurai <img src="https://github.com/blackcater/blackcater/raw/master/images/Hi.gif" height="32" />

## Who I am

<?xml version="1.0" encoding="utf-8"?>
<feed xmlns="http://www.w3.org/2005/Atom" xmlns:creativeCommons="http://backend.userland.com/creativeCommonsRssModule" xmlns:re="http://purl.org/atompub/rank/1.0">
    <title type="text">Active questions tagged python - Stack Overflow</title>
    <link rel="self" href="https://stackoverflow.com/feeds/tag/python" type="application/atom+xml" />
    <link rel="alternate" href="https://stackoverflow.com/questions/tagged/?tagnames=python&amp;sort=active" type="text/html" />
    <subtitle>most recent 30 from stackoverflow.com</subtitle>
    <updated>2022-07-26T06:13:52Z</updated>
    <id>https://stackoverflow.com/feeds/tag/python</id>
    <creativeCommons:license>https://creativecommons.org/licenses/by-sa/4.0/rdf</creativeCommons:license> 
    <entry>
        <id>https://stackoverflow.com/q/71437283</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How do I choose the correct input shape to my Dense Layer?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="tensorflow" />
            <category scheme="https://stackoverflow.com/tags" term="keras" />
            <category scheme="https://stackoverflow.com/tags" term="neural-network" />
        <author>
            <name>Random Guy</name>
            <uri>https://stackoverflow.com/users/18438056</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/71437283/how-do-i-choose-the-correct-input-shape-to-my-dense-layer" />
        <published>2022-03-11T10:42:43Z</published>
        <updated>2022-07-26T06:09:20Z</updated>
        <summary type="html">
            &lt;p&gt;I am working on a dataset with following input shapes of X and Y&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;print(X_train.shape, Y_train.shape)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;(211968, 1024, 2) (211968, 24)&lt;/p&gt;&#xA;&lt;p&gt;Here&#x27;s my simple Model with summary and the error:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;batch_size = 128&#xA;hidden_units = 256&#xA;dropout = 0.45&#xA;model = Sequential()&#xA;model.add(Dense(hidden_units,input_shape=(1024,2)))&#xA;model.add(Activation(&#x27;relu&#x27;))&#xA;model.add(Dropout(dropout))&#xA;model.add(Dense(hidden_units))&#xA;model.add(Activation(&#x27;relu&#x27;))&#xA;model.add(Dropout(dropout))&#xA;model.add(Dense(24))&#xA;model.add(Activation(&#x27;softmax&#x27;))&#xA;model.summary()&#xA;model.compile(loss=&#x27;categorical_crossentropy&#x27;,optimizer=&#x27;adam&#x27;,metrics=[&#x27;accuracy&#x27;])&#xA;model.fit(X_train, Y_train, epochs=30, batch_size=batch_size)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;ValueError: Shapes (128, 24) and (128, 1024, 24) are incompatible&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/24118234</id>
        <re:rank scheme="https://stackoverflow.com">13</re:rank>
        <title type="text">atom editor indentation error with Python</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="indentation" />
            <category scheme="https://stackoverflow.com/tags" term="atom-editor" />
        <author>
            <name>Ossama</name>
            <uri>https://stackoverflow.com/users/612242</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/24118234/atom-editor-indentation-error-with-python" />
        <published>2014-06-09T10:23:47Z</published>
        <updated>2022-07-26T06:09:11Z</updated>
        <summary type="html">
            &lt;p&gt;I am new to atom, so I opened my existing code using atom and modified few lines, then when I tried running the code with python, I get the following error:&lt;/p&gt;&#xA;&#xA;&lt;pre&gt;&lt;code&gt;IndentationError: unindent does not match any outer indentation level&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&#xA;&lt;p&gt;I realized that Atom editor does indent my code differently to what I had. refer to the attached picture below showing the different indentation styles. line 1300 is the old indentation and 1301 is the one created by Atom&lt;/p&gt;&#xA;&#xA;&lt;p&gt;How can I fix this without modifying my 1000&#x2B; line code and so that atom uses the same style of indentation.&lt;/p&gt;&#xA;&#xA;&lt;p&gt;&lt;img src=&quot;https://i.stack.imgur.com/nV2mQ.png&quot; alt=&quot;enter image description here&quot;&gt;&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/46109143</id>
        <re:rank scheme="https://stackoverflow.com">1</re:rank>
        <title type="text">How to run a python script from an MQL4 EA-process ( MetaTrader4 Terminal )?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="algorithmic-trading" />
            <category scheme="https://stackoverflow.com/tags" term="mql4" />
            <category scheme="https://stackoverflow.com/tags" term="metatrader4" />
            <category scheme="https://stackoverflow.com/tags" term="forex" />
        <author>
            <name>xion</name>
            <uri>https://stackoverflow.com/users/7816917</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/46109143/how-to-run-a-python-script-from-an-mql4-ea-process-metatrader4-terminal" />
        <published>2017-09-08T05:20:01Z</published>
        <updated>2022-07-26T06:09:10Z</updated>
        <summary type="html">
            &lt;p&gt;I have a simple &lt;code&gt;test.py&lt;/code&gt; script that I would like to run from an MQL4 EA.&lt;/p&gt;&#xA;&#xA;&lt;p&gt;How can I implement this?&lt;/p&gt;&#xA;&#xA;&lt;p&gt;I have tried using &lt;strong&gt;&lt;code&gt;ShellExecute()&lt;/code&gt;&lt;/strong&gt; but that will not work in my case as I am running MetaTrader4 Terminal on a linux machine and thus cannot call windows based &lt;code&gt;ShellExecute()&lt;/code&gt; ( even with a &lt;code&gt;wine&lt;/code&gt; ).&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118407</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">Can you help me with iterating in python</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="loops" />
            <category scheme="https://stackoverflow.com/tags" term="iterator" />
        <author>
            <name>Andy Panda</name>
            <uri>https://stackoverflow.com/users/19616200</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118407/can-you-help-me-with-iterating-in-python" />
        <published>2022-07-26T06:09:03Z</published>
        <updated>2022-07-26T06:09:03Z</updated>
        <summary type="html">
            &lt;p&gt;I am learning python iterators and i didnt understand one thing:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;class MyNumbers:&#xA;  def __iter__(self):&#xA;    self.n = 0&#xA;    return self&#xA;&#xA;  def __next__(self):&#xA;    self.n &#x2B;=1&#xA;    return self.n&#xA;&#xA;mynumbers = MyNumbers()&#xA;mynum = iter(mynumbers)&#xA;&#xA;print(next(mynum))&#xA;print(next(mynum))&#xA;print(next(mynum))&#xA;print(next(mynum))&#xA;print(next(mynum))&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Why in &lt;code&gt;def __iter__(self): self.n = 0 return self&lt;/code&gt; we return self? what is it for?&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73117864</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">function with while loop python with two different result</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="function" />
            <category scheme="https://stackoverflow.com/tags" term="loops" />
            <category scheme="https://stackoverflow.com/tags" term="if-statement" />
            <category scheme="https://stackoverflow.com/tags" term="while-loop" />
        <author>
            <name>Jovian Aditya</name>
            <uri>https://stackoverflow.com/users/19601668</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73117864/function-with-while-loop-python-with-two-different-result" />
        <published>2022-07-26T04:50:00Z</published>
        <updated>2022-07-26T06:08:57Z</updated>
        <summary type="html">
            &lt;p&gt;I want to code a function and get expected results like this (when i input number = 10):&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;10&#xA;9&#xA;8&#xA;7&#xA;6&#xA;5&#xA;4&#xA;3&#xA;2&#xA;1&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;And when i input number = -10 :&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;-10&#xA;-9&#xA;-8&#xA;-7&#xA;-6&#xA;-5&#xA;-4&#xA;-3&#xA;-2&#xA;-1&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;This is my code. Only works when number = 10. No result when im trying to input a = -10:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;def function_while(number):&#xA;i=0&#xA;while i&amp;lt;number:     &#xA;    if True:&#xA;        print(number-i)&#xA;    else:&#xA;        print(number&#x2B;1)&#xA;    i&#x2B;=1&#xA;function_while(number)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Is there any solution?&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118302</id>
        <re:rank scheme="https://stackoverflow.com">1</re:rank>
        <title type="text">python numpy find y value based on x value</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="numpy" />
        <author>
            <name>dummy</name>
            <uri>https://stackoverflow.com/users/15497620</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118302/python-numpy-find-y-value-based-on-x-value" />
        <published>2022-07-26T05:55:58Z</published>
        <updated>2022-07-26T06:08:22Z</updated>
        <summary type="html">
            &lt;p&gt;I want to get column y that has maximum x value.&#xA;If I have&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;arr = [[1, 1],[1, 2],[3, 0],[4, 7],[3, 1],[4, 6]]&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Since the minimum x value is 1, I want the value 1 and 2.&#xA;So far, I got the minimum x value by&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;min = np.amin(arr, axis=0)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;but I don&#x27;t know how to get the other value which has the min value&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73087847</id>
        <re:rank scheme="https://stackoverflow.com">-1</re:rank>
        <title type="text">How to detect and filter text/numbers with strikethrough in a cell containing both struck and unstruck text in Python (openpyxl)?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="python-3.x" />
            <category scheme="https://stackoverflow.com/tags" term="excel" />
            <category scheme="https://stackoverflow.com/tags" term="openpyxl" />
            <category scheme="https://stackoverflow.com/tags" term="xlsx" />
        <author>
            <name>Vignesh B</name>
            <uri>https://stackoverflow.com/users/17801190</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73087847/how-to-detect-and-filter-text-numbers-with-strikethrough-in-a-cell-containing-bo" />
        <published>2022-07-23T03:36:11Z</published>
        <updated>2022-07-26T06:08:18Z</updated>
        <summary type="html">
            &lt;p&gt;&lt;a href=&quot;https://i.stack.imgur.com/t9CzD.png&quot; rel=&quot;nofollow noreferrer&quot;&gt;&lt;img src=&quot;https://i.stack.imgur.com/t9CzD.png&quot; alt=&quot;enter image description here&quot; /&gt;&lt;/a&gt;&lt;/p&gt;&#xA;&lt;p&gt;Hi, I am trying to filter out the struck texts/numbers in xlsx file using python using openpyxl. I am able to remove the cells containing struck texts and numbers. However, when there are two values in a cell, one with struck and the other unstruck, I am unable to do it. I tried splitting and then doing it but couldn&#x27;t do it.&#xA;I have been using &lt;code&gt;cell.font.strikethrough&lt;/code&gt; to detect.&lt;/p&gt;&#xA;&lt;p&gt;My code:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;import openpyxl as op&#xA;wb=op.load_workbook(&amp;quot;Some_Workbook.xlsx&amp;quot;)&#xA;ws=wb[&#x27;Sheet1&#x27;]&#xA;&#xA;for row in ws.iter_rows(max_row=1,max_col=2):&#xA;    for cell in row:&#xA;        if cell.font.strike:&#xA;            print(&#x27;struck&#x27;,cell.value)&#xA;        else:&#xA;            print(&#x27;unstruck&#x27;,cell.value)&#xA;&#xA;wb.close()&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I used the above code to find if the cell had values that were struck.&lt;/p&gt;&#xA;&lt;p&gt;Please help.&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118333</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">What is the correct format code for this type of date?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="date" />
            <category scheme="https://stackoverflow.com/tags" term="datetime" />
            <category scheme="https://stackoverflow.com/tags" term="formatting" />
        <author>
            <name>mathslover</name>
            <uri>https://stackoverflow.com/users/19416480</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118333/what-is-the-correct-format-code-for-this-type-of-date" />
        <published>2022-07-26T06:00:08Z</published>
        <updated>2022-07-26T06:07:43Z</updated>
        <summary type="html">
            &lt;p&gt;I have a numpy array (called dates) of dates (as strings) which I thought were in the form %Y-%m-%d %H:%M:%S. However, I get an error that I have dates such as 2021-05-11T00:00:00.0000000. Not sure where did that additional &#x27;T&#x27; come and why is the time so precise.&#xA;I am trying to get rid of the time and only have the date.&lt;/p&gt;&#xA;&lt;p&gt;My code is here:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;dates = dataset.iloc[:,0].to_numpy()&#xA;&#xA;newDates = []&#xA;for i in range(0,len(dates)):&#xA;    newDates.append(datetime.strptime(dates[i], &#x27;%Y-%m-%dT%H:%M:%S.%f&#x27;))&#xA;    newDates[i] = newDates[i].strftime(&#x27;%Y-%m-%d&#x27;)&#xA;&#xA;dates = newDates&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I get an error saying &amp;quot;ValueError: unconverted data remains: 0&amp;quot;.&#xA;If I wrote instead&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;newDates.append(datetime.strptime(dates[i], &#x27;%Y-%m-%dT%H:%M:%S%f&#x27;))&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I get an error &amp;quot;ValueError: unconverted data remains: .0000000&amp;quot;.&#xA;In which format should the date be given?&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118392</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How can I optimize my youtube API calls that I don&#x27;t reach the daily quota?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="youtube-api" />
            <category scheme="https://stackoverflow.com/tags" term="youtube-data-api" />
        <author>
            <name>dlenker</name>
            <uri>https://stackoverflow.com/users/10389718</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118392/how-can-i-optimize-my-youtube-api-calls-that-i-dont-reach-the-daily-quota" />
        <published>2022-07-26T06:07:07Z</published>
        <updated>2022-07-26T06:07:07Z</updated>
        <summary type="html">
            &lt;p&gt;I&#x27;m working on a small python script that scans through my discogs.com collection (database for vinyl records where one can track their collection) and creates a list of all the songs on each record and saves them in a list.&#xA;Afterwards, I use the youtube data API to do a search for song title, artist and label to find the video for each song and save the video IDs. With that I can then create a youtube playlist of all the songs in my collection.&lt;/p&gt;&#xA;&lt;p&gt;My problem is that I reach the quota after searching for around 100 songs. How can I optimize my search so my 10&#x27;000 quota is not reached that quickly?&lt;/p&gt;&#xA;&lt;p&gt;Relevant code snippet:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;query = &#x27; - &#x27;.join([artist, title, catno])&#xA;            &#xA;request = youtube.search().list(q=query, part=&#x27;snippet&#x27;,  maxResults=1)&#xA;res = request.execute()&#xA;video_id = res[&#x27;items&#x27;][0][&#x27;id&#x27;][&#x27;videoId&#x27;]&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73117245</id>
        <re:rank scheme="https://stackoverflow.com">-1</re:rank>
        <title type="text">Nested List to Dictionary and back again</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="pandas" />
        <author>
            <name>Dan Neal</name>
            <uri>https://stackoverflow.com/users/6451732</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73117245/nested-list-to-dictionary-and-back-again" />
        <published>2022-07-26T02:51:22Z</published>
        <updated>2022-07-26T06:05:54Z</updated>
        <summary type="html">
            &lt;p&gt;I have some data structured like this:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;[[&amp;quot;ID&amp;quot;, &amp;quot;Header1&amp;quot;, &amp;quot;Header2&amp;quot;], [1, &amp;quot;a1&amp;quot;, &amp;quot;a2&amp;quot;], [2, &amp;quot;b1&amp;quot;, &amp;quot;b2&amp;quot;]]&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I want to be able to convert this to a dictionary (or maybe pandas dataframe?) that looks like this (or has constant lookup for ID).&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;{&#xA;  1: {&#xA;    &amp;quot;Header1&amp;quot;: &amp;quot;a1&amp;quot;,&#xA;    &amp;quot;Header2&amp;quot;: &amp;quot;a2&amp;quot;,&#xA;  },&#xA;  2: {&#xA;    &amp;quot;Header1&amp;quot;: &amp;quot;b1&amp;quot;,&#xA;    &amp;quot;Header2&amp;quot;: &amp;quot;b2&amp;quot;,&#xA;  }&#xA;}&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;But here is the tricky part.... after doing some processing (lets say adding a 3rd id and dictionary), I need to be able to convert it back to a nested list with the headers in the same order.&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;[[&amp;quot;ID&amp;quot;, &amp;quot;Header1&amp;quot;, &amp;quot;Header2&amp;quot;], [1, &amp;quot;a1&amp;quot;, &amp;quot;a2&amp;quot;], [2, &amp;quot;b1&amp;quot;, &amp;quot;b2&amp;quot;], [3, &amp;quot;c1&amp;quot;, &amp;quot;c2&amp;quot;]]&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Is there a simple way of doing this in pandas?  Or is dictionary the way to go?&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118190</id>
        <re:rank scheme="https://stackoverflow.com">1</re:rank>
        <title type="text">Why can&#x27;t I find table when scraping website?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="html" />
            <category scheme="https://stackoverflow.com/tags" term="web" />
            <category scheme="https://stackoverflow.com/tags" term="beautifulsoup" />
        <author>
            <name>Sean</name>
            <uri>https://stackoverflow.com/users/9181637</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118190/why-cant-i-find-table-when-scraping-website" />
        <published>2022-07-26T05:40:45Z</published>
        <updated>2022-07-26T06:05:45Z</updated>
        <summary type="html">
            &lt;p&gt;I am trying to fix this code where I&#x27;m trying to get table from SEC website of this company&lt;/p&gt;&#xA;&lt;p&gt;&lt;strong&gt;Libraries:&lt;/strong&gt;&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;# import our libraries&#xA;import requests&#xA;import pandas as pd&#xA;from bs4 import BeautifulSoup&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;&lt;strong&gt;Definition of parameters for search:&lt;/strong&gt;&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;# base URL for the SEC EDGAR browser&#xA;endpoint = r&amp;quot;https://www.sec.gov/cgi-bin/browse-edgar&amp;quot;&#xA;&#xA;# define our parameters dictionary&#xA;param_dict = {&#x27;action&#x27;:&#x27;getcompany&#x27;,&#xA;              &#x27;CIK&#x27;:&#x27;1265107&#x27;,&#xA;              &#x27;type&#x27;:&#x27;10-k&#x27;,&#xA;              &#x27;dateb&#x27;:&#x27;20190101&#x27;,&#xA;              &#x27;owner&#x27;:&#x27;exclude&#x27;,&#xA;              &#x27;start&#x27;:&#x27;&#x27;,&#xA;              &#x27;output&#x27;:&#x27;&#x27;,&#xA;              &#x27;count&#x27;:&#x27;100&#x27;}&#xA;&#xA;# request the url, and then parse the response.&#xA;response = requests.get(url = endpoint, params = param_dict)&#xA;soup = BeautifulSoup(response.content, &#x27;html.parser&#x27;)&#xA;&#xA;# Let the user know it was successful.&#xA;print(&#x27;Request Successful&#x27;)&#xA;print(response.url)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;&lt;strong&gt;This is where the problem is, when I try to loop over the content of the table i get error shown below as if the table does not exist.&lt;/strong&gt;&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;# find the document table with our data&#xA;doc_table = soup.find_all(&#x27;table&#x27;, class_=&#x27;tableFile2&#x27;)&#xA;&#xA;# define a base url that will be used for link building.&#xA;base_url_sec = r&amp;quot;https://www.sec.gov&amp;quot;&#xA;&#xA;master_list = []&#xA;&#xA;# loop through each row in the table.&#xA;for row in doc_table[0].find_all(&#x27;tr&#x27;):&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;&lt;strong&gt;The error:&lt;/strong&gt;&lt;/p&gt;&#xA;&lt;p&gt;&lt;a href=&quot;https://i.stack.imgur.com/8NEXm.png&quot; rel=&quot;nofollow noreferrer&quot;&gt;&lt;img src=&quot;https://i.stack.imgur.com/8NEXm.png&quot; alt=&quot;enter image description here&quot; /&gt;&lt;/a&gt;&lt;/p&gt;&#xA;&lt;p&gt;Here is the link to the website I am trying to scrape &lt;a href=&quot;https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&amp;amp;CIK=1265107&amp;amp;type=10-k&amp;amp;dateb=20190101&amp;amp;owner=exclude&amp;amp;start=&amp;amp;output=&amp;amp;count=100&quot; rel=&quot;nofollow noreferrer&quot;&gt;https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&amp;amp;CIK=1265107&amp;amp;type=10-k&amp;amp;dateb=20190101&amp;amp;owner=exclude&amp;amp;start=&amp;amp;output=&amp;amp;count=100&lt;/a&gt;&#xA;When I inspect the elements of the website I can&#x27;t find anything that could cause this error.&lt;/p&gt;&#xA;&lt;p&gt;Thank you for any help.&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118380</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How to implement logout functionality in django given that the admin selects the logout duration depending upon the options given via radio button</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="django" />
            <category scheme="https://stackoverflow.com/tags" term="frontend" />
            <category scheme="https://stackoverflow.com/tags" term="backend" />
            <category scheme="https://stackoverflow.com/tags" term="logout" />
        <author>
            <name>Meenal</name>
            <uri>https://stackoverflow.com/users/19622523</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118380/how-to-implement-logout-functionality-in-django-given-that-the-admin-selects-the" />
        <published>2022-07-26T06:05:28Z</published>
        <updated>2022-07-26T06:05:28Z</updated>
        <summary type="html">
            &lt;p&gt;I have an HTML page with the 4 radio buttons to select the time of logout:&#xA;So the admin can select after how many minutes he/she wants to log out of the Django application.&lt;/p&gt;&#xA;&lt;p&gt;Auto-logout options: 15mins 30mins 1hour never (radio button will be there)&lt;/p&gt;&#xA;&lt;p&gt;So how do we implement it? I am using the default login/logout template of django.allauth&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73116638</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">Python Script to transfer file from AWS S3 to Azure BLOB in databricks</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="python-3.x" />
            <category scheme="https://stackoverflow.com/tags" term="azure" />
            <category scheme="https://stackoverflow.com/tags" term="amazon-s3" />
            <category scheme="https://stackoverflow.com/tags" term="azure-databricks" />
        <author>
            <name>K.Tom</name>
            <uri>https://stackoverflow.com/users/9064240</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73116638/python-script-to-transfer-file-from-aws-s3-to-azure-blob-in-databricks" />
        <published>2022-07-26T00:33:45Z</published>
        <updated>2022-07-26T06:04:52Z</updated>
        <summary type="html">
            &lt;p&gt;Trying to copyfile AWS S3 to Azure blob storage using Access Key ID and Access secret Key ID in databricks.&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;Code:&#xA;====&#xA; set AWS_ACCESS_KEY_ID=&#x27;ABCDED&#x27;&#xA; set AWS_SECRET_ACCESS_KEY=&#x27;12345&#x27;&#xA;&#xA; azcopy cp &amp;quot;https://s3://emp-data/tsc/&amp;quot; &amp;quot;https://empdata.blob.core.windows.net/awstosf/&amp;quot; --recursive&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;The above code is not working and getting invalid syntax&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118375</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">DynamoDB query timestamp item in a loop, calculate timediff and add this result to new table row</title>
            <category scheme="https://stackoverflow.com/tags" term="javascript" />
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="lambda" />
            <category scheme="https://stackoverflow.com/tags" term="amazon-dynamodb" />
        <author>
            <name>JMS77</name>
            <uri>https://stackoverflow.com/users/81277</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118375/dynamodb-query-timestamp-item-in-a-loop-calculate-timediff-and-add-this-result" />
        <published>2022-07-26T06:04:52Z</published>
        <updated>2022-07-26T06:04:52Z</updated>
        <summary type="html">
            &lt;p&gt;using AWS Lambda, I want to be able to:&#xA;query item eventtime (UTC) from a dynamoDB table in a loop for all items, calculate time difference now()-eventtime, store the result value into a dynamodb item&#xA;I have not found a way to achieve this using AWS SDK DynamoDB&#xA;is it possible to call different dynamoDB object within the same lambda execution handler ?&#xA;thanks for ideas&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118240</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">The error in highlighting function using fitz package &amp; python code</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="highlight" />
        <author>
            <name>jane doe</name>
            <uri>https://stackoverflow.com/users/13303557</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118240/the-error-in-highlighting-function-using-fitz-package-python-code" />
        <published>2022-07-26T05:47:54Z</published>
        <updated>2022-07-26T06:04:44Z</updated>
        <summary type="html">
            &lt;p&gt;I have a pdf text highlighting problem, here i&#x27;m using &lt;em&gt;fitz&lt;/em&gt; for highlighting the specific text.&lt;br /&gt;&#xA;But when I run the system display I get a &amp;quot;segmentation fault&amp;quot; and the highlighted pdf not being saved.&#xA;Here I attached the code.&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;import fitz&#xA;&#xA;input1 = &amp;quot;abc.pdf&amp;quot;&#xA;input2 = &amp;quot;xyz.pdf&amp;quot;&#xA;&#xA;#Strikethrough&#xA;doc = fitz.open(input1)&#xA;length = len(doc)&#xA;&#xA;for text in changed_lines_set:&#xA;    for i in range(length):&#xA;        page = doc[i]&#xA;        text_instances = page.searchFor(text)&#xA;        highlight = page.addUnderlineAnnot(text_instances)&#xA;        highlight.setColors({&amp;quot;stroke&amp;quot;:(0, 0, 1), &amp;quot;fill&amp;quot;:(0.75, 0.8, 0.95)})&#xA;        highlight.update()&#xA;        # print(highlight)&#xA;doc.save(&amp;quot;output_file1.pdf&amp;quot;)&#xA;&#xA;# Highlighting&#xA;doc = fitz.open(input2)&#xA;length = len(doc)&#xA;for text in deleted_lines_set:&#xA;    for i in range(length):&#xA;        page = doc[i]&#xA;        text_instances = page.searchFor(text)&#xA;        highlight = page.addHighlightAnnot(text_instances)&#xA;        highlight.setColors({&amp;quot;stroke&amp;quot;:(0.5, 1, 1), &amp;quot;fill&amp;quot;:(0.75, 0.8, 0.95)})&#xA;        highlight.update()&#xA;doc.save(&amp;quot;output_file2.pdf&amp;quot;)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I got an error hint line: &lt;code&gt;highlight.update()&lt;/code&gt;&lt;/p&gt;&#xA;&lt;p&gt;How to solve this issue.&lt;br /&gt;&#xA;Thanks in advance&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118159</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How to apply H (homography matrix) to a list of x,y coordinates</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="numpy" />
            <category scheme="https://stackoverflow.com/tags" term="matrix" />
            <category scheme="https://stackoverflow.com/tags" term="homography" />
        <author>
            <name>J33T</name>
            <uri>https://stackoverflow.com/users/14983566</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118159/how-to-apply-h-homography-matrix-to-a-list-of-x-y-coordinates" />
        <published>2022-07-26T05:36:24Z</published>
        <updated>2022-07-26T06:04:41Z</updated>
        <summary type="html">
            &lt;p&gt;I have obtained a homography matrix H after applying it on a some coordinates from 2 images.&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;[[ 9.62122460e-02  4.19126557e-01  2.78378319e&#x2B;02]&#xA; [ 2.84972076e-02  1.04148707e&#x2B;00 -2.60554265e&#x2B;01]&#xA; [-7.03233591e-05  2.00171167e-03  1.00000000e&#x2B;00]]&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Now i want to apply this matrix to each x,y coordinate in a list, how can i do this in python ?&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;x = [336.0, 21.0, 874.0, 407.0, 671.0, 587.0, 153.5, 1030.5, 1032.5, 663.5, 793.5]&#xA;&#xA;y = [179.0, 205.0, 166.0, 148.0, 300.0, 93.0, 185.0, 214.0, 312.0, 182.0, 402.0]&#xA;&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73115407</id>
        <re:rank scheme="https://stackoverflow.com">1</re:rank>
        <title type="text">What is the difference between ... and : in Pytorch tensors and numpy indexing</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="numpy" />
            <category scheme="https://stackoverflow.com/tags" term="pytorch" />
            <category scheme="https://stackoverflow.com/tags" term="tensor" />
        <author>
            <name>Youcef</name>
            <uri>https://stackoverflow.com/users/9784337</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73115407/what-is-the-difference-between-and-in-pytorch-tensors-and-numpy-indexing" />
        <published>2022-07-25T21:12:59Z</published>
        <updated>2022-07-26T06:04:33Z</updated>
        <summary type="html">
            &lt;p&gt;I am trying to get used to Pytorch indexing. However I couldn&#x27;t understand the difference between tensor[:,-1] (which should print the last column) and tensor[...,-1] which is printing different output (output2)&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;import torch&#xA;tensor = torch.rand([3,3,3,3])&#xA;print(&#x27;Output1&#x27;)&#xA;print(tensor[:,-1])&#xA;print(&#x27;Output2&#x27;)&#xA;print(tensor[...,-1])&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73108877</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How do I send data from my frontend written in React to my backend written in Python?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="reactjs" />
            <category scheme="https://stackoverflow.com/tags" term="flask" />
        <author>
            <name>Yasho Bapat</name>
            <uri>https://stackoverflow.com/users/19617389</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73108877/how-do-i-send-data-from-my-frontend-written-in-react-to-my-backend-written-in-py" />
        <published>2022-07-25T12:00:57Z</published>
        <updated>2022-07-26T06:04:31Z</updated>
        <summary type="html">
            &lt;p&gt;`from flask import Flask, jsonify, request&#xA;from flask_cors import CORS&lt;/p&gt;&#xA;&lt;p&gt;app = Flask(&lt;strong&gt;name&lt;/strong&gt;)&#xA;cors = CORS(app)&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;@app.route(&#x27;/receiver&#x27;, methods = [&#x27;POST&#x27;])&#xA;def postME():&#xA;    data = request.get_json()&#xA;    #data = jsonify(data)&#xA;    print(data.json())&#xA;    return data&#xA;&#xA;&#xA;if __name__ == &amp;quot;__main__&amp;quot;:&#xA;    app.run(debug=True)&#xA;&#xA;`import React, {useState, useEffect} from &#x27;react&#x27;;&#xA;import logo from &#x27;./logo.svg&#x27;;&#xA;import &#x27;./App.css&#x27;;&#xA;&#xA;function App(){&#xA;&#xA;    const [query, setQuery] = useState(&#x27;&#x27;);&#xA;    const updateSearch = e =&amp;gt; {&#xA;        setQuery(e.target.value);&#xA;    //console.log(query);&#xA;    }&#xA;    &#xA;    const [atID, setAtID] = useState(&#x27;vangyachibhaji&#x27;);&#xA;&#xA;    useEffect(() =&amp;gt; {&#xA;        console.log(query);&#xA;    }, [atID])&#xA;&#xA;    const searchID = e =&amp;gt; {&#xA;        e.preventDefault();&#xA;        setAtID(query);&#xA;        console.log(&amp;quot;query: &amp;quot; &#x2B; query);&#xA;        setQuery(&#x27;&#x27;);&#xA;        postToPython();&#xA;    }&#xA;    const postToPython = () =&amp;gt; {&#xA;        fetch(&amp;quot;http://127.0.0.1:5000/receiver&amp;quot;, &#xA;        {&#xA;            method: &#x27;post&#x27;,&#xA;            headers: {&#xA;                &#x27;Content-type&#x27;: &#x27;application/json&#x27;,&#xA;                &#x27;Accept&#x27;: &#x27;application/json&#x27;&#xA;            },&#xA;        // Strigify the payload into JSON:&#xA;        body:JSON.stringify(query)}).then(res=&amp;gt;{&#xA;                if(res.ok){&#xA;                    return res.json()&#xA;                }else{&#xA;                    alert(&amp;quot;something is wrong&amp;quot;)&#xA;                }&#xA;            }).then(jsonResponse=&amp;gt;{&#xA;                &#xA;                // Log the response data in the console&#xA;                console.log(jsonResponse)&#xA;            } &#xA;            ).catch((err) =&amp;gt; console.error(err));&#xA;            &#xA;           } &#xA;    &#xA;&#xA;    return(&#xA;        &amp;lt;div className=&#x27;Search-bar&#x27;&amp;gt;&#xA;            &amp;lt;form className = &#x27;search-form&#x27; onSubmit={searchID}&amp;gt;&#xA;                &amp;lt;input type=&amp;quot;text&amp;quot; placeholder=&#x27;search&#x27; onChange={updateSearch}/&amp;gt;&#xA;                &amp;lt;button &amp;gt;search&amp;lt;/button&amp;gt;&#xA;            &amp;lt;/form&amp;gt;&#xA;        &amp;lt;/div&amp;gt;&#xA;    );&#xA;}&#xA;&#xA;export default App;&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;&lt;code&gt; &lt;/code&gt;I want to send data from a search bar in my webpage (written in React JS) to my python code. The data will be a single simple string, which will be sent to my python code and will be treated as the input.&#xA;I tried doing it using Flask but I keep getting an Error 405 (Method Not Allowed). Can someone pls help me out I have been racking my brain for the past 2 days (the stuff after app.run(debug = True) is my React code (.js)&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118350</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How to initialize the parameter in the cross validation method and get the final model after training and evaluating using this method?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="scikit-learn" />
            <category scheme="https://stackoverflow.com/tags" term="cross-validation" />
            <category scheme="https://stackoverflow.com/tags" term="modeling" />
            <category scheme="https://stackoverflow.com/tags" term="training-data" />
        <author>
            <name>elldora</name>
            <uri>https://stackoverflow.com/users/11529057</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118350/how-to-initialize-the-parameter-in-the-cross-validation-method-and-get-the-final" />
        <published>2022-07-26T06:02:37Z</published>
        <updated>2022-07-26T06:02:37Z</updated>
        <summary type="html">
            &lt;p&gt;As I learned about &lt;strong&gt;cross-validation&lt;/strong&gt; algorithm, from most of the articles on the web, there are variety of &lt;strong&gt;cross-validation&lt;/strong&gt; methods. Here I want to be clear about the &lt;em&gt;&lt;strong&gt;k-fold cross-validation&lt;/strong&gt;&lt;/em&gt; technique.&lt;/p&gt;&#xA;&lt;p&gt;In the &lt;em&gt;&lt;strong&gt;k-fold cross-validation&lt;/strong&gt;&lt;/em&gt; algorithm, we can split the training set in to &lt;em&gt;k&lt;/em&gt; not-overlapped folds.&lt;/p&gt;&#xA;&lt;p&gt;As we split the training data in to &lt;em&gt;k&lt;/em&gt; folds, we have to train the model in &lt;em&gt;k&lt;/em&gt; &lt;strong&gt;iterations&lt;/strong&gt;.&lt;/p&gt;&#xA;&lt;p&gt;So, in each iteration, we &lt;strong&gt;train&lt;/strong&gt; the model with &lt;strong&gt;(k-1) folds&lt;/strong&gt; and &lt;em&gt;&lt;strong&gt;validate&lt;/strong&gt;&lt;/em&gt; it with the &lt;em&gt;&lt;strong&gt;remained fold&lt;/strong&gt;&lt;/em&gt;.&lt;/p&gt;&#xA;&lt;p&gt;In each split we can calculate the desired metric(s) of our model.&lt;/p&gt;&#xA;&lt;p&gt;At the end we can report the &lt;strong&gt;training error&lt;/strong&gt; by taking the average of scores of all iterations.&#xA;But what is the &lt;strong&gt;final trained model&lt;/strong&gt;?&lt;/p&gt;&#xA;&lt;p&gt;Some points in those articles are not clear for me?&lt;/p&gt;&#xA;&lt;ol&gt;&#xA;&lt;li&gt;&lt;p&gt;Should I &lt;strong&gt;initiate model&#x27;s parameters in each iteration&lt;/strong&gt;?&#xA;I ask this, because if I don&#x2019;t initialize the parameter&#x27;s it could save the pattern of data which I want to be unseen in the next iteration and so on&#x2026;&lt;/p&gt;&#xA;&lt;/li&gt;&#xA;&lt;li&gt;&lt;p&gt;Should I save the &lt;strong&gt;initial parameter of the split in which I gained the best score&lt;/strong&gt;, as the best initial values of the parameters?&lt;/p&gt;&#xA;&lt;/li&gt;&#xA;&lt;li&gt;&lt;p&gt;Should I retrain the model initiating it with the initial values of the parameters gained in my second question and then feed it with whole training dataset and gain the &lt;strong&gt;final trained model&lt;/strong&gt;?&lt;/p&gt;&#xA;&lt;/li&gt;&#xA;&lt;/ol&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/604266</id>
        <re:rank scheme="https://stackoverflow.com">290</re:rank>
        <title type="text">Django set default form values</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="django" />
            <category scheme="https://stackoverflow.com/tags" term="django-models" />
            <category scheme="https://stackoverflow.com/tags" term="django-forms" />
        <author>
            <name>Mike</name>
            <uri>https://stackoverflow.com/users/72987</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/604266/django-set-default-form-values" />
        <published>2009-03-02T22:18:18Z</published>
        <updated>2022-07-26T06:01:01Z</updated>
        <summary type="html">
            &lt;p&gt;I have a Model as follows:&lt;/p&gt;&#xA;&#xA;&lt;pre&gt;&lt;code&gt;class TankJournal(models.Model):&#xA;    user = models.ForeignKey(User)&#xA;    tank = models.ForeignKey(TankProfile)&#xA;    ts = models.IntegerField(max_length=15)&#xA;    title = models.CharField(max_length=50)&#xA;    body = models.TextField()&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&#xA;&lt;p&gt;I also have a model form for the above model as follows:&lt;/p&gt;&#xA;&#xA;&lt;pre&gt;&lt;code&gt;class JournalForm(ModelForm):&#xA;    tank = forms.IntegerField(widget=forms.HiddenInput()) &#xA;&#xA;    class Meta:&#xA;        model = TankJournal&#xA;        exclude = (&#x27;user&#x27;,&#x27;ts&#x27;)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&#xA;&lt;p&gt;I want to know how to set the default value for that tank hidden field. Here is my function to show/save the form so far:&lt;/p&gt;&#xA;&#xA;&lt;pre&gt;&lt;code&gt;def addJournal(request, id=0):&#xA;    if not request.user.is_authenticated():&#xA;        return HttpResponseRedirect(&#x27;/&#x27;)&#xA;&#xA;    # checking if they own the tank&#xA;    from django.contrib.auth.models import User&#xA;    user = User.objects.get(pk=request.session[&#x27;id&#x27;])&#xA;&#xA;    if request.method == &#x27;POST&#x27;:&#xA;        form = JournalForm(request.POST)&#xA;        if form.is_valid():&#xA;            obj = form.save(commit=False)&#xA;&#xA;            # setting the user and ts&#xA;            from time import time&#xA;            obj.ts = int(time())&#xA;            obj.user = user&#xA;&#xA;            obj.tank = TankProfile.objects.get(pk=form.cleaned_data[&#x27;tank_id&#x27;])&#xA;&#xA;            # saving the test&#xA;            obj.save()&#xA;&#xA;    else:&#xA;        form = JournalForm()&#xA;&#xA;    try:&#xA;        tank = TankProfile.objects.get(user=user, id=id)&#xA;    except TankProfile.DoesNotExist:&#xA;        return HttpResponseRedirect(&#x27;/error/&#x27;)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/72277084</id>
        <re:rank scheme="https://stackoverflow.com">2</re:rank>
        <title type="text">what is label_gain in LightGBM ranker?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="machine-learning" />
            <category scheme="https://stackoverflow.com/tags" term="lightgbm" />
        <author>
            <name>Wobble bruh</name>
            <uri>https://stackoverflow.com/users/19101939</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/72277084/what-is-label-gain-in-lightgbm-ranker" />
        <published>2022-05-17T15:48:49Z</published>
        <updated>2022-07-26T05:59:25Z</updated>
        <summary type="html">
            &lt;p&gt;I basically want to know what that parameter is and what kind of input it takes. I want to understand how to use it in different cases.&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118326</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">python/requests_html , html.render() failed</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="python-requests-html" />
        <author>
            <name>anderwyang</name>
            <uri>https://stackoverflow.com/users/13710421</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118326/python-requests-html-html-render-failed" />
        <published>2022-07-26T05:59:07Z</published>
        <updated>2022-07-26T05:59:07Z</updated>
        <summary type="html">
            &lt;p&gt;In below python/requests_html , &lt;code&gt;r.html.xpath(&amp;quot;//ul/li[3]/span/span[2]&amp;quot;)&lt;/code&gt; return &lt;code&gt;[]&lt;/code&gt; (wish to return  &lt;code&gt;Ender 3&lt;/code&gt;)&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;from requests_html import HTMLSession&#xA;with HTMLSession() as session:&#xA;    r = session.get(&#x27;https://www.amazon.com/dp/B07BR3F9N6&#x27;)&#xA;r.html.xpath(&amp;quot;//ul/li[3]/span/span[2]&amp;quot;)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I add &lt;code&gt;r.html.render()&lt;/code&gt; ,want to render the web ,bu the it return error &lt;code&gt;RuntimeError: Cannot use HTMLSession within an existing event loop. Use AsyncHTMLSession instead.&lt;/code&gt;&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;from requests_html import HTMLSession&#xA;    with HTMLSession() as session:&#xA;        r = session.get(&#x27;https://www.amazon.com/dp/B07BR3F9N6&#x27;)&#xA;        r.html.render()&#xA;    r.html.xpath(&amp;quot;//ul/li[3]/span/span[2]&amp;quot;)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Anyone can help ? Thanks!&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73077054</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">get idxmax rolling for each group and each row?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="pandas" />
            <category scheme="https://stackoverflow.com/tags" term="numpy" />
        <author>
            <name>Jack</name>
            <uri>https://stackoverflow.com/users/5576930</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73077054/get-idxmax-rolling-for-each-group-and-each-row" />
        <published>2022-07-22T08:04:30Z</published>
        <updated>2022-07-26T05:58:08Z</updated>
        <summary type="html">
            &lt;p&gt;data: &lt;a href=&quot;https://github.com/zero-jack/data/blob/main/hy_data.csv#L7&quot; rel=&quot;nofollow noreferrer&quot;&gt;https://github.com/zero-jack/data/blob/main/hy_data.csv#L7&lt;/a&gt;&lt;/p&gt;&#xA;&lt;h1&gt;Goal&lt;/h1&gt;&#xA;&lt;ul&gt;&#xA;&lt;li&gt;get the idxmax from last n rows for each group.&lt;/li&gt;&#xA;&lt;/ul&gt;&#xA;&lt;h1&gt;Try&lt;/h1&gt;&#xA;&lt;pre&gt;&lt;code&gt;df=df.assign(&#xA;        l6d_highest_date=lambda x: x.groupby(&#x27;hy_code&#x27;)[&#x27;high&#x27;].transform(lambda x: x.rolling(6).idxmax())&#xA;&#xA;&#xA;AttributeError: &#x27;Rolling&#x27; object has no attribute &#x27;idxmax&#x27;&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;notice: &lt;code&gt;week_date&lt;/code&gt; is the index.&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73107908</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">how to generate company logo image mask using OpenCV?</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="numpy" />
            <category scheme="https://stackoverflow.com/tags" term="opencv" />
        <author>
            <name>Parth Soni</name>
            <uri>https://stackoverflow.com/users/18800214</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73107908/how-to-generate-company-logo-image-mask-using-opencv" />
        <published>2022-07-25T10:43:46Z</published>
        <updated>2022-07-26T05:58:07Z</updated>
        <summary type="html">
            &lt;p&gt;I am working on removing the company logo background image mask but I&#x27;m not getting the exact output. I try many ways to remove the company logo background but every model is trained in human categories just like model name mode net, u2net, etc. I plan to train the custom model so I need an image and mask I&#x27;m generating an image mask but not getting exact output here is my code.&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;import numpy as np &#xA;&#xA;# Reading image&#xA;image = cv2.imread(&#x27;image_path&#x27;)&#xA;gray = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)&#xA;&#xA;# Find Canny edges&#xA;edged = cv2.Canny(gray, 30, 200)&#xA;cv2.waitKey(0)&#xA;&#xA;# creating canvas&#xA;canvas = np.zeros(image.shape, np.uint8)&#xA;canvas.fill(255)&#xA;&#xA;#creating image background mask&#xA;mask = np.ones(image.shape, dtype=np.uint8) * 255&#xA;&#xA;contours, hierarchy = cv2.findContours(edged,&#xA;   cv2.RETR_EXTERNAL, cv2.CHAIN_APPROX_NONE)&#xA;&#xA;cnts = contours[0]&#xA;for c in cnts:&#xA;    x,y,w,h = cv2.boundingRect(c)&#xA;&#xA;    ROI = image[y:y&#x2B;h, x:x&#x2B;w]&#xA;&#xA;#finding controus&#xA;contours_mask, hierarchy = cv2.findContours(edged, cv2.RETR_EXTERNAL, cv2.CHAIN_APPROX_NONE)&#xA;&#xA;for contour in range(len(contours_mask)):&#xA;   cv2.fillConvexPoly(mask, contours_mask[contour], (0,0,255))&#xA;&#xA;# fill color in background image&#xA;cv2.floodFill(mask, None, seedPoint=(0, 0), newVal=128, loDiff=1, upDiff=1)&#xA;&#xA;r=cv2.selectROI(&#x27;ROI&#x27;, edged,False,False)&#xA;imROI = edged[int(r[1]):int(r[1]&#x2B;r[3]), int(r[0]):int(r[0]&#x2B;r[2])]&#xA;&#xA;cv2.imshow(&#x27;Canny Edges After Contouring&#x27;, ROI)&#xA;cv2.waitKey(0)&#xA;&#xA;print(&amp;quot;Number of Contours found = &amp;quot; &#x2B; str(len(contours)))&#xA;&#xA;# Draw all contours&#xA;# -1 signifies drawing all contours&#xA;cv2.drawContours(image, contours, -1, (0, 255, 0), 3)&#xA;&#xA;cv2.imshow(&#x27;Contours&#x27;, image)&#xA;cv2.imshow(&#x27;background mask&#x27;, mask)&#xA;cv2.imshow(&#x27;canvas&#x27;, canvas)&#xA;cv2.waitKey(0)&#xA;cv2.destroyAllWindows()```&#xA;&#xA;**&amp;gt;I am getting that kind of output in background mask image output.**&#xA;[enter image description here][1]&#xA;&#xA;&#xA;[enter image description here][2]&#xA;&#xA;&#xA;  [1]: https://i.stack.imgur.com/6B5Mx.png&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73117515</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">The random function does not start correctly. If I click on the button the text doesn&#x27;t change, but if I close and reopen the app it changes</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="python-3.x" />
            <category scheme="https://stackoverflow.com/tags" term="string" />
            <category scheme="https://stackoverflow.com/tags" term="tkinter" />
            <category scheme="https://stackoverflow.com/tags" term="random" />
        <author>
            <name>Jas_99</name>
            <uri>https://stackoverflow.com/users/18313765</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73117515/the-random-function-does-not-start-correctly-if-i-click-on-the-button-the-text" />
        <published>2022-07-26T03:44:29Z</published>
        <updated>2022-07-26T05:57:38Z</updated>
        <summary type="html">
            &lt;p&gt;This script has the purpose of displaying the word &amp;quot;della gara&amp;quot; or &amp;quot;del match&amp;quot; in combination with &amp;quot;valida&amp;quot; or &amp;quot;valido, depending on the grammar rule if male or female. Don&#x27;t worry, it works correctly :) Don&#x27;t worry, even if the text is in a non-English language, it doesn&#x27;t matter, because it prints quietly. All that is needed is to apply the random function with &lt;code&gt;sinonimo_partita_random&lt;/code&gt; inside the for loop.&lt;/p&gt;&#xA;&lt;p&gt;&lt;strong&gt;PROBLEM&lt;/strong&gt;: The problem is that the random function doesn&#x27;t start correctly when I click the Print button. Try clicking on the Print button many times, nothing happens.&lt;/p&gt;&#xA;&lt;p&gt;I would like to display &lt;code&gt;sinonimo_partita_random&lt;/code&gt;, but if I click it is always printed &amp;quot;della gara&amp;quot; or always &amp;quot;del match&amp;quot;. While, if I close and reopen the script, the word is changed.&lt;/p&gt;&#xA;&lt;p&gt;How can I make the random function fully functional when I click the Print button?&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;import random&#xA;from tkinter import ttk&#xA;import tkinter as tk&#xA;from tkinter import *&#xA;&#xA;root = tk.Tk()&#xA;root.geometry(&amp;quot;400x150&amp;quot;)&#xA;                      &#xA;sinonimi_partita_diz = {&#xA;&#xA;        &amp;quot;della gara&amp;quot;: {&amp;quot;genere&amp;quot; : &amp;quot;femminile&amp;quot;, &amp;quot;unit&#xE0;&amp;quot; : &amp;quot;singolare&amp;quot;, &amp;quot;apostrofo&amp;quot; : &amp;quot;no&amp;quot;},&#xA;        &amp;quot;del match&amp;quot;: {&amp;quot;genere&amp;quot; : &amp;quot;maschile&amp;quot;, &amp;quot;unit&#xE0;&amp;quot; : &amp;quot;singolare&amp;quot;, &amp;quot;apostrofo&amp;quot; : &amp;quot;no&amp;quot;},&#xA;        }&#xA;&#xA;valido_a_diz = {&#xA;    &#xA;            &amp;quot;valido&amp;quot; : {&#xA;            &amp;quot;genere&amp;quot; : &amp;quot;maschile&amp;quot;,&#xA;            &amp;quot;unit&#xE0;&amp;quot; : &amp;quot;singolare&amp;quot;,&#xA;            &amp;quot;apostrofo&amp;quot; : &amp;quot;no&amp;quot;&#xA;            },        &#xA;&#xA;            &amp;quot;valida&amp;quot; : {&#xA;            &amp;quot;genere&amp;quot; : &amp;quot;femminile&amp;quot;,&#xA;            &amp;quot;unit&#xE0;&amp;quot; : &amp;quot;singolare&amp;quot;,&#xA;            &amp;quot;apostrofo&amp;quot; : &amp;quot;no&amp;quot;&#xA;            },                &#xA;        }&#xA;&#xA;####################&#xA;&#xA;text = tk.Text(root,width=43,height=2)&#xA;text.place(x=15, y=50)&#xA;&#xA;#THE PROBLEM IS HERE:&#xA;sinonimo_partita = (&amp;quot;della gara&amp;quot;, &amp;quot;del match&amp;quot;)&#xA;sinonimo_partita_random = random.choice(sinonimo_partita)&#xA;&#xA;valido_a = &amp;quot;&amp;quot;&#xA;for key, value in valido_a_diz.items():&#xA;    if sinonimi_partita_diz[sinonimo_partita_random] == value:&#xA;        valido_a = key&#xA;        break&#xA;&#xA;def print():&#xA;    text.delete(1.0,END)&#xA;    phrase = f&amp;quot;{sinonimo_partita_random} {valido_a}&amp;quot;&#xA;    text.insert(tk.END, phrase)&#xA;&#xA;button2 = Button(root, text=&amp;quot;Print&amp;quot;, command = print)&#xA;button2.pack()&#xA;button2.place(x=15, y=100)&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118311</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">No form of window into EXE</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="printing" />
            <category scheme="https://stackoverflow.com/tags" term="exe" />
        <author>
            <name>Tristan Moran</name>
            <uri>https://stackoverflow.com/users/19519798</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118311/no-form-of-window-into-exe" />
        <published>2022-07-26T05:56:57Z</published>
        <updated>2022-07-26T05:56:57Z</updated>
        <summary type="html">
            &lt;p&gt;So I&#x27;m making a python game with no form of a window popping up, only commands like&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;print(&amp;quot;Welcome to Game!!!&amp;quot;)    &#xA;name = input(&amp;quot;Whats your name???&amp;quot;)    &#xA;print(&amp;quot;Hello, &amp;quot; &#x2B; name)    &#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;and such. and I wonder, if I turn this into a home, well it open a terminal or shell or something, so I&#x27;m asking anyone who has done this before and if I&#x27;m wasting my time.&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118307</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">SQLAlchemy Attribute Error Using Chinook db</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="sql" />
            <category scheme="https://stackoverflow.com/tags" term="database" />
            <category scheme="https://stackoverflow.com/tags" term="sqlalchemy" />
            <category scheme="https://stackoverflow.com/tags" term="crud" />
        <author>
            <name>TrevTheDev</name>
            <uri>https://stackoverflow.com/users/17892505</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118307/sqlalchemy-attribute-error-using-chinook-db" />
        <published>2022-07-26T05:56:32Z</published>
        <updated>2022-07-26T05:56:32Z</updated>
        <summary type="html">
            &lt;p&gt;I am experimenting with SQLAlchemy for the very first time, I followed a tutorial previously then to embed the knowledge I wanted to create my own Table, I have produced the following code:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;# Structure to start db&#xA;from sqlalchemy import (&#xA;    create_engine,&#xA;    Column,&#xA;    Integer,&#xA;    String&#xA;)&#xA;from sqlalchemy.ext.declarative import declarative_base&#xA;from sqlalchemy.orm import sessionmaker&#xA;&#xA;&#xA;# executing the instructions from the &amp;quot;chinook&amp;quot; database&#xA;db = create_engine(&amp;quot;postgresql:///chinook&amp;quot;)&#xA;base = declarative_base()&#xA;&#xA;&#xA;# - A table for **your favorite places&#xA;# (country name, capital city, population, etc.)&#xA;class Favorite_Places(base):&#xA;    __tablename__ = &amp;quot;Favorite Places&amp;quot;&#xA;    id = Column(Integer, primary_key=True)&#xA;    country_name = Column(String)&#xA;    capital_city = Column(String)&#xA;    population = Column(Integer)&#xA;&#xA;&#xA;# instead of connecting to the database directly, we will ask for a session&#xA;# create a new instance of sessionmaker, then point to our engine (the db)&#xA;Session = sessionmaker(db)&#xA;# opens an actual session by calling the Session() subclass defined above&#xA;session = Session()&#xA;&#xA;&#xA;# creating the database using declarative_base subclass&#xA;base.metadata.create_all(db)&#xA;&#xA;# Creating records on our db&#xA;colombia = Favorite_Places(&#xA;    country_name=&amp;quot;Colombia&amp;quot;,&#xA;    capital_city=&amp;quot;Bogota&amp;quot;,&#xA;    population=7181000&#xA;)&#xA;&#xA;# Add each instance of our favorite places to our session&#xA;session.add(colombia)&#xA;&#xA;# commit our session to the database&#xA;session.commit()&#xA;&#xA;# Query the db to find all the programmers&#xA;favorite_places = session.query(Favorite_Places)&#xA;for places in favorite_places:&#xA;    print(&#xA;        favorite_places.id,&#xA;        favorite_places.country_name,&#xA;        favorite_places.capital_city,&#xA;        favorite_places.population,&#xA;        sep=&amp;quot; | &amp;quot;&#xA;    )&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;I am currently using the Chinook db, I have my terminal split into two so I can run the db on one and cross-reference it with my python file as seen below:&lt;/p&gt;&#xA;&lt;p&gt;&lt;a href=&quot;https://i.stack.imgur.com/rd4lR.jpg&quot; rel=&quot;nofollow noreferrer&quot;&gt;&lt;img src=&quot;https://i.stack.imgur.com/rd4lR.jpg&quot; alt=&quot;Split Terminal&quot; /&gt;&lt;/a&gt;&lt;/p&gt;&#xA;&lt;p&gt;As you can see on the db, the Table appears but I cant save any data to it, when I run the .py file on the right terminal I get an attribute error, saying that my Query is not defined, on the tutorial there were no issues like this, Could someone just help me to understand why this is the case? Been at it since yesterday afternoon&lt;/p&gt;&#xA;&lt;p&gt;Thanks in advance&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73106025</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">could not open port &#x27;COM3&#x27;: Permission Error(13, &#x27;Access is denied.&#x27;, None, 5)</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="arduino" />
            <category scheme="https://stackoverflow.com/tags" term="permissionerror" />
        <author>
            <name>TomYum</name>
            <uri>https://stackoverflow.com/users/19615805</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73106025/could-not-open-port-com3-permission-error13-access-is-denied-none-5" />
        <published>2022-07-25T08:19:59Z</published>
        <updated>2022-07-26T05:56:09Z</updated>
        <summary type="html">
            &lt;p&gt;I wanted to make a code which recognizes if I pressed the left or the right button using Pygame, and then sending that information to Arduino and either turning on or off a light. I am using Visual Studio Code for python. Since I am using python with Arduino, this requires both programs to be open at the same time. I tried browsing and looking for other people doing the same thing and having the same problem, and tried using their solutions but nothing worked for me. I tried:&lt;/p&gt;&#xA;&lt;ul&gt;&#xA;&lt;li&gt;using &lt;code&gt;ser.close()&lt;/code&gt;, and the program said it was a mistake&lt;/li&gt;&#xA;&lt;li&gt;closing the serial monitor, which has always been closed&lt;/li&gt;&#xA;&lt;li&gt;checking if I was using the correct port, I was&lt;/li&gt;&#xA;&lt;li&gt;unplugging and plugging back in&lt;/li&gt;&#xA;&lt;li&gt;running VSC as administrator.&lt;/li&gt;&#xA;&lt;/ul&gt;&#xA;&lt;p&gt;Here is my python code. The error occurs in line 9:&lt;/p&gt;&#xA;&lt;p&gt;&lt;img src=&quot;https://i.stack.imgur.com/TsKjp.png&quot; alt=&quot;here is my python code. The error occurs in line 9&quot; /&gt;&lt;/p&gt;&#xA;&lt;p&gt;Here is my Arduino code.&lt;/p&gt;&#xA;&lt;p&gt;&lt;img src=&quot;https://i.stack.imgur.com/YDElN.png&quot; alt=&quot;here is my Arduino code.&quot; /&gt;&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118057</id>
        <re:rank scheme="https://stackoverflow.com">0</re:rank>
        <title type="text">How find records with specific date using Python and MySQL</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="mysql" />
        <author>
            <name>Siciid</name>
            <uri>https://stackoverflow.com/users/19179518</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118057/how-find-records-with-specific-date-using-python-and-mysql" />
        <published>2022-07-26T05:21:00Z</published>
        <updated>2022-07-26T05:55:25Z</updated>
        <summary type="html">
            &lt;p&gt;I have created small project about students registration. I am using Python and MySQL. I want to how find students registered with specific date. I have tried and created the following codes:&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;import tkinter as tk&#xA;from tkinter import ttk&#xA;from tkcalendar import DateEntry &#xA;import mysql.connector&#xA;&#xA;my_w = tk.Tk()&#xA;my_w.geometry(&amp;quot;900x650&amp;quot;)  # Size of the window &#xA;my_w.title(&amp;quot;Tutorial&amp;quot;)  # Adding a title&#xA;sel=tk.StringVar()&#xA;cal=DateEntry(my_w,selectmode=&#x27;day&#x27;,textvariable=sel)&#xA;cal.grid(row=0,column=0,padx=20,pady=30)&#xA;def my_upd(*args): # triggered when value of string varaible changes&#xA;    if(len(sel.get())&amp;gt;4):&#xA;        dt=cal.get_date() # get selected date object from calendar&#xA;        dt1=dt.strftime(&amp;quot;%Y-%m-%d&amp;quot;) #format for MySQL date column &#xA;        dt2=dt.strftime(&amp;quot;%d-%B-%Y&amp;quot;) #format to display at label &#xA;        l1.config(text=dt2) # display date at Label&#xA;        con =mysql.connector.connect(host=&amp;quot;localhost&amp;quot;,database=&#x27;tutorial&#x27;,user=&amp;quot;root&amp;quot;,password=&amp;quot;&amp;quot;)&#xA;        cur=con.cursor()&#xA;        query=&amp;quot;SELECT * from students WHERE regisdate=%s&amp;quot;&#xA;        r_set=cur.execute(query,dt1) # execute query with data&#xA;        for item in trv.get_children(): # delete all previous listings&#xA;            trv.delete(item)&#xA;        total=0 # to store total sale of the selected date&#xA;        for dt in r_set: &#xA;            trv.insert(&amp;quot;&amp;quot;, &#x27;end&#x27;,iid=dt[0], text=dt[0],&#xA;               values =(dt[0],dt[1],dt[2],dt[3]))&#xA;            total=round(total&#x2B;(dt[2]*dt[3]),2)&#xA;        l2.config(text=&amp;quot;Total: &amp;quot; &#x2B; str(total)) # show total value&#xA;l1=tk.Label(my_w,font=(&#x27;Times&#x27;,22,&#x27;bold&#x27;),fg=&#x27;blue&#x27;)&#xA;l1.grid(row=0,column=1)&#xA;trv = ttk.Treeview(my_w, selectmode =&#x27;browse&#x27;)&#xA;  &#xA;trv.grid(row=1,column=1,padx=20,pady=20)&#xA;# number of columns&#xA;trv[&amp;quot;columns&amp;quot;] = (&amp;quot;0&amp;quot;, &amp;quot;1&amp;quot;, &amp;quot;2&amp;quot;,&amp;quot;3&amp;quot;)&#xA;trv[&#x27;height&#x27;]  =20&#xA;# Defining heading&#xA;trv[&#x27;show&#x27;] = &#x27;headings&#x27;&#xA;  &#xA;# width of columns and alignment &#xA;trv.column(&amp;quot;0&amp;quot;, width = 30, anchor =&#x27;c&#x27;)&#xA;trv.column(&amp;quot;1&amp;quot;, width = 80, anchor =&#x27;c&#x27;)&#xA;trv.column(&amp;quot;2&amp;quot;, width = 80, anchor =&#x27;c&#x27;)&#xA;trv.column(&amp;quot;3&amp;quot;, width = 80, anchor =&#x27;c&#x27;)&#xA;&#xA;  &#xA;# Headings  &#xA;# respective columns&#xA;trv.heading(&amp;quot;0&amp;quot;, text =&amp;quot;ID&amp;quot;)&#xA;trv.heading(&amp;quot;1&amp;quot;, text =&amp;quot;Name&amp;quot;)&#xA;trv.heading(&amp;quot;2&amp;quot;, text =&amp;quot;Contact&amp;quot;)&#xA;trv.heading(&amp;quot;3&amp;quot;, text =&amp;quot;RegisDate&amp;quot;)  &#xA;&#xA;sel.trace(&#x27;w&#x27;,my_upd)&#xA;&#xA;l2=tk.Label(my_w,font=(&#x27;Times&#x27;,22,&#x27;bold&#x27;),fg=&#x27;red&#x27;)&#xA;l2.grid(row=1,column=2,sticky=&#x27;ne&#x27;,pady=20)&#xA;&#xA;my_w.mainloop()  # Keep the window open&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;When i run the above code, it raises this error:&lt;/p&gt;&#xA;&lt;p&gt;Exception in Tkinter callback&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;Traceback (most recent call last):&#xA;  File &amp;quot;C:\Users\Siciid\AppData\Local\Programs\Python\Python310\lib\tkinter\__init__.py&amp;quot;, line 1921, in __call__&#xA;    return self.func(*args)&#xA;  File &amp;quot;c:\Users\Siciid\Desktop\Tutorial\datewise.py&amp;quot;, line 22, in my_upd&#xA;    r_set=cur.execute(query,dt1) # execute query with data&#xA;  File &amp;quot;C:\Users\Siciid\AppData\Local\Programs\Python\Python310\lib\site-packages\mysql\connector\cursor_cext.py&amp;quot;, line 257, in execute&#xA;    prepared = self._cnx.prepare_for_mysql(params)&#xA;  File &amp;quot;C:\Users\Siciid\AppData\Local\Programs\Python\Python310\lib\site-packages\mysql\connector\connection_cext.py&amp;quot;, line 686, in prepare_for_mysql&#xA;    raise errors.ProgrammingError(&#xA;mysql.connector.errors.ProgrammingError: Could not process parameters: str(2022-07-25), it must be of type list, tuple or dict&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;Please i need your help.&lt;/p&gt;&#xA;
        </summary>
    </entry>
    <entry>
        <id>https://stackoverflow.com/q/73118144</id>
        <re:rank scheme="https://stackoverflow.com">-2</re:rank>
        <title type="text">How to create a dictionary to append file name as key and data as value</title>
            <category scheme="https://stackoverflow.com/tags" term="python" />
            <category scheme="https://stackoverflow.com/tags" term="list" />
            <category scheme="https://stackoverflow.com/tags" term="dictionary" />
            <category scheme="https://stackoverflow.com/tags" term="yaml" />
            <category scheme="https://stackoverflow.com/tags" term="key" />
        <author>
            <name>Anu Shivangi</name>
            <uri>https://stackoverflow.com/users/16560784</uri>
        </author>
        <link rel="alternate" href="https://stackoverflow.com/questions/73118144/how-to-create-a-dictionary-to-append-file-name-as-key-and-data-as-value" />
        <published>2022-07-26T05:34:08Z</published>
        <updated>2022-07-26T05:52:12Z</updated>
        <summary type="html">
            &lt;p&gt;I am trying to create a python dictionary from Yaml file, some yaml files are of list type and some are dict type. I want to create Dictionary to finally create a json  where I want structure as {&amp;quot;file_name_1&amp;quot;:{},&amp;quot;file_name_2&amp;quot;:[{},{}]}&#xA;I&#x27;m trying with below code to append but getting error :&lt;/p&gt;&#xA;&lt;pre&gt;&lt;code&gt;json_dict = {}&#xA;file_name = &#x27;abc.yaml&#x27;&#xA;with open(files) as file:&#xA;yaml_data = yaml.safe_load(file)&#xA;json_dict[file_name].append(yaml_data)&#xA;&#xA;Error : KeyError: &#x27;abc.yaml&#x27;&#xA;&lt;/code&gt;&lt;/pre&gt;&#xA;&lt;p&gt;can someone please help me what I am doing wrong here. file_name and data will be appended in loop for multiple files.&lt;/p&gt;&#xA;
        </summary>
    </entry>
</feed>
- A passionate team player who has gained domain knowledge and experience on backend development and am willing to apply them in challenging tech-projects.
- 🎤 Software Engineer - Sysco LABS
- 💬 Actively writing blogs [Check it Out!](https://medium.com/@rcvaram)
- 📬 How to reach me: <a href="mailto:cvaram96@gmail.com">Let's get in touch!</a>



## ✏️ Recent Blog

- <a href='https://codeburst.io/edge-detection-depth-analysis-669d5adcbae6' target='_blank'>Edge Detection Depth Analysis</a> 
- <a href='https://medium.com/%E0%AE%A4%E0%AE%B4%E0%AE%B2%E0%AE%BF/documenting-spring-boot-api-using-swagger2-14926e8e20a4' target='_blank'> Swagger2 for Spring boot API</a>
- <a href='https://medium.com/%E0%AE%A4%E0%AE%B4%E0%AE%B2%E0%AE%BF/what-how-in-spring-boot-authentication-52ecd1514b2c' target='_blank'>Spring boot Authentication</a>
- <a href='https://medium.com/analytics-vidhya/creating-own-network-scanner-using-python-f11a50a5ff77' target='_blank'>Netwrok Scanner</a> 


<a href="https://stackexchange.com/users/15591403/rcvaram"><img src="https://stackexchange.com/users/flair/15591403.png" width="208" height="58" alt="profile for rcvaram on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for rcvaram on Stack Exchange, a network of free, community-driven Q&amp;A sites" /></a>



 [![Sivaram Rasathurai's github stats](https://github-readme-stats.vercel.app/api?username=rcvaram&count_private=true&show_icons=true&theme=dracula)](https://github.com/rcvaram/github-readme-stats)
 
 
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rcvaram&layout=compact&count_private=true&show_icons=true&theme=dracula)](https://github.com/rcvaram/github-readme-stats)


Happy coding !!!
### Connect with me
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/sivaramrasathurai/)
[![Twitter Badge](https://img.shields.io/twitter/follow/rcvaram?style=social)](https://twitter.com/rcvaram)
[![GitHub Badge](https://img.shields.io/github/followers/rcvaram?label=Follow%20%40rcvaram&style=social)](https://github.com/rcvaram)


<!--- 
Profile Inspiration -
https://github.com/christina-ml/christina-ml/blob/main/README.md
https://dev.to/diogorodrigues/creating-amazing-github-profiles-readme-5h31

Make buttons - https://shields.io/
Custom Logos - https://simpleicons.org/
-->

