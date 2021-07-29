# Conquering Responsive Layouts

![Conquering Responsive Layouts image](https://d31ezp3r8jwmks.cloudfront.net/gjQ6wqLoXSviuBRJPa3PXUPi)

This repo tracks the progress and general tips from [**Conquering Responsive Layouts**](https://courses.kevinpowell.co/courses/conquering-responsive-layouts) tutorial, by [Kevin Powell](https://youtube.com/kevinpowell)

<hr>

## Day 1
* A website is responsive by default. If it's not responsive, it's because we've done something to make our website not responsive.
* Percentages in CSS **(%)** are relative to the parent element.
* Avoid using heights.

## Day 2
* **em** is a unit related to the parent element, while **rem** refers to the font size of the root (normally 16 pixels).
* Use **rems** to font sizes and avoid using **ems**.
* **ems** can be used in paddings, margins, widths, etc, especially in buttons, to mantain proportionality.

## Day 3
* Use **max-width** to limit a certain element width to a given point.

## Day 4
* **vw** and **vh** (viewport width and height, respectively) are units related to the screen size.
* These units are particularly useful for proportional titles, padding and margins, for example.

## Days 5, 6 and 7
* Practice Time, review of the week and solution to the challenge.

## Day 8
* Introduction to flexbox and flexbox challenge 01.

## Day 9
* Including images in Flexbox may cause an issue. The image can stretch. **align-items** and **align-self** can solve it.
* **justify-content** can solve another position problems. It'a property that can be used to control the empty space in a flex container.
* In order to **justify-content** to work, the sum of the widths of flex items needs to be less than 100%.
* **max-width** of 100% can make every image responsive, and ensure it will never be bigger than its original size.

## Day 10
* Flexbox challenge 02 + some extra optional content.

## Day 11
* Flexbox challenge 03.

## Day 12
* Tricks to fancier up the navigation bar.

## Days 13 and 14
* Flexbox challenge 04 + Break Time!.

## Days 15 and 16
* **Media Queries** allow us to overwrite some styles based on some conditions, generally the screen width.
* There are two approaches related to media queries: **Mobile-first** and **Desktop-first**.
* The order of media queries matter, so they can overwrite each other. In case of min-width, the order is to smallest to greatest.
* Keep the media queries to a minimum possible, to make the CSS easier to mantain.

## Day 17
* The meta viewport tag is very important. It ensures the website is going to be responsive the way you want it be.
* The tag is `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

## Day 18
* Don't do layout things at first. Initially, it's better to focus in global styles and basic styles, such as tipography, colors, spacing, etc.
* The major advantage of mobile-first is that you don't have to worry so much about layout.

# Day 19
* Avoid lines of text that go all the way across the screen

# Day 20
* Navigation challenge - Adapting navbar to mobile-first workflow

# Day 21
* Final challenge (without video solution)
