# Timezones home page

This is a website that shows current time in several timezones, so you use it as your home page for your browser and that way you very easily know the time around the world.

I recommend you use the [Custom new tab URL](https://chrome.google.com/webstore/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia?hl=en)Chrome extension to set it as the default page for new tabs.

It is based on the [Figured It Out](https://chrome.google.com/webstore/detail/figure-it-out/lialghmkggocekkpjbnoacohodmckfke?hl=en) Chrome extension (free only for two timezones), if you want a more advanced idea, take a look at it.

To customize timezones, edit `index.html` and change the `zones` array.

```javascript
var zones = [
    {
        "location": "San Francisco",
        "timezone": "America/Los_Angeles"
    },
    {
        "location": "Spain<br>Milan",
        "timezone": "Europe/Madrid"
    },
    {
        "location": "London",
        "timezone": "Europe/London"
    },
    {
        "location": "New York<br>Boston",
        "timezone": "America/New_York"
    },
    {
        "location": "Tokyo",
        "timezone": "Japan"
    }
];
```

You can check this nice list of all available [timezone name definitions](https://docs.trifacta.com/display/DP/Supported+Time+Zone+Values). The order of the zones is rearrange for display in increased difference with local time.

You can fork this repo and publish your modification as a GitHub page, or download the `index.html` file and use locally or upload it to your own server.
