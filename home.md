---
layout: default
---

<meta name="google-site-verification" content="Ay7DuHomj_FffCIPkk06PMst9-V1kwZij44bLz5SeuI" />
    
   <!-- Global site tag (gtag.js) - Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=UA-178685535-2"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());   </script>
     <script async defer src="https://buttons.github.io/buttons.js"></script>

 <section id="downloads">
	<button style="border-radius: 4px;
	padding: 1px;
	font-size: 13px;
	border: none;
	vertical-align: top;
	margin-top: 12px;
	background-color: #F5F5F5;">   <a href="https://chrome.google.com/webstore/detail/fragmentqr/cabodnfakameckfbbgkciiifempglloj" class="btn" title="Get it on the Chrome Web Store" padding="0">
   <img src="https://developer.chrome.com/webstore/images/ChromeWebStore_Badge_v2_496x150.png" height="42px" alt="Available on the Chrome Webstore"></a></button>
   <button style="border-radius: 4px;
	background: #f0f8ff;
	padding: 15px;
	font-size: 17px;
	border: none;
	vertical-align: top;
	margin-top: 12px;
	background-color: #F5F5F5;"><a style="color: black;" class="btn" href="https://github.com/y330/FragmentQR/issues" rel="noopener" target="_blank" aria-label="Issues y330/FragmentQR on GitHub"> <svg viewBox="0 0 16 16" width="14" height="14" class="octicon octicon-issue-opened" aria-hidden="true"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"></path></svg> <span>Issue</span></a></button>
 <iframe src="https://ghbtns.com/github-btn.html?user=y330&repo=FragmentQR&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub">
 </iframe>
 <iframe src="https://ghbtns.com/github-btn.html?user=y330&repo=FragmentQR&type=watch&count=true&v=2" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"> </iframe>

 </section>
 
<!-- Place this tag where you want the button to render. -->


<style>h1{color: orange;} sup:hover{background-color: yellow; color: orange;} </style>

# FragmentQR

<em><b>Coded by Yonah Aviv</b></em>


