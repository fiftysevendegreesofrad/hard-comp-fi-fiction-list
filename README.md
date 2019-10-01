# hard-comp-fi-fiction-list 

The deployed list lives at https://fiftysevendegreesofrad.github.io/hard-comp-fi-fiction-list/

To update: add new books and/or new reviews of books already listed, to [data.json](data.json), then send a pull request. 

* Fields attached to the book:

  * title: actually **title (author)**. Hyperlink from the title if and only if it's to a legal free download. Don't forget to escape double quotes, like this: `<a href=\"http://...\">`

  * length. Short, Medium or Long only please.
  
* Fields attached to your review (scores are averaged per book and reviews appended):

  * reviewer (optional): whatever name you want to attribute your review to
  
  * csprop: CompFi proportion. How much of the manuscript is dedicated to computing concepts? This is descriptive not normative: more is not necessarily better, and less might mean more time for e.g. character development. Score out of 5.
  
  * cscent: CompFi centrality. How central are computing concepts to the narrative? The entire story may hinge on a CS concept even if it receives few words. Score out of 5.

  * overallscore: Rating out of 5 for quality of work.
  
  * review. You can use HTML. Currently marking any spoilers with `(spoiler) <span style=\"color:white\">spoiler goes here</span>`.
  
