---
theme: apple-basic
layout: intro
titleTemplate: '%s - Ilham Wahabi'
---

# Into Accessibility

Let's create a better web for everyone!

<div class="absolute bottom-10">
  <span class="font-700">
    Ilham Wahabi, June 25 2021
  </span>
</div>

---

# Who is the speaker???

<br>
<br>

- 😀 **Name:** - Ilham Wahabi
- 📝 **Role:** - Frontend Developer
- 👨‍🎓 **Education:** - Informatics ITB
- 🤝 **Ex:** - Dekoruma, Stoqo, etc
- 👨‍💻 **Hobby:** - Hacking at iwgx.io
- 🧑‍ **Currently:** - CTO Bersihin.co

<br>
<br>

Follow me on [Twitter](https://twitter.com/ilhamwahabigx) and [Github](https://github.com/iwgx) 👋

---
layout: section
---

# What is Accessibility?

---
layout: quote
---

# "Web accessibility means that people with disabilities can use the web (perceive, understand, navigate, interact, contribute)"

---
layout: section
---

# Why Accessibility Important?

---
layout: quote
---

# "About 30.38 million Indonesians — 14.2 percent of population — had a disability in 2018 "
Survei Sosial Ekonomi Nasional

---
layout: quote
---

# "About 56.7 million Americans — 19 percent of the population — had a disability in 2010"

---
layout: quote
---

# "An estimated 7.9 million persons (age 6 and older) have difficulty seeing words and letters in ordinary newspaper print"
Lighthouse International Research Study

---
layout: quote
---

# "Currently around 10 per cent of the total world's population, or roughly 650 million people, live with a disability."

---
layout: bullets
---

# Types of Disabilities

<br>
<br>

* Attention-Deficit/Hyperactivity Disorders
* Blindness or Low Vision
* Brain Injuries
* Deaf/Hard-of-Hearing
* Learning Disabilities
* Physical Disabilities
* Speech and Language Disabilities

---
layout: bullets
---

# Developer Should Care Because

<br>
<br>

* We're making it inaccessible
* Human rights
* Legal issue
* Reach a larger audience

---
layout: section
---

# How People Browse the Web?

---
layout: intro-image-right
image: '/images/mouse.jpg'
---

# Mouse


---
layout: intro-image-right
image: '/images/keyboard.png'
---

# Keyboard

---
layout: intro-image-right
image: '/images/head-wand.jpg'
---

# Head Wand

---
layout: intro-image-right
image: '/images/mouth-stick.jpg'
---

# Mouth Stick

---
layout: intro-image-right
image: '/images/single-switch.jpg'
---

# Single Switch

---
layout: intro-image-right
image: '/images/screen-reader.jpg'
---

# Screen Reader

---
layout: section
---

# Any Complaints?

---
layout: quote
---

# "Amazon were sued in 2018 on claims that their website was inaccessible to the blind and visually impaired"


### The lawsuit claimed that the website Amazon.com did not provide text alternatives for non-text content on its website, blocking screen-reading software from presenting information to visually impaired users


---
layout: quote
---

# "Burger King was subject to an ADA lawsuit in 2018."

### It explained that every time the claimant visited the website, they experienced problems that prevented from accessing key information about their goods and services.

---
layout: quote
---

# "In 2012, it was claimed that Netflix, failed to provide adequate closed captioning on its 'Watch Instantly' program."

### A settlement was agreed and Netflix agreed to quickly provide captions on newly released content.

---
layout: bullets
---

## the list goes on:

* Apple
* Nike
* Hulu
* Bank of America
* Rolex
* eHarmony
* NBA
* and many more ...

<br>
<br>
<br>

# Your company next ???

---
layout: section
---

# Let's Prevent That

---
layout: bullets
---

## Image Alt Text
- Make it accurate
- Make it concise
- Don't be redundant
- Don't use "image of" or "graphic of"

<br>

```html
// Bad example, no alt text ❌
<img src="bandung.jpg" />

// Bad example, we already know that was picture ❌
<img alt="Picture of Bandung" src="bandung.jpg" />

// Good example ✅
<img alt="Scenery of Bandung city" src="bandung.jpg" />

// Good example, if it's just decorative image ✅
<img alt="" src="pattern.jpg" />
```

---
layout: bullets
---

## ARIA Attributes

<br>

---
layout: bullets
---

## Semantic HTML
- Always prefer use appropriate element
- Use sorted headings (h1-h6) and landmarks

<br>

```html
// Bad example, use "button" instead ❌
<div onclick="submitForm()">Click Me</div>

// Bad example, use "h1" instead ❌
<p class="header-1" />

// Good example, use tag properly ✅
<a href="twitter.com">Navigate to Twitter</a>
```

- If forced, you can use ARIA attributes to mimic it

```html
// Mimic 'button' element into a 'div'
<div tabindex="0" role="button" class="button" onclick="btnClicked()" onKeyUp="btnClicked()">
  Click Me
</div>
```
---
layout: bullets
---

## Color Contrast

<br>

---
layout: bullets
---

## Focus Management

<br>

---
layout: bullets
---

## Announcements

<br>

---
layout: section
---

# actually many more...

<br>
<br>
<br>

## let's save it for the next occasion :)

---
layout: section
---

# Tools to Help Us