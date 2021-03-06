---
layout: post
title: UX of mailto
---
&ldquo;mailto&rdquo; hyperlinks in HTML have a bad rep that I've never really understood.

I generally prefer launching my mail client with an autofilled address, over deciphering a [at]/[dot] style address (i.e. the least human friendly thing ever), or an overly complex contact form.

Nonetheless, clicking a hyperlink and watching Mail.app launch when I *wasn't expecting it* seems to occur a lot more than it should. If you decide to include a mailto link, I encourage you to use one of these two display methods.

* Use the email address as anchor text. If people see an email address with your website's hyperlink styling, they'll assume that their mail client will launch on click. It's a standardised design pattern. Anything other than an email address (e.g. &ldquo;contact me&rdquo;, &ldquo;get in touch&rdquo;, etc), and the user will assume that they'll be taken to a new page. Unless you&hellip;
* &hellip;alert the user about what the link is going to do. Use a [tooltip](http://twitter.github.com/bootstrap/javascript.html#tooltips), and reveal a message on hover - &ldquo;launch your email client&rdquo; or a nicer sounding alternative. While I generally favour using the email address as the anchor, I'm aware that this can look a little out of place when placed inside a traditional navigation area. So, if you do vary the anchor text, give your users a warning.

Remember, people still use software like Outlook, and no one wants that opening when they're not expecting it.