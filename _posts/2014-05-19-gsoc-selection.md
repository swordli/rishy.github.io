---
layout:     post
title:      Google Summer of Code 2014
date:       2014-05-19 01:30:45
summary:    Got Selected for Google Summer of Code 2014, with Mifos as my mentoring organization.
categories: GSOC'14
comments: true
---

I have got selected for Google Summer of Code 2014 and from today onwards the Coding period for GSOC starts.

For next 3 months I'll be working on developing a Batch API for an awesome community - [mifos](http://mifos.org/).

Mifos is an organization that leverages the power of Open Source to fuel the functioning of micro-finance institutions and helps in fighting poverty, worldwide.

[Batch API](https://mifosforge.jira.com/wiki/display/projects/GSOC+2014+-+Batch+API) project is focused towards creating an API akin to [facebook-multiple-requests](https://developers.facebook.com/docs/graph-api/making-multiple-requests/) so that multiple HTTP requests can be handled by mifos platform. This provides an efficient way for clients based on mifos platform to send multiple HTTP requests as JSON string and get back a Batch HTTP response in JSON.

For this project I'll be working with Java(Spring/Jersey/JPA) for developing the backend API and AngularJS and Bootstrap 3 for making all the UI changes. Development work regarding the Batch API can be followed at: [Github - mifos X Batch API](https://github.com/rishy/mifosx/tree/Batch-API).

<!-- % if page.comments % -->

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = 'rishabhshukla';
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>

<!-- % endif % -->