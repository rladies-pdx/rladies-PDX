---
title: "Propose a meetup"
date: "2016-05-05T21:48:51-07:00"
---

<form action="https://formspree.io/apresstats@gmail.com" method="POST">
  <label for="name">What's your name? </label><br>
  <input type="text" name="name" required="required" placeholder="Name"><br>
  <label for="email">What's your email address? </label><br>
  <input type="email" name="_replyto" required="required" placeholder="Email"><br>
  <label for="message">Your proposal:</label><br>
  <textarea cols="100" rows="20" name="message" id="message" required="required" class="form-control" placeholder="Describe what you want to talk about"></textarea>
  <input type="hidden" name="_next" value="/html/thanks.html" /><br>
  <button type="submit" class="btn">
    <i class="fa fa-send fa-lg" aria-hidden="true"></i> Send
  </button>
  <input type="hidden" name="_subject" value="Website message" />
  <input type="text" name="_gotcha" style="display:none" />
</form>