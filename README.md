# Full Date View
========
## PLEASE NOTE

**I cannot provide any support or guidance beyond this README. If this code helps you that's great but I have no plans to develop Full Date View beyond this demo (it's not a final product and has limited functionality). I cannot reply to any requests for help.**

* * *

### Convert Date into Full Date View (jQuery / Zepto plugin)

[**Try Full Date View Demo**](http://vidyutkumar.info/fulldateview)

Months is an experimental example and not under active development. If it suits your requirements feel free to expand upon it!

## Usage

Write your Full date HTML like so:

    <div id="fulldate">
        <input type="date" />
        <button type="button" >Submit</button>
    </div>

Then HTML for Output

    <textarea id="fulldate-output"></textarea>

Then activate with jQuery like so:

    $(SomeId).fulldate();

## Note

Default date format accepet of chrome else Date Format: yy-mm-dd 
Exp:
Input: 15/06/24
Output: Wednesday June 24, 2015
