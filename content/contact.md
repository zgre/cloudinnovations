---
title: "Contact"
heroBackground: "img/hero.jpg"
draft: false
---
---
<br>
<br>
<br>
Unit 2A, 17/F, Glenealy Tower, No.1 Glenealy
Central, Hong Kong S.A.R


<form name="contact" method="POST" data-netlify="true" class="contact-form">
  <label for="name">Name</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Message</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit">Send Message</button>
</form>

<style>
.contact-form {
  max-width: 400px;
  margin: 2em auto;
  padding: 2em;
  background: #f9f9f9;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  display: flex;
  flex-direction: column;
  gap: 1em;
}
.contact-form label {
  font-weight: 600;
  margin-bottom: 0.2em;
}
.contact-form input, .contact-form textarea {
  padding: 0.7em;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
}
.contact-form button {
  background: #007bff;
  color: #fff;
  border: none;
  padding: 0.8em 1.2em;
  border-radius: 4px;
  font-size: 1em;
  cursor: pointer;
  transition: background 0.2s;
}
.contact-form button:hover {
  background: #0056b3;
}
</style>

