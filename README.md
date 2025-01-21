# Sammi Browser Websocket Example

I wanted to make a small example SAMMI extension and corresponding browser page to be able to show how you can use OBS's websocket plugin to interact with the two.

Big thanks to [Krackatoa](https://bsky.app/profile/krackatoa.ca) for all the help!

## Implementation Notes

For ease of installation I've hosted `index.html` using [github pages](https://pages.github.com/) this is an easy and free way to have the html be on a server, but you could have your html file hosted locally.

The extension just exists for having a button making the scene as well as showing how to send data to the browser page. There's no commands or anything like that.

To install the extension, you'll need to go through the regular process. Then modify the `Create Scene` button to have your ws port and password (this will just set a query parameter on your browser source).

Once installed, you can press the `Send Event` button to see it show up in the browser.