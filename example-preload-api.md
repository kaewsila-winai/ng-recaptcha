---
layout: example
title: Preloaded reCAPTCHA API Example
permalink: /preload-api
backlink: example-preload-api
---

<script src="https://www.google.com/recaptcha/api.js?render=explicit&amp;onload=onloadCallback"></script>
<script>
    function onloadCallback() {
        System.import('examples/main-preload-api').catch(function(err) { console.error(err); });
    }
</script>