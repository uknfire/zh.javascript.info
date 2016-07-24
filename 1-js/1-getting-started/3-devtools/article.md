# Developer console

And the one more thing before we get down to coding.

A code is error-prone. You are quite likely to have errors... Oh what I'm talking? You are *absolutely* going to make errors, at least if you're a human, not a [robot](https://en.wikipedia.org/wiki/Bender_(Futurama)).

But in the browser, a user doesn't see the errors by default. So, if something goes wrong in the script, we won't see what's broken and can't fix it.

To see errors and get a lot of other useful information about scripts, browsers have embedded "developer tools".

**Most often developers lean towards Chrome or Firefox for the development.**

Other browsers also provide developer tools, but are usually in a "catching-up" position, compared to Chrome/Firefox which are the best.

If there is an error in the certain browser only, then we can always switch to it's developer tools for the concrete problem.

Developer tools are really powerful, there are many features. On this stage let's just look how to open them, look at errors and run JavaScript commands.

[cut]

## Google Chrome

Open the page [bug.html](bug.html).

There's an error in the JavaScript code on it. It's hidden from a regular visitor's eyes, so let's open developer tools to see it.

Press the key `key:F12` or, if you're on Mac, then `key:Cmd+Opt+J`.

The developer tools will open on the Console tab by default.

It looks somewhat like this:

![chrome](chrome.png)

The exact look depends on your Chrome version. It changes from time to time, but should be similar.

- Here we can see the red-colored error message. In this case the script contains a "lalala" command, which was put there just because it is unknown.
- On the right, there is a clickable link to the source `bug.html:12` with the line number where the error has occured.

Below the error message there is a blue `>` symbol. It marks a "command line" where we can type JavaScript commands and press enter to run them (`key:Shift+Enter` to input multiline commands).

Now we can see errors and that's enough for the start. We'll be back to developer tools later and cover debugging more in-depth in the chapter <info:debugging-chrome>.


## Firefox, Edge and others

Most other browsers use `key:F12` to open developer tools.

The look & feel of them is quite similar, once we know how to use one of them (can start with Chrome), can easily switch to another.

## Safari

Safari (if you use Mac, not Windows/Linux) is a little bit special here. We need to enable the "Develop menu" first.

There's a checkbox for that at the bottom of the "Advanced" pane of the preferences:

![safari](safari.png)

Now `key:Cmd+Opt+C` can toggle the console. Also note that the new top menu item has appeared with many useful options.

## Summary

  - Developer tools allow us to see errors, run commands, examine variables and much more.
- They can be opened with `key:F12` for most browsers under Windows. Chrome for Mac needs `key:Cmd+Opt+J`, Safari: `key:Cmd+Opt+C` (need to enable first).

Now we have the environment ready. In the next section we get down to JavaScript.