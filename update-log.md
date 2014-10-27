---
layout: page
permalink: /update-log/
title: "Update Log"
description: 
modified: 2014-10-22 23:11:00 +0100
tags: []
jquery: true
---
## This page lists the last 20 commits.

<div id="github-commits"></div>

<script src="{{ site.url }}/assets/js/vendor/github.commits.widget.js"></script>

<script>
$(function() {
    $('#github-commits').githubInfoWidget(
        { user: 'xplorup', repo: 'xplorup.github.io', branch: 'master', last: 20, limitMessageTo: 20 });
});
</script>  