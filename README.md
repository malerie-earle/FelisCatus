# FelisCatus
Website created for software development program assignment.


Assignment Instructions:
Overview:

You are asked to create a small wildlife educational website. You will pick a species of animal, bird, insect, fish, etc. and research this species online. You will then create a multimedia website that uses resources about your chosen species (e.g., images, audio, and video) from open web archives.

The web is full of both proprietary and open-licensed resources. The former cannot be reused by you: you can’t take an image or logo from someone else’s site and use it on your own. This is a copyright violation. However, there are also many open resources that you can copy and reuse. Learning how to find and use these correctly is important when building your own web content.

Requirements:

Step 1. Choose a Species

Pick a species to research from those listed in iNaturalist, see:

https://www.inaturalist.org/observations?place_id=any&view=species

It can be a plant, animal, insect, bird, etc. Ideally you should choose a species that lives near you, but you are free to also choose something else that you find interesting. You must work on your own species (i.e., you can’t partner with other students in the course). Given the number of natural species in the world, it would be surprising if two students chose the same one.

Step 2. Research on iNaturalist.org

Research your chosen species using iNaturalist’s website. For example, if you were interested in the Red-bellied Woodpecker, you would begin with the following page:

https://www.inaturalist.org/taxa/18205-Melanerpes-carolinus

Learn as much as you can about the species. Take notes to help you with the creation of your website. You may NOT copy the text word-for-word, only use it as background material.

Step 3. Research on 3 Other Platforms

Conduct a similar search for other sources of information about your chosen species. Find 3 other web resources to use in your research. Try to find reputable sources of information. Take notes as you do your research on these other sites and keep track of all the sites/URLs you use. You will need to properly cite these in your about.html page (see below).

Step 4. Write a Research Summary [OPTIONAL-YOU CAN USE LOREM HERE IF NOT ABLE TO WRITE THE SUMMARY OF YOUR OWN – DON’T STUCK ON THIS RATHER FOCUS ON THE MARKUP CONTENT MORE]

Write a 500 to 1,000 word summary of your research. Your goal is to educate a non-scientific audience about your chosen species. Give them an overview and summary. You should define any terms you use, and help your reader understand the concepts you discuss.

You may NOT copy/paste any text, all words must be your own.(Or Lorum ipsem 😊)

Step 5. Convert to Markup

Convert your text to HTML. Make use of all appropriate HTML elements https://developer.mozilla.org/en-US/docs/Web/HTML/Element. For example, if you use lists or acronyms, quotes or technical terms, dates or definitions, etc. you should make use of the associated HTML5 elements.

In your final markup, you should try to use HTML5 semantic elements as much as possible (see https://developer.mozilla.org/en-US/docs/Web/HTML/Element), for example

- <meta> tags for document, author, topic details

- <title> for the document’s title

- <article>, <header>, <footer> for the structure of your document

- <nav>, <li> for navigation links

- Headings <h1>, <h2>, …

- Definitions using <dfn>

- Figures using <figure>, <figcaption>

- Lists using <ol>, <ul>, <li>

- Paragraphs <p>

- Hyperlinks <a>

- Abbreviations <abbr>

- Quotes and Citations using <q>, <blockquote>, <cite>

- Data and Time using <time>, <data>

- Inline text with <em>, <i>, <strong>, <b>

You will be marked on your knowledge and use of these elements, and how well you have used them to markup your text. You may NOT submit a series of plain text paragraphs with no other elements. Spend some time choosing and implementing your markup.

Step 6. Add Media

Find supporting media resources to help educate the reader on your topic. Media helps tell a story and is one of the secret powers that the web has over other print media.

Here’s an example web page from the Globe and Mail newspaper that uses a mix of text and media well:

https://www.theglobeandmail.com/canada/article-the-last-lighthouse-keeper-why-a-nova-scotian-couple-refused-to-leave/

In this site you see all of the following HTML5 and media being used:

- Text Headings and Paragraphs

- Images with captions

- Audio

- Video, both looping/muted in the background, and also embedded

- Graphics (e.g., Interactive Map)

Your site doesn’t need to be this elaborate, but hopefully you get some ideas to help guide your use of text and media.

You can use any open licensed media resource that allows reuse, but may not use copyright materials. How do you know if something is copyright? Everything is copyright! Unless you are told you can reuse something that you find, assume that you can’t. Open licensed materials will be marked as such.

Here are some links to help you find open licensed media:

- https://support.google.com/websearch/answer/29508?co=GENIE.Platform%3DAndroid&hl=en - https://www.wikihow.com/Find-Creative-Commons-Videos-on-YouTube - https://search.creativecommons.org/ - https://unsplash.com/ - https://www.flickr.com/creativecommons/

You are asked to include the following open licensed resources on your page:

- At least 2 photos

- At least 1 video (i.e. using the <video> element) or 1 YouTube embed (i.e., using an <iframe>)

- 1 audio resource (i.e. using the <audio> element) in your page. If you can’t find audio directly related to your topic, get creative. Maybe you can use background sound, or include a song from a band that uses the same name.

Use appropriate HTML to include these resources in your site along with the text you have written. You may link to external URLs where applicable (i.e., you don’t have to download and use resources if they are publicly hosted). Make sure you do the following:

- All images should have alt text included and used captions to describe the image and give credit

- Videos and Audio should include controls - Use appropriate sizes for all media. You can use a tool like https://squoosh.app/ to reduce the size of an image that is very big to download.

Step 7. Add A Design

You can use either the following style sheets OR create your own as we have discussed lately in our classes.

However, you are encouraged to use one of the various “class-less” CSS stylesheets described here: https://css-tricks.com/no-class-css-frameworks/ These stylesheets can be included in the <head></head> of your document, for example:

<head>

<link rel="stylesheet" href="https://unpkg.com/mvp.css">

Try experimenting with some of these stylesheets to find one that makes your page look good to you.
