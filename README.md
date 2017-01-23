# trump-clock
A little website to help us all count down the day until Trump is gone. To see the final product, visit http://zimboboys.com/trump-clock/

I used HTML, CSS, and JavaScript to make this site.

### how it's made
The HTML is just a very basic framework for the actual dates to go into. The <span> elements are used to give the times a place to fit in while remaining on the same line.

CSS is pretty much as basic as I could go, with just some background colors, font styles, and font colors. This is to give it the "American feel".

JavaScript - the one thing that I know nothing about - is what this project is focused on. Without going into too much detail about what is going on with the coding stuff, I will try to explain it.

1. The goal date, 20 January 2021 at 17:00:00 GMT (the same time when the inaguration takes place), was put into epoch time, because this is what computers use to read dates.
2. The computer's time is also looked at in epoch time, and these times are subtracted to get the remainging milliseconds until the big day happens.
3. This is converted into years, days, hours, etc. by divinding the amount of milliseconds.
4. All of these new integers are then set as the <span> elements to display the final product.