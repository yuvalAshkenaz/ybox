<section>
			<h3>Files</h3>
			<pre><code><span class="blue">&lt;link</span> <span class="red">rel</span><span class="purple">="stylesheet"</span> <span class="red">href</span><span class="purple">="dist/css/ybox.min.css"</span> <span class="blue">/&gt;</span>
<span class="blue">&lt;script</span> <span class="red">type</span><span class="purple">="text/javascript"</span> <span class="red">src</span><span class="purple">="dist/js/directive.min.js"</span><span class="blue">/&gt;</span></script>
<span class="blue">&lt;script</span> <span class="red">type</span><span class="purple">="text/javascript"</span> <span class="red">src</span><span class="purple">="dist/js/ybox.min.js?lang=he"</span><span class="blue">/&gt;</span></script></code></pre>
		</section>
		<section>
			<h3>All parameters</h3>
			<table border="0" cellpadding="10" cellspacing="0" width="100%" style="line-height:24px;">
				<tr>
					<td width="360">code</td>
					<td width="25" class="hide-on-tablet">:</td>
					<td>
						When calling to yBox from your Java Script, you can write your HTML code<br />
						<code>yBox({ code: '&lt;div class="my-class"&gt;Some text&lt;/div&gt;' });</code>
					</td>
				</tr>
				<tr>
					<td>self</td>
					<td class="hide-on-tablet">:</td>
					<td>
						<code>&lt;a href="#popup" class="yBox <b>my-link</b>"&gt;The link&lt;/a&gt;</code><br />
						<code>&lt;script&gt; yBox({ self: $('.my-link') }); &lt;/script&gt;</code>
					</td>
				</tr>
				<tr>
					<td>yBoxClass</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Added to &lt;div class="yBoxFrame"&gt; in yBox window<br />
						<code>yBox({ yBoxClass: 'my-class' });</code>
					</td>
				</tr>
				<tr>
					<td>url</td>
					<td class="hide-on-tablet">:</td>
					<td>
						When calling to element from java script.<br />
						<code>&lt;div id="my-popup"&gt; &lt;/div&gt;</code><br />
						<code>&lt;script&gt; yBox({ url: '#my-popup' }); &lt;/script&gt;</code>
					</td>
				</tr>
				<tr>
					<td>https://domain.com<b>?msg=</b>Some text</td>
					<td class="hide-on-tablet">:</td>
					<td>msg parameter in url pop the yBox with your text.</td>
				</tr>
				<tr>
					<td>https://domain.com<b>?ybox-url</b>=my-popup</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Call to element from URL address<br />
						<code>&lt;div id="my-popup"&gt; &lt;/div&gt;</code>
					</td>
				</tr>
				<tr>
					<td>https://domain.com<b>?ybox-class</b>=my-popup-class</td>
					<td class="hide-on-tablet">:</td>
					<td>add class to yBox window from URL address</td>
				</tr>
				<tr>
					<td>function beforeYboxOpen(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function before opening yBox<br />
						self = The yBox button
					</td>
				</tr>
				<tr>
					<td>function afterYboxOpen(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function after opening yBox<br />
						self = The yBox button
					</td>
				</tr>
				<tr>
					<td>function beforeYboxClose(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function before closing yBox<br />
						self = The yBox button
					</td>
				</tr>
				<tr>
					<td>function afterYboxClose(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function after yBox closed<br />
						self = The yBox button
					</td>
				</tr>
			</table>
		</section>
    
![screenshot](https://user-images.githubusercontent.com/110046564/190384617-3a205b43-e050-4ff9-afac-40aed3b121f8.png)
<!DOCTYPE HTML>
<html lang="en-US">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=1" />
	<title>yBox</title>
	<link rel="stylesheet" href="demo_files/demo.css" />
	<script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
</head>
<body>
	<main>
		<section>
			<h3>Files</h3>
			<pre>
				<code><span class="blue">&lt;link</span> <span class="red">rel</span><span class="purple">="stylesheet"</span> <span class="red">href</span><span class="purple">="dist/css/ybox.min.css"</span> <span class="blue">/&gt;</span>
<span class="blue">&lt;script</span> <span class="red">type</span><span class="purple">="text/javascript"</span> <span class="red">src</span><span class="purple">="dist/js/directive.min.js"</span><span class="blue">/&gt;</span></script>
<span class="blue">&lt;script</span> <span class="red">type</span><span class="purple">="text/javascript"</span> <span class="red">src</span><span class="purple">="dist/js/ybox.min.js?lang=he"</span><span class="blue">/&gt;</span></script></code>
			</pre>
		</section>
		<section>
			<h3>All parameters</h3>
			<table border="0" cellpadding="10" cellspacing="0" width="100%" style="line-height:24px;">
				<tr>
					<td width="360">code</td>
					<td width="25" class="hide-on-tablet">:</td>
					<td>
						When calling to yBox from your Java Script, you can write your HTML code<br />
						<code>yBox({ code: '&lt;div class="my-class"&gt;Some text&lt;/div&gt;' });</code>
					</td>
				</tr>
				<tr>
					<td>self</td>
					<td class="hide-on-tablet">:</td>
					<td>
						<code>
							&lt;a href="#popup" class="yBox <b>my-link</b>"&gt;The link&lt;/a&gt;<br />
							yBox({ self: jQuery('.my-link') });
						</code>
					</td>
				</tr>
				<tr>
					<td>yBoxClass</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Added to &lt;div class="yBoxFrame"&gt; in yBox window<br />
						<code>yBox({ yBoxClass: 'my-class' });</code>
					</td>
				</tr>
				<tr>
					<td>url</td>
					<td class="hide-on-tablet">:</td>
					<td>
						When calling to element from java script.<br />
						<code>&lt;div id="my-popup"&gt; &lt;/div&gt;</code><br />
						<code>&lt;script&gt; yBox({ url: '#my-popup' }); &lt;/script&gt;</code>
					</td>
				</tr>
				<tr>
					<td>https://domain.com<b>?msg=</b>Some text</td>
					<td class="hide-on-tablet">:</td>
					<td>msg parameter in url pop the yBox with your text.</td>
				</tr>
				<tr>
					<td>https://domain.com<b>?ybox-url</b>=my-popup</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Call to element from URL address<br />
						<code>&lt;div id="my-popup"&gt; &lt;/div&gt;</code>
					</td>
				</tr>
				<tr>
					<td>https://domain.com<b>?ybox-class</b>=my-popup-class</td>
					<td class="hide-on-tablet">:</td>
					<td>add class to yBox window from URL address</td>
				</tr>
				<tr>
					<td>function beforeYboxOpen(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function before opening yBox<br />
						self = The yBox button -> if no button then it return the div
					</td>
				</tr>
				<tr>
					<td>function afterYboxOpen(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function after opening yBox<br />
						self = The yBox button -> if no button then it return the div
					</td>
				</tr>
				<tr>
					<td>function beforeYboxClose(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function before closing yBox<br />
						self = The yBox button -> if no button then it return the div
					</td>
				</tr>
				<tr>
					<td>function afterYboxClose(self){ ... };</td>
					<td class="hide-on-tablet">:</td>
					<td>
						Calling the function after yBox closed<br />
						self = The yBox button -> if no button then it return the div
					</td>
				</tr>
			</table>
		</section>
		<section>
			<h3>Open yBox on page load</h3>
			<pre>
				<code><span class="blue">&lt;script&gt;</span>
yBox({
    code : <span class="grey">'&lt;div class="my-class"&gt;Some text&lt;/div&gt;'</span>
});
<span class="blue">&lt;/script&gt;</span></code>
			</pre>
		</section>
		<section>
			<h3>Open yBox by calling the element from JavaScript</h3>
			<div style="display:none;">
				<div id="popup" href="#popup">Hello :-)</div>
			</div>
			<pre>
				<code><span class="blue">&lt;div</span> <span class="red">style</span>=<span class="purple">"display:none;"</span><span class="blue">&gt;</span>
   <span class="blue">&lt;div</span> <span class="red">id</span>=<span class="purple">"popup"</span><span class="blue">&gt;</span>Hello :-)<span class="blue">&lt;/div&gt;
&lt;/div&gt;</span>
<span class="blue">&lt;script&gt;</span>
yBox({
    url : <span class="grey">'#popup'</span>
});
<span class="blue">&lt;/script&gt;</span></code>
			</pre>
		</section>
		<section>
			<h3>
				Calling the function before opening yBox<br />
				<span style="font-size:16px;">self = The yBox button</span>
			</h3>
			<pre>
				<code><span class="blue">function</span> beforeYboxOpen(self){ <span class="green">/* Do something before yBox is open */</span> };</code>
			</pre>
			<a href="#link1" class="yBox alertBeforeYbox">Click here for example</a>
		</section>
		<section>
			<h3>
				Calling the function after opening yBox<br />
				<span style="font-size:16px;">self = The yBox button</span>
			</h3>
			<pre>
				<code><span class="blue">function</span> afterYboxOpen(self){ <span class="green">/* Do something after yBox is open */</span> };</code>
			</pre>
			<a href="#link1" class="yBox alertAfterYbox">Click here for example</a>
		</section>
		<section>
			<h3>
				Calling the function before closing yBox<br />
				<span style="font-size:16px;">self = The yBox button</span>
			</h3>
			<pre>
				<code><span class="blue">function</span> beforeYboxClose(self){ <span class="green">/* Do something before yBox is close */</span> };</code>
			</pre>
			<a href="#link1" class="yBox alertBeforeClose">Click here for example</a>
		</section>
		<section>
			<h3>
				Calling the function after yBox closed<br />
				<span style="font-size:16px;">self = The yBox button</span>
			</h3>
			<pre>
				<code><span class="blue">function</span> afterYboxClose(self){ <span class="green">/* Do something after yBox is close */</span> };</code>
			</pre>
			<a href="#link1" class="yBox alertAfterClose">Click here for example</a>
		</section>
		<section>
			<h3>Add "msg" parameter to URL</h3>
			<pre>
				<code>https://www.domain.com/?<span style="color:red;">msg</span>=Some text</code>
			</pre>
		</section>
		<section>
			<h3>Calling to yBox in yBox window</h3>
			<a href="#link1" class="yBox">Click here for example</a>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">#link1</span>"<span class="blue"> <span class="red">class</span>="<span class="purple">yBox</span>"&gt; &lt;/a&gt;</span></code>
			</pre>
			<div style="display:none;">
				<div id="link1">
					<div class="inner" style="width:200px;height:100px">
						Hello
						<div style="padding:20px 0 0 0;">
							<a href="#link2" class="yBox">Click me</a>
						</div>
					</div>
				</div>
			</div>
			<div style="display:none;">
				<div id="link2">Hello again :)</div>
			</div>
		</section>
		<section class="iframeSection">
			<h3>Open Iframe / YouTube / Vimeo with yBox <span class="grey2" style="display:inline-block;direction:ltr;">( class="yBox yBox_iframe" )</span></h3>
			<a href="https://www.youtube.com/watch?v=eEMpCcLm6NI&list=RDeEMpCcLm6NI&start_radio=1" class="yBox yBox_iframe" rel="nofollow" title="Click Here">
				<img id="koko" src="https://img.youtube.com/vi/eEMpCcLm6NI/0.jpg" alt="" width="100" height="100" />
			</a>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">https://www.youtube.com...</span>" <span class="red">class</span>="<span class="purple">yBox yBox_iframe</span>"<span class="blue">&gt; &lt;/a&gt;</span></code>
			</pre>
		</section>
		<section class="iframeSection">
			<h3>Open inner video file <span class="grey2" style="display:inline-block;direction:ltr;">( class="yBox yBox_video" )</span></h3>
			<a href="demo_files/mov_bbb.mp4" class="yBox yBox_video" rel="nofollow" title="Click Here">
				<img id="koko" src="demo_files/movie_img.jpg" alt="" width="100" height="100" />
			</a>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">/path/to/video.mp4</span>" <span class="red">class</span>="<span class="purple">yBox yBox_video</span>"<span class="blue">&gt; &lt;/a&gt;</span></code>
			</pre>
		</section>
		<section>
			<h3>Add different class <span class="grey2" style="display:inline-block;direction:ltr;">( data-ybox-class="my_class" )</span></h3>
			<a href="#myLink" data-ybox-class="myYboxClass" class="yBox">Click here for example</a>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">#myLink</span>" <span class="red">data-ybox-class</span>="<span class="purple">myYboxClass</span>" <span class="red">class</span>="<span class="purple">yBox</span>"<span class="blue">&gt; &lt;/a&gt;</span></code>
			</pre>

			<div style="display:none;">
				<div id="myLink" style="direction:ltr;">
					Hey - look at me!!
				</div> 
			</div> 
		</section>
		<section>
			<h3>Open with AJAX <span class="grey2" style="display:inline-block;direction:ltr;">( class="yBox yBox_ajax" )</span></h3>
			<a href="https://www.google.com" class="yBox yBox_ajax">Click here for example</a>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">https://www.google.com</span>" <span class="red">class</span>="<span class="purple">yBox yBox_ajax</span>"<span class="blue">&gt; &lt;/a&gt;</span></code>
			</pre>
		</section>
		<section>
			<h3>Grouped galleries <span class="grey2" style="display:inline-block;direction:ltr;">( data-ybox-group="group_name" )</span></h3>
			<h4>Group 1</h4>
			You can edit the ALT of the images
			<span class="grey2" style="display:inline-block;direction:ltr;">( data-ybox-alt="Image Alt" )</span>
			<div class="group-wrap">
				<a href="demo_files/1.jpg" class="yBox" data-ybox-alt="Image Alt 1" data-ybox-group="group1">
					<img src="demo_files/1.jpg" alt="" width="200" />
				</a>
				<a href="demo_files/2.jpg" class="yBox" data-ybox-alt="Image Alt 2" data-ybox-group="group1">
					<img src="demo_files/2.jpg" alt="" width="200" />
				</a>
				<a href="demo_files/3.jpg" class="yBox" data-ybox-alt="Image Alt 3" data-ybox-group="group1">
					<img src="demo_files/3.jpg" alt="" width="200" />
				</a>
			</div>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">image.jpg</span>" <span class="red">data-ybox-group</span>="<span class="purple">group1</span>" <span class="red">data-ybox-alt</span>="<span class="purple">Image Alt</span>" <span class="red">class</span>="<span class="purple">yBox</span>"<span class="blue">&gt; &lt;/a&gt;</span></code>
			</pre>
			<h4>Group 2</h4>
			<div class="group-wrap">
				<a href="demo_files/4.jpg" class="yBox" data-ybox-group="group2">
					<img src="demo_files/4.jpg" alt="" width="200" />
				</a>
				<a href="demo_files/5.jpg" class="yBox" data-ybox-group="group2">
					<img src="demo_files/5.jpg" alt="" width="200" />
				</a>
				<a href="https://www.youtube.com/watch?v=c7ZZ04Yo7lw" class="yBox yBox_iframe" data-ybox-alt="Image Alt 3" data-ybox-group="group2">
					<img src="demo_files/video-img.jpg" alt="" width="200" />
					<div class="play"></div>
				</a>
			</div>
			<pre> 
				<code><span class="blue">&lt;a</span> <span class="red">href</span>="<span class="purple">image.jpg</span>" <span class="red">data-ybox-group</span>="<span class="purple">group2</span>" <span class="red">class</span>="<span class="purple">yBox</span>"<span class="blue">&gt; &lt;/a&gt;</span></code>
			</pre>
		</section>
	</main>

<link rel="stylesheet" href="dist/css/ybox.min.css" />
<script type="text/javascript" src="dist/js/directive.min.js"></script>
<script type="text/javascript" src="dist/js/ybox.js?lang=en"></script>

<script type="text/javascript">
function beforeYboxOpen(self){
	if ( self.hasClass('alertBeforeYbox') ) {
		alert('Before yBox open');
	}
};
function afterYboxOpen(self){
	if ( self.hasClass('alertAfterYbox') ) {
		alert('After yBox open');
	}
};
function beforeYboxClose(self){
	if( self.hasClass('alertBeforeClose') ) {
		let confirmAction = confirm("Are you sure you want to close yBox?");
        if ( ! confirmAction ) {
			return false;
		}
	}
};
function afterYboxClose(self){
	if ( self.hasClass('alertAfterClose') ) {
		alert('After yBox close');
	}
};
</script>

</body>
</html>
