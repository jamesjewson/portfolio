
# James Jewson's Portfolio Site
---
# Socials:
<p>
<a href="https://twitter.com/jjewson" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="jjewson" height="30" width="40" /></a>
<a href="https://linkedin.com/in/jamesjewson" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="james jewson" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/16706229/james-jewson" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="james jewson" height="30" width="40" /></a>
</p>

# <a href="https://jamesjewson.netlify.app/#contact">Contact Me Here</a>
--- 

# What is this site?

- This website was built to display my CSS, HTML, and JavaScript abilities, as well as serving as a place to showcase my portfolio. It is based on the following template:

# Dimension by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Dimension, a fun little one-pager with modal-ized (is that a word?) "pages"
and a cool depth effect (click on a menu item to see what I mean). Simple, fully
responsive, and kitted out with all the usual pre-styled elements you'd expect.
Hope you dig it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Responsive Tools (github.com/ajlkn/responsive-tools)



# If I asked you for help (Hi Josh)
- Most everything that I changed or am attempting to mainuplate is in main.js. This does not mean I won't need to change things in other files

- I'm attempting to make it possible to scroll through the articles instead of needing to click on each nav link. My issue is that sometimes more than one article is given the "active" class at a time. Other times the screen size gets a little messed up, and makes the page really long and places the article in a weird spot.


- Line 314 resets Scrolldown to 0 on body click
- Line ~400 begins scroll functionality
- I THINK I might be able to do something either with the code on util.js:275 or $main._show on main.js:75. 
- I tried on scroll if(window.location.href  = "#ID" and is at the botttom of the page){show the next one} and had the same issues. Let me know if this is confusing.
