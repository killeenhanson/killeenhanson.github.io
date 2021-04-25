---
layout: text
title: Blank Template
question: How do I best communicate what motivates my work?
label: 
tags: 
categories:
description: This is a blank template for experimenting with the features and organization of the pages on this website.
publish: April 2021
year: 2021
image: 
permalink: /projects/blanktemplate
---

<figure>
<img src="/images/projects/neighborly_2971.JPG">
    <figcaption>Full-width image with caption.</figcaption>
</figure>

<p>Opening paragraph with preceeding full-width image and caption. To insert a full-width image, put the image between <i>figure</i> tags.</p> 

<p>But that's not the only way you can use images! You can insert column-width images like so:</p>

<img src="/images/projects/neighborly_2971.JPG">
    
<div class="images-right"><p>&uarr; Column-width image with right-aligned caption with <a href="https://example.com">link</a>.</p></div>
<section class="clear"></section>

Here's some basic text content:

<figure>
    <figcaption>These markdown tips come from <a href="http://www.markdownguide.org/basic-syntax">http://www.markdownguide.org/basic-syntax</a></figcaption>
</figure>

Fun fact: In markdown, I don't need to separate your paragraphs with paragraph tags. Instead, to create paragraphs, use a blank line to separate one or more lines of text. But, <a href="https://www.markdownguide.org/basic-syntax/#paragraphs">unless the paragraph is in a list</a>, don’t indent paragraphs with spaces or tabs.

And if I want to just make a line break, as I would with a <br /> tag, <a href="https://www.markdownguide.org/basic-syntax/#line-breaks">I can</a>, by using two or more spaces (commonly referred to as “trailing whitespace”) for line breaks. But it's maybe not the best option, because it’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. Fortunately, there is another option supported by nearly every Markdown application: the `<br>` HTML tag.

(In the previous paragraph, in order to make the `<br>` tags legible, or, in any case when I want to denote a word or phrase as code, I need to enclose it in backticks (<code>`</code>) or enclose the backticks with `<code></code>` HTML tags. And if the word or phrase I want to denote as code includes one or more backticks, I can escape it by enclosing the word or phrase in double backticks (<code>``</code>).)

And a blockquote:

>Phasellus suscipit pulvinar mauris et ultrices. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Quisque elementum in nibh a imperdiet. Nullam posuere fermentum nulla, vitae consectetur nisi fermentum sed. Mauris faucibus, velit vitae ullamcorper dignissim, libero est iaculis tortor, vel malesuada justo nisl ut sapien. Ut quis sapien sed risus lobortis interdum. Morbi ut risus eget nunc tincidunt euismod. Mauris finibus euismod molestie. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aliquam viverra rutrum pretium.

<figure>
    <figcaption>You can insert margin text anywhere, by using the <i>figure</i> and <i>figcaption</i> tags. The margin text is aligned with the text or image that follows it.</figcaption>
</figure>

Aenean aliquet mollis erat, fermentum porta erat lobortis sit amet. Morbi imperdiet metus non tellus rutrum, a pharetra ante interdum. Fusce sagittis nisi nulla. Sed laoreet elit sit amet lectus venenatis fringilla. Donec vel tellus velit. Quisque sapien erat, gravida non nisi eu, volutpat fringilla diam. Cras purus lectus, lacinia ac lacus id, condimentum dignissim orci.

<p>You can include links to footnotes within the text, like <a id="footnote-1-ref" href="#footnote-1">this</a>. You can also arrange the images in two columns, like so:</p>

<div class="images-left">
    <img src="/images/projects/neighborly_2971.JPG"></div>
            <p>&uarr; mushrooms, calabrian chili peppers</p>

<div class="images-right">
    <img src="/images/projects/neighborly_2971.JPG"></div>

<section class="clear"></section>

... or like this, with the images spanning across the main text column, if you put them between <i>figure</i> tags:

<figure>
<div class="images-left">
    <img src="/images/projects/neighborly_2971.JPG"></div>
    
<div class="images-right">
    <img src="/images/projects/neighborly_2971.JPG"></div>
    <figcaption>Caption for the two images above.</figcaption>
</figure>

<section class="clear"></section>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec laoreet sapien eu rhoncus bibendum. Donec tristique, ex et lobortis porttitor, justo mauris tempor purus, sed pellentesque quam mi sit amet augue. Pellentesque eget porttitor mauris, vel feugiat nisi. Cras sed arcu non purus consequat gravida.

<figure>
    <figcaption>But if you want to use a superscript number, you have to remember to use the <i>class=footnote</i> within the link tag, which looks better than using the <i>superscript</i> tag. (Also, I don't know how marginalia works on mobile devices. TBD.)</figcaption>
</figure>

I can decide to use the margins for the footnotes, which could be cool, and can choose to link a number<a id="footnote-2-ref" class="footnote" href="#footnote-2">2</a> rather than a word to the footnote. Marginalia is neat!

Integer euismod cursus dolor eu luctus. Ut sed laoreet ligula. Duis luctus rhoncus nisl et porttitor. Morbi quam sem, lobortis et lacus eget, finibus mattis mi. Aenean neque ex, condimentum et nisl eu, fermentum varius magna. Ut condimentum neque ac elit tempor suscipit.

Unordered lists don't look very exciting in this template, FYI:

<ul>
    <li>- Sed vehicula finibus libero, bibendum placerat dolor pulvinar ut. Integer ornare in tortor eget suscipit.</li>
    <li>- Morbi aliquet lectus ante, et semper arcu blandit vel. Nullam gravida a mauris at pulvinar.</li>
    <li>- Proin a nisl consectetur, elementum sem et, viverra ante. Donec egestas blandit venenatis. </li>
    <li>- Integer vel nibh ex. Nam consectetur, lacus in euismod pellentesque, ligula ipsum accumsan quam, dignissim porttitor est nunc sit amet metus.</li>
</ul>

<br>
Ordered lists work slightly better:

<ol>
    <li>Sed vehicula finibus libero, bibendum placerat dolor pulvinar ut. Integer ornare in tortor eget suscipit.</li>
    <li>Morbi aliquet lectus ante, et semper arcu blandit vel. Nullam gravida a mauris at pulvinar.</li>
    <li>Proin a nisl consectetur, elementum sem et, viverra ante. Donec egestas blandit venenatis. </li>
    <li>Integer vel nibh ex. Nam consectetur, lacus in euismod pellentesque, ligula ipsum accumsan quam, dignissim porttitor est nunc sit amet metus.</li>
</ol>

<br>
Morbi nisl lacus, feugiat lobortis metus vitae, lacinia hendrerit elit. Nunc tempus ex non scelerisque sollicitudin. In hac habitasse platea dictumst. 

<!--Footnotes -->
<div class="notes">
<h4>Notes</h4><br />

<ol>
    <li><p id="footnote-1">This is the content for footnote #1. To use footnotes, you'll need to update the number within the link tag.&nbsp;<a href="#footnote-1-ref">↩</a></p>
    </li>
    <li><p id="footnote-2">FYI, the content for Footnote #2 is in the margin alongside the footnote link.&nbsp;<a href="#footnote-2-ref">↩</a></p></li>
</ol>

<i>You can put generic note text here. It's a good place for saying thank you, referencing general inspirations, mentioning publication history, etc.</i>

</div>