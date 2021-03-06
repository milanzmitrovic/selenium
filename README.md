

# Selenium tutorial




## Tools that we are going to use


- Python 3.7

- PyCharm
- Selenium library
- Google chrome web browser
- Chromedriver.exe

## Basic pattern

1. Instantiate chrome instance

2. Get to the desired web page
3. Locate web element
4. Interact with web element


## Different ways to find/locate element

- by id
- by class name
- by name (html name attribute of element)
- by tag name
- by xpath
- by css selector
- by link text (a href html tag)
- by partial link text

## Complex/difficult locators

- xpath
- CSS selector

Separate lessons will be dedicated to these two ways of locating element.

Why are they usefull? - We can do sth like "Find element that has two 
child elements of type div that each has two li elements below it."




## Find element VS find element[S]

driver.find_element_by ... -> returns webelement object

driver.find_elements_by ... -> returns list of webelement objects


## Useful web site for testing practice

Here can be found web elements that we are 
going to use during exercises <https://formy-project.herokuapp.com> .

We can find detailed documentation of python selenium api on this 
link <https://selenium-python.readthedocs.io> . This is place where 
I used to spend lot of time when I was working with selenium.

## Which locator is good?

One that is:
- Unique
- Descriptive
- Static



## Getting started

- Install PyCharm community version
- Install google chrome
- Get chromedriver (check chrome version first)
- pip install selenium


## Why do we need automated tests?

- During development process, that can last several years, every week new features are added.
- Before proceeding with new functionalities, we need to be sure that old features work.
- Using automated tests, we can easily test all product features at once.



## Elements that we will learn to handle

TextBox, Submit button, CheckBox, Radio button, how to click on Image,
Select value from DropDown, Mouse Click and Keyboard events,
How to upload and Download files, Alert & Pop up window handling,
Handling Web Tables, Verifying Tooltip.

## Xpath cheatsheet

-
-
-

## CSS selector cheatsheet

-
-
-



