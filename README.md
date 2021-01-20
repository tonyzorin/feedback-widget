## ProdCamp embeddable feedback widget
How to add 

1. Sign up at ProdCamp.
https://app.prodcamp.com/sign-up?ref=github

2. Go to all products.
https://app.prodcamp.com/products/

3. Click on the existing product and click on the Widget tab on the top.

4. Click on the "Generate" button. The code will be copied to your clipboard.

5. Paste it to your page. It will look like:

`<script>
        !function(t,e,a,n){function o(){if(!e.getElementById(a)){var t=e.getElementsByTagName(n)[0],o=e.createElement(n);o.type="text/javascript",o.async=!0,o.src="https://cdn.prodcamp.com/js/prdcmp-widget.js",t.parentNode.insertBefore(o,t)}}if("function"!=typeof t.ProdCamp){var c=function(){c.args.push(arguments)};c.t="%TOKEN%",c.p="ABCDEFGHI", c.args = [], t.ProdCamp = c, "complete" === e.readyState ? o() : t.attachEvent ? t.attachEvent("onload", o) : t.addEventListener("load", o, !1) } }(window, document, "prodcamp-js", "script");
</script>`

6. In order to identify current user you need to provide the data in the following format:
`<script>
    ProdCamp('init', {
        email: 'janedoe@prodcamp.com',
        companyName: 'ProdCamp',
        firstName: 'Jane',
        lastName: 'Doe',
    });
</script>`

For more questions check our help:
https://help.prodcamp.com/feedback-channels/embeddable-widget

Privacy policy:
https://www.prodcamp.com/company/legal/privacy-policy
