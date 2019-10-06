# MediaWiki-Template-V1<br><br>
Customized Template for MediaWiki by customizing the Pivot Responsive template. https://github.com/Hutchy68/pivot/<br><br><br>
<img src="https://live.staticflickr.com/1895/43667601755_2ec3dd1274_h.jpg">


<br><br><article class="markdown-body entry-content p-5" itemprop="text"><h1><a id="user-content-mediawiki-pivot-skin" class="anchor" aria-hidden="true" href="#mediawiki-pivot-skin"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>How to use original MediaWiki Pivot Skin</h1>
<p><a href="https://travis-ci.org/Hutchy68/pivot" rel="nofollow"><img src="https://camo.githubusercontent.com/60775f8ef16aeb49e65091486a48166cb6ef3766/68747470733a2f2f7472617669732d63692e6f72672f48757463687936382f7069766f742e7376673f6272616e63683d6d6173746572" alt="Build Status" data-canonical-src="https://travis-ci.org/Hutchy68/pivot.svg?branch=master" style="max-width:100%;"></a>
<a href="https://scrutinizer-ci.com/g/Hutchy68/pivot/?branch=master" rel="nofollow"><img src="https://camo.githubusercontent.com/996e7c358a68b9d83beb2319ae3980fe20bd6f67/68747470733a2f2f7363727574696e697a65722d63692e636f6d2f672f48757463687936382f7069766f742f6261646765732f7175616c6974792d73636f72652e706e673f623d6d6173746572" alt="Scrutinizer Code Quality" data-canonical-src="https://scrutinizer-ci.com/g/Hutchy68/pivot/badges/quality-score.png?b=master" style="max-width:100%;"></a></p>
<p>A <a href="http://www.mediawiki.org" rel="nofollow">MediaWiki</a> skin that focuses on mobile first but will pivot to all viewports with elegance. Supports responsive layouts and has classes predefined for <a href="http://semantic-mediawiki.org/wiki/Semantic_MediaWiki" rel="nofollow">Semantic MediaWiki</a>. Built on the <a href="http://foundation.zurb.com" rel="nofollow">Zurb Foundation 5</a> CSS framework.</p>
<h2><a id="user-content-download" class="anchor" aria-hidden="true" href="#download"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Download</h2>
<p>First, copy the Pivot source files into your MediaWiki skins directory (see <a href="https://www.mediawiki.org/wiki/Manual:Skinning" rel="nofollow">skinning</a> for general information on MediaWiki skins). You can either download the files and extract them from:</p>
<pre><code>https://github.com/hutchy68/pivot/archive/master.zip
</code></pre>
<p>You should extract that into a folder named <code>pivot</code> in your <code>skins</code> directory.</p>
<p>Alternatively, you can use git to clone the repository, which makes it very easy to update the code, using:</p>
<pre><code>git clone https://github.com/hutchy68/pivot.git
</code></pre>
<p>After that, you can issue <code>git pull</code> to update the code at anytime.</p>
<h2><a id="user-content-setup" class="anchor" aria-hidden="true" href="#setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Setup</h2>
<p>Once the skin is in place add the following line to your <code>LocalSettings.php</code> file.</p>
<pre><code>wfLoadSkin( 'pivot' );
</code></pre>
<p>This will activate Pivot in your installation. At this point you can select it as a user skin in your user preferences.</p>
<p>To activate Pivot for all users and anonymous visitors, you need to set the <code>$wgDefaultSkin</code> variable and set it to <code>pivot</code>.</p>
<pre><code>$wgDefaultSkin = "pivot";
</code></pre>
<h2><a id="user-content-configurations" class="anchor" aria-hidden="true" href="#configurations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Configurations</h2>
<p>Use following features in <code>LocalSettings.php</code> to change the behavior.</p>
<ul>
<li><code>'showActionsForAnon' =&gt; true</code> displays page actions for non-logged-in visitors.</li>
<li><code>'fixedNavBar' =&gt; false</code> will allow the NavBar to scroll with the content, <code>true</code> will lock the NavBar.</li>
<li><code>'usePivotTabs' =&gt; false</code> set to true to enable Foundation tabs markup in wiki pages.</li>
<li><code>'showHelpUnderTools' =&gt; true</code> a Link to "Help" will be created under "Tools".</li>
<li><code>'showRecentChangesUnderTool's =&gt; true</code> a Link to "recent changes" will be created under "Tools".</li>
<li><code>'wikiName' =&gt; &amp;$GLOBALS['wgSitename']</code> default is the sitename. Set to display a short version without changing the systems wikiname.</li>
<li><code>'wikiNameDesktop' =&gt; &amp;$GLOBALS['wgSitename']</code> default sitename. Set to display a longer name in desktop view.</li>
<li><code>'navbarIcon' =&gt; false</code> no icon in mobile view, <code>true</code> to use the global set logopath image of the wiki.</li>
<li><code>'preloadFontAwesome' =&gt; false</code> set to true to preload Font Awesome as a <code>&lt;head&gt;</code> element. Useful to overcome MIME type server configurations not set correctly.</li>
<li><code>'showFooterIcons' =&gt; false</code> will show text in place of footer icons, <code>true</code> will output the icons as globally set.</li>
<li><code>'addThisPUBID' =&gt; ''</code> empty string will not fire the AddThis script, <code>'ra-##-#######'</code> publisher ID will allow the run the AddThis script in async on content pages only.</li>
<li><code>'useAddThisShare' =&gt; ''</code> default empty string, do not use AddThis share, <code>your_addthis_specific_div_class_string</code> will insert the share toolbox div directly under page title, but before the tagline with your custom div class.</li>
<li><code>'useAddThisFollow' =&gt; ''</code> default empty string, do not use AddThis follow, <code>your_addthis_specific_div_class_string</code> will insert the follow toolbox div in the <code>right-footer</code> area before icon or text output with your custom div class.</li>
</ul>
<p>These are the default values and the example of the array to change the defaults. Add the following after <code>wfLoadSkin( 'pivot' );</code> in <code>LocalSettings.php</code> to change the feature defaults:</p>
<pre><code>$wgPivotFeatures = array(
	'showActionsForAnon' =&gt; true,
	'fixedNavBar' =&gt; false,
	'usePivotTabs' =&gt; false,
	'showHelpUnderTools' =&gt; true,
	'showRecentChangesUnderTools' =&gt; true,
	'wikiName' =&gt; &amp;$GLOBALS['wgSitename'],
	'wikiNameDesktop' =&gt; &amp;$GLOBALS['wgSitename'],
	'navbarIcon' =&gt; false,
	'preloadFontAwesome' =&gt; false,
	'showFooterIcons' =&gt; true,
	'addThisPUBID' =&gt; '',
	'useAddThisShare' =&gt; '',
	'useAddThisFollow' =&gt; ''
);
</code></pre>
<h3><a id="user-content-notes-on-other-skins" class="anchor" aria-hidden="true" href="#notes-on-other-skins"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Notes on other skins</h3>
<p>As you build a wiki out with Pivot you will likely use the responsive grid from Foundation. This is key to making a responsive wiki, and is one of the largest <em>migration</em> requirements when you want to move a wiki that previously used Vector (and likely a lot of tables for layout) to Pivot. Once you do this, the ability of a user to select whatever skin will be removed. If you take full advantage of Pivot in your templates the lack of the Foundation grid will make viewing the wiki using <a href="http://wikiapiary.com/wiki/Skin:Vector" rel="nofollow">Vector</a> or <a href="http://wikiapiary.com/wiki/Skin:MonoBook" rel="nofollow">MonoBook</a> very difficult.</p>
<p>Because of this, it is suggested that you set the <code>$wgSkipSkins</code> variable to make sure that everyone sees the site as you intended it. This removes other skins from being user selectable options.</p>
<pre><code># Pivot is specific, so lets disable other skins
$wgSkipSkins = array( 'chick', 'cologneblue', 'modern', 'myskin', 'nostalgia', 'simple', 'standard', 'filament', 'monobook', 'vector' );
</code></pre>
<p>You may also want to allow users to set a User CSS if they want to tweak things inside of Pivot. This is entirely optional.</p>
<pre><code># Allow User CSS, mostly for skin testing
$wgAllowUserCss = true;
</code></pre>
<h2><a id="user-content-using-pivot" class="anchor" aria-hidden="true" href="#using-pivot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using Pivot</h2>
<p>Questions, open an issue in this repo on Github.</p>
</article>
