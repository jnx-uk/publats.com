---
title: Contact
permalink: "/contact/"
layout: page
---

 <div class="container">
  <form action="/contact/sent" name="contact" method="POST" data-netlify="true">
<p>
    <label for="fname">Name</label><br />
    <input type="text" id="name" name="name" placeholder="Your name.."></p>
<p>
    <label for="lname">Email</label><br />
    <input type="email" id="email" name="email" placeholder="Your email address.."></p>
<p>
    <label for="message">Message</label><br />
    <textarea id="subject" name="message" placeholder="Your message.." style="height:200px"></textarea></p>
<p>
    <button type="submit">Send</button>
</p>
  </form>
</div> 