# DOM-Events-Udemy-Zero-to-Mastery-128-
My solution to the DOM Events Exercise from Andrei Neagoie's "The Complete Web Developer in 2019: Zero to Mastery".
I've added comments for all of the additions I made to the code beyond the initial template.

I took a different route than the solutions I saw posted, creating the Delete buttons as sibling nodes to their corresponding <code>li</code> items rather than children of them. I originally did this to avoid having the button's deleting onclick event trigger the toggling onclick event of its <code>li</code> parent. After the fact, I discovered (a) I could have used<code>stopPropagation();</code> to prevent this, but was hoping to get feedback as to whether my method was a viable alternative. Any feedback on quality/readability/etc is appreciated.

The direct link to the previewed webpage is here:

http://htmlpreview.github.io/?https://github.com/ricobadico/DOM-Events-Udemy-Zero-to-Mastery-128-/blob/master/index.html
