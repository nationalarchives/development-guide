# Peer review checklist

This checklist represents all the checks necessary to ensure that all steps contained in the accompanying [development guide](development-guide.md) have been followed. Each section corresponds to a Checkpoint in the Development Guide and there are sections for comments from both the developer(s) and peer reviewer.

If for any reason it has not been possible to meet any individual standard set out in the development guide the reason and justification should be recorded here.

## Checkpoint 1: We meet needs using HTML - Comments from peer reviewer and developer(s)

The W3C validator identified 14 issues with the HTML. Of these:

* 1  related to `<meta>` tag http-equiv and X-UA-Compatible
* 10 **Priority*  related to the vue.js tags like .e.g v-cloak, v-if etc.
* 1  **Priority* relate to a end tag 'br'.
* 2  related to the type attribute is unnecessary for JavaScript resources.

Within the 'Wifi' form: 

* **Priority** the 'email' field currently has no type and it should be 'email'
* **Priority** missing the 'for' attribute on the checkbox's 'label' 

## Checkpoint 2: Enhance with CSS - Comments from peer reviewer and devloper(s)

**Priority** the text is underlined on the connect button

## Checkpoint 3: Enhance with JavaScript - Comments from peer reviewer and devloper(s)

**Priority** there's no JS fallback on terms and conditions when JS is disabled in the browser 

## Checkpoint 4: Implementation reflects key architectural considerations - Comments from peer reviewer and devloper(s)

All key architectural considerations are OK here.

## Checkpoint 5: pre-release checks

* Release version is WCAG 2.0 compliant at AA
* Testing user goals across browsers, devices and contexts

**To be done after the issues identified above have been addressed**

### Comments from peer reviewer and developer(s)
1. 10 **Priority*  related to the vue.js tags like .e.g v-cloak, v-if etc.
> >  I'm not sure how could this be resolved, as these are the directives provided by the vue.js framework. I have spoken to our Lead front developer, and said that this should not be an issue.

2. related to `<meta>` tag http-equiv and X-UA-Compatible
> > This is an issue that has come from our TNA base, and would need to be flagged globally.

3. **Priority* relate to a end tag 'br'.
> > This is now fixed.

4. related to the type attribute is unnecessary for JavaScript resources.
> > This is now fixed.

5. the 'email' field currently has no type and it should be 'email'
> > This is now fixed.

6. missing the 'for' attribute on the checkbox's 'label'.
> > This is now fixed.

7. the text is underlined on the connect button
> > This is now fixed.

8. there's no JS fallback on terms and conditions when JS is disabled in the browser.
> > This is now fixed.


## Lessons learned

What are the key lessons to take forward for future projects?