This piece of code will take screenshots of elements. I work in the advertising branche and sometimes we need to know whether the ads are not blank. We don't get any revenue of blank advertisements.

Implement the class in your project and add the following two line to your testing code:

    TakeElementScreenshot screenshot = new TakeElementScreenshot(driver);
    screenshot.shoot(element);
