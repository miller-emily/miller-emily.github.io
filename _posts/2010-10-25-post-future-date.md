---
layout: post
title: "Cathedrals as Data and a Step Into Digital Text Analysis"
date: 2020-10-07
categories:
  - Post
last_modified_at: 2017-03-09T12:45:25-05:00
---
The Digital Humanities seed was planted for me, ironically, in a class where we still sometimes used an overhead projector. It was a class on Victorian detective fiction and we were reading Charles Dickens’ The Mystery of Edwin Drood. Among discussion of the ultimate mystery--no one will ever know who killed Edwin Drood because Dickens died--and teasing the British imperial threads out of the Princess Puffer’s journey from her opium den in the East End of London to sleepy rural Cloisterham, Professor Colman said something that I largely forgot about until I began to study digital text analysis. 

He pointed out that Dickens uses the word “monotonous” a lot in the novel, and it would be nice to find a pdf and Command+F search just how many times. I remember looking down at my chunky Penguin edition and thinking how long it would take to manually find all the instances of a single word in all those small-text pages of long, long periodic sentences. You’d never be quite sure you’d found all of them. It was a wall of data.

As a first step into the sandbox of digital text analysis, I recently pasted Project Gutenberg’s edition of Drood into Voyant (http://voyant-tools.org) and found that there are seven uses of “monotonous” in the whole text, and one use of “monotony.” All uses in their context relate to a character’s effort to understand some vast aggregation of Data. What follows is an experiment in using data science to understand novels, and novels to understand data science, using The Mystery of Edwin Drood as my very first corpus.

My approach to Victorian and contemporary novels has always been analogue and recently pivoted into eco-theory. Both the Environmental and the Digital Humanities attempt to comprehend the age of data; the volume of the world. Each uses its literary branch as a scrim on which to project patterns and discussions otherwise disembodied. In a desperate bid to belong to either, I was looking for the overlap of EH and DH when I found Stephanie Posthumus and Stefan Sinclair’s discussion of “reading environments.” Ecocriticism, they write, “brings together the individual, the text and the physical environment” (Posthumus and Sinclair 257). And, “a print book can be considered an interface between the reader and words--it is the point at which components meet and interact…” (Posthumus and Sinclair 259). In this collaborative article, an ecocritic and a digital humanist reconcile what it is to “read” an environment, and how the reader’s “reading environment” colors this. 

They make a case study of reconciliation through an ecocritical analysis of a posthuman novel, using Voyant to scale between distant and close readings of the text. As my chunky Penguin edition was one “reading environment,” Posthumous and Sinclair characterize Voyant as another: one that is, through the simplicity of its interface (which has simplified further since the article’s publication in 2014), “making an argument about the kind of reading environment that is most useful to literary scholars” (Posthumus and Sinclair 263).

It was that analysis that made me decide to open a Victorian novel I’d read on paper in two new “reading environments,” and what I found was that data--large amounts of it in a rapidly changing world--is an invaluable approach to environmental readings of Victorian novels. 

Urban expansion, industrialization, and empire are latent threads in Mystery of Edwin Drood; the plot is moved by other agents. But the motion between Cloisterham as pastoral Englishness and London as urban globalness builds a mounting tension about Cloisterham as it always has been, and Cloisterham as it may end up being. Curiously, the word “monotonous” appears only in descriptions of Cloisterham, London, or description of Jasper and Mr. Sapsea’s lives therein. 

But the use of “monotonous” does not imbue its descriptions with a feeling of monotonousness. Rather, around it hangs an anxiety, an excess of information, change, stimulus--I suggest that “monotonous” encapsulates the feeling experienced when one encounters a wall of data, aggregated into something too vast to be felt and processed simply by observing. The resultant blur can be perceived only in monotone. The closest uses in the text appear within the same passage, an aggregation of the sensory data in Cloisterham’s cathedral: 

> Old Time heaved a mouldy sigh from tomb and arch and vault; and gloomy shadows began to deepen in corners; and damps began to rise from green patches of stone; and jewels, cast upon the pavement of the nave from stained glass by the declining sun, began to perish.  Within the grill-gate of the chancel, up the steps surmounted loomingly by the fast-darkening organ, white robes could be dimly seen, and one feeble voice, rising and falling in a cracked, monotonous mutter, could at intervals be faintly heard  (Dickens chapter 9, emphasis mine).

The periodic sentences mount on each other, and the passage is bookended in vast forces of nature (“Old Time” and “the sea fell”). The detail jumps between the five senses, lingering on one only long enough to begin to establish a pattern before jumping to another: we begin with smell (“mouldy sigh”) but follow it directly into sight (the arches and shadows), touch as “damps began to rise.” We arrive at sound (“feeble voice”). This one voice in such a vast space becomes “monotonous,” environment-as-data pressing in upon the lone human. The senses blur into each other, both creating and obscuring pattern. The white robes “[can] be dimly seen,” but against the organ and the voice and the rising damps I synesthetically read the rustle of fabric. Data both forms and flattens place.

There is more to be read in this vein, examining contemporary novels of the Anthropocene distantly and closely in order to tease pattern from monotony. Both eras are characterized by the sudden and rapid circulation of technology and data, and their novels portray that change as they process it. A comparative reading of Victorian and contemporary novels might insert itself into the ongoing discourse of the Anthropocene, exploring the ways in which we (whether through novels or data science) confront problems of scale in ages of data and climate change.

				
Bibliography: 	


Dickens, Charles. The Mystery of Edwin Drood. Chapman and Hall, 1914. Project Gutenberg. http://www.gutenberg.org/files/564/564-h/564-h.htm

Stephanie Posthumus & Stéfan Sinclair (2014) Reading environment(s): digital humanities meets ecocriticism, Green Letters, 18:3, 254-273, DOI: 10.1080/14688417.2014.966737 



```bash
jekyll build --future
```
