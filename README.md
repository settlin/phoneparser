Bloated & Deprecated
====================
While it works, I will not recommend this. (Mind it, this is also not available at npm, so you have to use it from git directly).

Better option: Use https://github.com/halt-hammerzeit/libphonenumber-js via `npm install libphonenumber-js`. Cleaner, simpler and better.

PhoneParser
===========

A very simple to use library that parse phone numbers into country code, area code, and number.
It uses libphonenumber.

Here is a demo: https://rawgit.com/Gilshallem/phoneparser/master/demo.htm

Usage
========
1. Download phoneparser.js
2. Link the js file to your html or any other type of project.

Thats it!


Example
========

parsePhone("12025550104");

result:
{
  countryCode:1,
  areaCode:202,
  number:5550104,
  countryISOCode:"US"
}

ENJOY!! :)
