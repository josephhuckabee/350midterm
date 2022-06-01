---
title: fourth
layout: base.njk
tags: navItem
---

<link rel="stylesheet" type="text/css" href="fullpage.css" />

<!-- This following line is optional. Only necessary if you use the option css3:false and you want to use other easing effects rather than "easeInOutCubic". -->
<script src="vendors/easings.min.js"></script>

<script type="text/javascript" src="fullpage.js">
  $(document).ready(function() {
	$('#fullpage').fullpage({
		//options here
		autoScrolling:true,
		scrollHorizontally: true
    sectionColor: ['#fff', '#444', '#777', 'blue']
    css3: true
	});

	//methods
	$.fn.fullpage.setAllowScrolling(false);
});
</script>


<div id="fullpage">
	<div class="section">Some 1</div>
	<div class="section">Some2</div>
	<div class="section">Some 3/div>
	<div class="section">Some 4</div>
</div>