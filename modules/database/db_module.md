--- 
title: Black Code Studies
author: Spring 2017
doc: db_module.md
--- 

# Corrupt the CSV
## Database Module Assignment - DUE APRIL 6, 2017 by 4:15 pm 

**Note--You'll see that I've removed the Black Visual Archive from your assignment so we can spend more time doing visual work next week and in the remaining weeks of the class. For this assignment, focus on the text/number data you have at hand and how to work with that. If you've already begun to think about how to CSV black visual data, you are welcome to incorporate that as extra credit**

The last three class periods (Black Data, The Numbers Game, Black Visual Archives I), we have discussed how scholars have quantified data in slavery's archive. You might be surprised to know you've looked at wide range of sources--slave ship manifests (Eltis and Richardson), mapping data on slave revolts (Brown), sculptures (Kara Walker), prints and silhouettes (Kara Walker), Civil War portraits, Carrie Mae Weems, listservs and slave trade debates, dictionaries and print images of African women (Handler, Morgan), and even Beyoncé. Only some of these express data about slavery in numbers. And yet the constitutent element of the internet are the 101010100s of the digital format. At the same time, the ways and moments when black people have been expressed in numbers--in slave ship manifests, for example--come with their own kind of violence and dehumanization.

Creating a CSV (comma separate values) file is a way to a) explore that base element of the digital, b) practice breaking non-text and text sources into numbers, c) think in a Black Code Studies way (fugitive, insurgent, black, human, undercommoning) about what data does and means in black history and with black people. We essentially are looking at the inner guts and architecture of everything we unthinkingly type, view, and play with on our phones and computers today.

For example, tweets are simply JSON files:
<pre><code>
{"tweet1":
  {
    "user": {"username": "wcaleb", "followers": 205},
    "date_sent":"January 14, 2014",
    "text":"I heart Cheerios.",
    "hashtags": [],
    "coordinates": null,
    "has_image":false
  },
"tweet2":
  { 
    "user": {"username": "wcaleb", "followers": 205},
    "date_sent":"September 1, 2013",
    "text":"Does anyone have any good #json links?",
    "hashtags": ["#json"],
    "coordinates": [-75.14310264, 40.05701649]
  }
}
</pre></code>

And, as your Twitter archivist for your team knows, this is why your tweets appear in CSV format, something like this:

<pre><code>
tweet1,username,wcaleb,followers,date_sent,text,hashtags,coordinates,has_image
1, wcaleb,205,2014-14-01,I heart Cheerios,,null,false
</pre></code>

Having data as a CSV also means we can work forwards into something more complicated--from CSV to Excel spreadsheet to charts and graphs--as we did with Slave Voyages Database.

## THIS IS A TEAM ASSIGNMENT

Your job this week was to corrupt a CSV using the ship manifest of the brig, *Orleans*, the ship that brought Solomon Northrup from Richmond, VA to New Orleans, LA. You will continue this work as follows:

## Step 1

1. Create a CSV that breaks the violence of the document. You began this work on Tuesday. Remember the rules?

<pre><code>
Rules:

1. At least 3 fields
2. At least 5 records as proof; but all records must be able to translate
3. Try using: Boolean, null, array [predetermined series of values, i.e. choice]
4. Values stay the same (ex. you can’t change someone’s name or age)
5. Values can be in text or number format
</pre></code>

Instead of stopping at 5 records, your job is to complete this work and create a CSV for the entire manifest. You may tweak your team's original formula in any way you wish--consider the versions you created in class to be first drafts. Some things to keep in mind:

1. Remember the work we did around Boolean, null, and array variables. You are free to use those as creatively as possible. 
2. Also keep in mind what those variables can and cannot do--i.e., making a field in your CSV Boolean means that the only values possible in that field are "1" or "0" (yes or no). Likewise, making a field an array in your CSV means the only values possible in that field must come from the choices you've provided in your array. 
3. You cannot manipulate the information already given. To repeat the example from class: If your field is "complexion" and you'd like to make it an array, you can give that field as many choices you want, but among those choices must be all of the values listed on the manifest. 
4. Don't forget that there is more information in the document than the list of names--ship name, embarkation and disembarkation points, ship captain, date, etc. You don't have to use these values, but you do have to consider how they fit into your formula.

When your file is complete, name it: team#_corruptcsv_orleans.csv and post it in the database module of the git. You CAN create it as a new file in git; simply use the .csv extension instead of .md. You may also create it elsewhere (TextEdit or TextWrangler) and then drag and drop. 

## Step #2 - Report

In a separate Markdown file, in at least 500 words, decode your team's formula. Explain:

* How does this CSV disrupt/break/corrupt the violence of the slave ship manifest?
* For each field, explain/justify why your team decided this was the best way to corrupt?
* For each use of Boolean, null, and array, explain/justify why your team decided this was the best way to corrupt?
* How did you corrupt each individual record? (i.e. how does your formula disrupt Plat's appearance in the document) 
* How did you corrupt the document as a whole? (i.e. how does your formula disrupt the underlying logic of a slave ship manifest)

## Step #3 - Individual Analysis - **Due by Midnight**

As we haven't done a self/peer evaluation check in for some time, your final step is an individual analysis, emailed to me privately at jmj@jhu.edu:

* How does the CSV your Team created represent/do/enact (verb of your choice) Black Code Studies (this should be the longest answer, at least 750 words and it should include references to texts we have read in class so far)
* What process did your Team use to create the CSV?
* How did you participate in that process?
* What roles and responsibilities did members of the Team have? How were they defined?
* Is there anything else you want to add about the assignment, the final product, or your work with the team?

/fin
