# Fall 2024 Principles of Databases — Assignment 1

* **Read these instructions repeatedly until you understand, then begin your project. If something is not clear, ask.**

## ❖・Before You Begin・❖

1. Log in to GitHub.
2. Fork this repo(sitory). See [this video](http://code-warrior.github.io/tutorials/git/github/forking-and-cloning-at-the-github-web-site/) on how to carry out this step and step `3`.
3. Clone your fork, using either the web site or the GitHub Desktop client.
4. Checkout your personalized branch, the one with your name and GitHub handle.

---

## ❖・Introduction・❖

In this assignment, you’ll work in two languages: XML and JSON; one will mirror the other. For the XML part, you’ll create an XML document that represents students at a university, and you’ll author a grammar, via a DTD document, that will define the language of your XML document. You’ll use the content in the included `content.md` file to create this XML project. You’ll then convert the XML to its JSON equivalent.

---

## ❖・Details・❖

Per `content.md`, your student is comprised of the following information:

* First name
* Middle name
* Last name
* Preferred name
* Student ID
* Email
* Phone
* Status (first year, second year, etc)
* GPA
* Major
* Minor
* Status (full-time, part-time, graduated, withdrawn)
* Advisor
* Date of initial enrollment
* Graduation date

---

## ❖・Rules・❖

### General

* You may *only* use the content in the included `content.md` file for this assignment.
* Indent all your code, regardless of language, uniformly by 2 spaces. Do not mix tabs and spaces.
* Implement the JSON and XML independently, then compare, as one will likely be more logical than the other.

### XML Section

* Your markup must go in `xml/index.xml`.
* Your style content must go in `xml/style.css`.
* The grammar of your XML project must go in `xml/student.dtd`.
* Comment every line of your DTD.
* Author the DTD on your own; no help from WebStorm.
* Style your XML using CSS so it’s easy to read in the browser.
* Expose any XML attributes to the front end using CSS’s [`content`](https://developer.mozilla.org/en-US/docs/Web/CSS/content) property and [`attr()`](https://developer.mozilla.org/en-US/docs/Web/CSS/attr) function.
* Use the [XML Language Support by Red Hat extension for VS Code](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml), extension ID `redhat.vscode-xml`, to validate your XML with your DTD.

### JSON

* Validate your JSON directly in your editor and/or at [jslint.com](http://jslint.com/).

---

## ❖・Grading・❖

| Item                     | Points |
|--------------------------|:------:|
| *XML Implementation*     | `20`   |
| *DTD Implementation*     | `20`   |
| *JSON Implementation*    | `20`   |
| *Code Quality*           | `20`   |
| *Following Instructions* | `20`   |

---

## ❖・Due・❖

Thursday, 19 September 2024, at 10:00 AM. ***Note*: Per the syllabus, NO late submissions will be accepted**

---

## ❖・Submission・❖

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may *only* be submitted via GitHub. **No other form of submission will be accepted**.
