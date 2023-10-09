# jp-wordapp-v1.0.0
An app for benkyouing the nihongoz, specifically vocabulary.

# About 
Version 1.0.0 of my word app for studying Japanese vocabulary in a fun, quick, and efficent way. 

The concept is based on RealKana by HooLogic. 

You select the word list, choose your settings, select the words you want to study, then start the quiz! 

The quiz by default randomly selects a word, then randomly selects the current answer. The current answer will either be the English meaning of the word or the reading in Japanese. Once the current answer is answered, it will go to the unanswered answer (example: if you first answered the meaning, it would go to the reading). Once both answers are answered (the meaning and reading), it moves onto the next word. You can toggle the randomization off and on, as well as whether or not you want to learn both or only the reading or meaning. The quiz goes on indefinitely. 

# Technical Note
You will need a live server to fully view the app. The word lists are JSON files. 

Written with HTML, CSS, and plain JavaScript.

# Other Notes
The JSON files provided in this version are only the test files, not the full ones. They're sufficient for functionality. 

Feel free to build your own version of the app. I know one of the most annoying things for me over the past 1.5 years was trying to find similar apps I could use as code reference and couldn't (particularly with the double-answer-randomization). Credit is appreciated. If you use my app as a basis for yours, including the HTML and CSS, please remove my branding and stuff lol – I hope that's obvious.

# Backstory 
I had this app idea for about 1.5 years. 

I returned back to learning Japanese mid-January 2022 after a 9 – almost 10 – year hiatus after I read a manga I couldn't get enough of and pretty much went "I'm not waiting for the next volume, I'm reading it in Japanese" and proceeded to do so. This lead to creating custom word lists of all the different words I didn't know. 

I wanted a really fast and efficent way to learn all 3000+ words in my word lists. I very quickly concluded a web app in the style of RealKana (https://realkana.com/) would be most effective based on my previous experience. 

The reason why it took me about 1.5 years to build the app is because I didn't actually know how to build it. My JavaScript skills were pretty much non-existant and I could barely use anything more than console.log. I needed to relearn JavaScript, but I dragged my feet with doing that. 

Then around May 2023, I started focusing on web development again and decided to properly learn JavaScript this time. I spent about 1 hour and 15 minutes a day, 4x a week relearning JavaScript for about 2 or 3 months. 

It was the end of July 2023 when I felt frustrated that the app wasn't already built and I didn't already know all 3k+ words in my word list. 

...then it occured to me that I probably knew enough JavaScript to build the app. I also probably had enough knowledge of JavaScript now to properly search for things I didn't know. 

So I tried...and succeeded!!! 

Okay, sure. 

There's a bit of a weird glitch when typing kana for the answer where the input validates before fully answering. 

Some parts aren't the most beautiful. 

The mobile version of the app isn't fully developed yet.

There are other features I'd like to have that are planned for later versions. 

The basic concept of the app though – a typing test that randomizes both the reading and the meaning; instant feedback on whether or not the word is right or wrong – all of that is there. It works. That's what matters to me. 

I wanted to share it with others mostly because I figured other people would find it useful too. If it was, I would love to hear about!