**FragmentQR is a web extension that generates QR codes linking to Text Fragments<sup>[1](#myfootnote1)</sup> from selected text on any webpage.**


When scanning such a QR code, the text fragment will be scrolled into view and/or highlighted in yellow when opened, depending on the browser and/or platform.

<hr>

## Tutorial

<a href="https://bit.ly/GetFragmentedQR" title="View this as a sideshow on the Chrome Web Store"><img src="https://lh3.googleusercontent.com/pw/ACtC-3f7FGuESSm9z3SPDAbhQHSr3YYL03r1gGBeSWYqbG8NyXxtg3gMWO4dbrM8yuhsMsCuf_JLqLSUWfSSodKzYR8mg6FkX5PmxXgfG8iPANMsQpsiE6GTlWFIRsHIZqi2ZBX0btMnBlUltWArYFdlTrhbhQ=w1210-h448-no?authuser=0" width="fit-content" alt="FragmentQR infographic of intructions"/></a>

To learn how to QR encode text fragments using FragmentQR, you can examine the infographic above. Alternatively, read the instructions below:
 <hr style="width:70%; align: middle;">

### Instructions

 <ol>
  <li>Select text</li>
  <li>Ctrl/Cmd + Shift + L to copy the text fragment. Wait for your selected text fragment be highlighted in yellow.</li>
  <li>Ctrl/Cmd+Q to open the extension popup</li>
  <li>Click the paste button</li>
  <li>Scan it on your mobile device using a QR code scanner such as Google Lens or some default camera apps. Check compatible browsers in the FAQ.</li>
 </ol>
 
 If steps 1 or 2 do not work, go to chrome://extensions/shortcuts to reconfigure the shortcuts
 
 <hr width="70%">
 

### Demo of FragmentQR v1.0.0(Old)

[
![
](https://lh3.googleusercontent.com/pw/ACtC-3cera_XKIXLjEw9LyZh93DtSKTDoQsyF2aYR0Y_L-PCeMttnP3Gr1OiOIxL4nLN_ltCioZyQMUwizFb2wyZLzytBktmEuWRptUGYOFoChSq_bQpZ_g5TEnbb_ZG__Y0rjNbj2oUiHBPotXUOP6X2NID3g=w212-h112-no?)
](http://bit.ly/youtubeFragQR)

## FAQ


### **What are Text Fragments?**

<block class="fragd"><a class="foot" name="myfootnote1"><sup>[1]</sup></a> Text Fragment: Part of a URL that specifies a piece of text to be scrolled into view and highlighted in yellow. 
</block>

>    "Text Fragments let you specify a text snippet in the URL fragment. When navigating to a URL with such a text fragment, the browser can emphasize and/or bring it to the user's attention." web.dev	

- <p>
  <details>
    <summary>Click this to collapse/fold the technical definition.</summary> 
            A text fragment is a part of a URL defined in a URI fragment <code>your-url/#URI-fragment</code>
   after the <code>#</code> that defines a text snippet. The syntax for a text fragment is  <code>your-url/#:~:text=text-snippet</code> with the specific text specified after    <code>:~:text=</code>.
  </details>
  </p>

Example:

>[https://en.wikipedia.org/wiki/Table_of_keyboard_shortcuts?oldformat=true#Comparison_of_keyboard_shortcuts:~:text=Keyboard%20
shortcuts%20are%20a%20common%20aspect%20of%20most%20modern%20operating%20systems](https://en.wikipedia.org/wiki/Table_of_keyboard_shortcuts?oldformat=true#Comparison_of_keyboard_shortcuts:~:text=Keyboard%20shortcuts%20are%20a%20common%20aspect%20of%20most%20modern%20operating%20systems)

 In Chromium 80+, this feature is known as <a href="https://github.com/WICG/scroll-to-text-fragment/" title="Scroll-to-Text Fragment on GitHub">Scroll-to-Text Fragment</a>.

 


### **What will FragmentQR do for me?**

- **FragmentQR**  uses the idea of Scroll-to-Text Fragment, and can enable you to select any text, and press `⇧ + ⌘ + L` or `Ctrl + Shift + L`
to copy it as a text fragment. You can then press `⌘ + Q` or `Ctrl + Q` to open the extension popup and generate a QR code from your clipboard. Reference your device below to know if text fragments are supported for you.


### **What browsers/platforms are compatible with FragmentQR?**
- As of 10/02/2020, browsers per platform required to use text fragments are defined in the table below. I would like to point out that Chromium 80 is the bear minimum for all devices in order to use text fragments with the intended functionality.
<hr width="25%" color="orange">

|OS |Minimum Browser Version|
|--|--|
|Android 5.5 or later|Chrome 85, Android WebView 81|
|Windows 7 or later|Chromium 80|
|Mac OS X 10.10 or later|Chromium 80|
|iOS 12|Coming soon, but in Chrome for iOS enabling #shared-highlighting-ios on chrome://flags allows scrolling to the fragment. The availability on iOS is up to Apple as Chrome for iOS uses Apple WebKit.|

<a href="https://caniuse.com/url-scroll-to-text-fragment#tab-container:~:text=content%2Dvisibility-,Can%20I%20use" title="Check compatability of scroll to text fragment" target="_blank">Check current status</a>

-----


### <em>Changelog v1.6</em>

<ol>
    <li>Fix issue when system theme is set to light</li>
    <li>Minor improvements</li>
  
</ol>
  
---- 
### <em>Changelog v1.5</em>

 <ol>  
  <li>New icon and name changes to FragmentQR</li>
  <li>Paste button now works.</li>
  <li>Vast UI and functionality improvements</li>
  <li>Added support for copying text framents</li>
  <li>Added keyboard shortcuts</li>
  <li>Light theme(currently does not save between sessions)</li>
 </ol>
 
 -----
 
### TODO

  - [ ] add keyboard shorcut to open popup with link to text fragment as a placeholder in the textarea
  
----
----

 
FragmentQR uses Scroll to Text Fragment, a feature in Chromium 80+. 


<b>© 2020 MIT license Yonah Aviv.</b>


Contributions and Donations welcome.


<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=CBYMNSA8XYYY2&item_name=To+continue+doing+whatever+I+am+doing&currency_code=CAD&source=url"><img src="https://camo.githubusercontent.com/d5d24e33e2f4b6fe53987419a21b203c03789a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d677265656e2e737667" /></a>