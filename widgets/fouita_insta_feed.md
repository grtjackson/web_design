Information taken from:

https://dev.to/haynajjar/how-to-embed-a-free-instagram-widget-on-your-website-3oi6?


# How to Embed the Instagram Widget

Here’s a step-by-step guide to embedding the Instagram widget on your website:
Step 1: Visit Fouita's Instagram Widget Page

Go to Fouita’s Instagram Widget page to get started.

# Step 2: Customize Your Widget

- Insert your Instagram profile link, username, or hashtag to pull the feed.
- Customize the layout and colors to match your website’s design.

# Step 3: Copy the Embed Code

Once you’ve customized the widget, copy the generated embed code.

# Step 4: Paste the Code into Your Website

Paste the embed code into your website’s HTML where you want the Instagram feed to appear.

# Example Embed Code

Here’s what the embed code looks like:

`<div id="ft-insta-app"></div>
<script type="module">
    import App from "https://cdn.fouita.com/public/instagram-feed.js"; 
    new App({ 
        target: document.getElementById("ft-insta-app"), 
        props: {
            "settings": {
                "layout": "carousel",
                "header": true,
                "autoplay": true,
                "zigzag": false,
                "cols": 4,
                "cardHeight": 300,
                "gap": 0,
                "direction": "down",
                "height": 700,
                "bgColor": "",
                "txtColor": "",
                "ukey": "xxxxxx-xxxx-xxxxx-xxxx-xxxxxxxxxx"
            }
         }
    });
</script>`

