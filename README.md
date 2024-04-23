- 👋 Hi, I’m @ruk6ana
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ruk6ana/ruk6ana is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
	
	
	<!DOCTYPE html>
	
	
	
	<html lang="en-US">
	
	<head id="ctl00_Head1"><meta charset="utf-8" /><link rel="stylesheet" type="text/css" href="../App_Themes/NextMDBase.css?version=5.2.0" />

	<script type="text/JavaScript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>

	<script type="text/javascript" src="../App_Scripts/jquery.mask.js"></script>

	<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.8.23/jquery-ui.min.js"></script>

	<script type="text/javascript" src="../App_Scripts/AccessibleCalendarAPI.js"></script>

	<script type="text/javascript" src="../App_Scripts/AccessibleCalendar.js"></script>

	<script type="text/javascript" src="../App_Scripts/NextMDScripts.js"></script>

	<script type="text/javascript" src="../App_Scripts/ValidateEmail.js"></script>

	
	<!--[if !IE 7]>
	<style type="text/css">
	#UAcontainer {display:table;height:100%}
	</style>
	<![endif]-->
	<!--[if IE]>
	<style>
	input[type=submit]:focus, input[type=button]:focus { 
	border:1px solid white;
	</style>
	<![endif]-->
	<style>
	@media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
	/* IE10+ CSS styles go here */
	input[type=submit]:focus, input[type=button]:focus {
	border:1px solid white;
	}
	}
	</style>
	<script type="text/javascript">
	$(document).ready(function () {
	
	(function (i, s, o, g, r, a, m) {
	i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () {
	(i[r].q = i[r].q || []).push(arguments)
	}, i[r].l = 1 * new Date(); a = s.createElement(o),
	m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)
	})(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');
	ga('create', 'UA-44873915-6', 'auto');
	ga('send', 'pageview');
	
	SetAsteriskLabelInsideFieldLabel();
	
	//Bottom contents in UAmain div are hidden by the page footer (which is having position fixed)
	//so giving bottom margin equivalent to the footer outerHeight to the UAmain div. 
	$('#UAmain').css('padding-bottom', $('#footer').outerHeight());
	});
	</script>
	
	<title>
	Login - Patient Portal
	</title><link href="../App_Themes/NextMDTheme/jquery.jscrollpane.css" type="text/css" rel="stylesheet" /><link href="../App_Themes/NextMDTheme/jquery-ui.css" type="text/css" rel="stylesheet" /><link href="../App_Themes/NextMDTheme/NextMDStyleSheet.css" type="text/css" rel="stylesheet" /></head>
	
	<body id="ctl00_Body1">
	
	<div id="msgBanner" class="messageBanner posInherit">
	<div id="msgBannerInfo" class="meesageBannerInfo" aria-hidden="true">
	<span id="message"></span>
	</div>
	
	
	<div id="msgBannerInfoEmpty"></div>
	
	<div class="messageBannerClose">
	<a id="btnCloseTopBanner" role="button" aria-label='Close the message' href="javascript:void(0)">

	<img src="../App_Themes/NextMDTheme/Images/banner_close.png" alt='Close the message' aria-hidden="true" />
	</a>
	</div>
	<div class="clearBoth"></div>
	</div>
	
	<form name="aspnetForm" method="post" action="./login.aspx" onsubmit="javascript:return WebForm_OnSubmit();" id="aspnetForm" autocomplete="off">
	<div>
	<input type="hidden" name="__EVENTTARGET" id="__EVENTTARGET" value="" />
	<input type="hidden" name="__EVENTARGUMENT" id="__EVENTARGUMENT" value="" />
	<input type="hidden" name="__LASTFOCUS" id="__LASTFOCUS" value="" />
	<input type="hidden" name="__VIEWSTATE" id="__VIEWSTATE" value="/wEPDwUJNTY5MDM3ODYwDxYCHhNWYWxpZGF0ZVJlcXVlc3RNb2RlAgEWAmYPZBYCAgEPZBYCZg9kFgYCAQ9kFgJmDxYCHgdWaXNpYmxlaGQCAw9kFgYCAQ8PFgIeBFRleHQFvgFUaGUgUGF0aWVudCBQb3J0YWwgd2Vic2l0ZSB3aWxsIGJlIHVuYXZhaWxhYmxlIGZyb20gRnJpZGF5LCBBdWd1c3QgMDUsIDEwOjAwIHAubS4gKEVUKSB0byBTYXR1cmRheSwgQXVndXN0IDA2LCAxMDowMCBhLm0uIChFVCkgZm9yIG1haW50ZW5hbmNlLiAgV2Ugc2luY2VyZWx5IGFwb2xvZ2l6ZSBmb3IgYW55IGluY29udmVuaWVuY2UuZGQCCQ8PFgIeD0N1cnJlbnRBdHRlbXB0c2ZkFgICAQ9kFgZmD2QWBgICD2QWAgIBDw8WAh8CZWRkAgsPDxYCHwJkZGQCEA8PFgIfAgUiQ3VycmVudCB0aW1lOiA0LzEzLzIwMjQgNzo0OToyNiBQTWRkAgEPDxYEHgtOYXZpZ2F0ZVVybAUiaHR0cHM6Ly93d3cubmV4dG1kLmNvbS9PbmxpbmVIZWxwLx4GVGFyZ2V0BQZfYmxhbmtkZAIID2QWBGYPZBYCAgEPZBYCAgEPDxYCHg1BbHRlcm5hdGVUZXh0BQVDbG9zZWRkAgEPZBYCZg9kFgICAQ8PFgIfAgW1A0l0IGhhcyBiZWVuIGtub3duIHRoYXQgc3BhbSBibG9ja2luZyBzb2Z0d2FyZSB1c2VkIGJ5IGVtYWlsIHByb3ZpZGVycyBzdWNoIGFzIEFPTCBhbmQgTmV0emVybyBtYXkgYmUgYmxvY2tpbmcgbGVnaXRpbWF0ZSBlbWFpbHMuICBUbyBlbnN1cmUgdGhhdCB5b3UgYXJlIHJlY2VpdmluZyBQYXRpZW50IFBvcnRhbCBlbWFpbHMgcGxlYXNlIGRvIHRoZSBmb2xsb3dpbmc6PGJyIC8+PGJyIC8+QWRkIE5leHRNRC5jb20gdG8geW91ciBjb250YWN0IGxpc3QsIGFkZHJlc3MgbGlzdCwgc2FmZSBsaXN0LCBvciAiRG8gTm90IEJsb2NrIiBsaXN0LjxiciAvPjxiciAvPklmIHlvdSBhcmUgdXNpbmcgeW91ciBvd24gc3BhbSBmaWx0ZXJpbmcgc29mdHdhcmUsIHBsZWFzZSBiZSBzdXJlIHRoYXQgeW91IGFyZSBub3QgZmlsdGVyaW5nIG91dCBlbWFpbCBmcm9tIE5leHRNRC5jb20uZGQCCg9kFgICCQ8PFgIfBmVkZAIFD2QWFmYPFgIeBXN0eWxlBQ1kaXNwbGF5Om5vbmU7ZAIBDw8WAh8CBSHvv70xOTk2LTIwMjQgTlhHTiBNYW5hZ2VtZW50LCBMTENkZAICDw8WAh8CZWRkAgMPDxYCHwFoZGQCBA8PFgIfAgUGdjUuMy4wZGQCBQ8WAh8BaBYCAgEPDxYCHwFoZGQCBg8WAh8BaBYCAgEPDxYGHwQFJ34vSGVscC9lbi1VUy9OZXh0TURQYXRpZW50VXNlckd1aWRlLnBkZh8FBQZfYmxhbmsfAWhkZAIIDxYCHwFoFgICAQ8PFgYfBAUcaHR0cDovL2dldC5hZG9iZS5jb20vcmVhZGVyLx8FBQZfYmxhbmsfAWhkZAILD2QWBAIBDw8WAh8EBRlodHRwczovL3d3dy5uZXh0bWQuY29tL20vZGQCAw8WAh8BaGQCDA8WAh8BaBYCAgEPDxYGHwQFFn4vVHJvdWJsZXNob290aW5nLmFzcHgfBQUGX2JsYW5rHwFoZGQCDQ8QD2QWAh4KYXJpYS1sYWJlbAUITGFuZ3VhZ2UPFgRmAgECAgIDFgQQBQdFbmdsaXNoBQVlbi1VU2cQBQhFc3Bhw7FvbAUFZXMtTVhnEAUM566A5L2T5Lit5paHBQV6aC1DTmcQBQznuYHpq5TkuK3mlocFBXpoLUhLZxYBZmQYAQUeX19Db250cm9sc1JlcXVpcmVQb3N0QmFja0tleV9fFgEFKWN0bDAwJENvbnRlbnRQbGFjZUhvbGRlcjEkTG9naW4yJGJ0bkNsb3NlAPTvn9AEy6WApwoFb/n1OL1fDpU=" />
	</div>
	
	<script type="text/javascript">
	//<![CDATA[
	var theForm = document.forms['aspnetForm'];
	if (!theForm) {
	theForm = document.aspnetForm;
	}
	function __doPostBack(eventTarget, eventArgument) {
	if (!theForm.onsubmit || (theForm.onsubmit() != false)) {
	theForm.__EVENTTARGET.value = eventTarget;
	theForm.__EVENTARGUMENT.value = eventArgument;
	theForm.submit();
	}
	}
	//]]>
	</script>
	
	
	<script src="/ud2/WebResource.axd?d=izl3u1jkxfOMtofEnAHn9vZZnqTg-hP8_ZidY5uPJM9ND5GluTO7bqjptG1hmxob-gLnw0BAFOaKpy1g0&amp;t=637455983131717566" type="text/javascript"></script>

	
	
	<script src="/ud2/WebResource.axd?d=IHf8-aaIeQMIkYYcFu2T1PrxI0dM2lxCXeOgPnCW7DJxehxqcKGu0NBFAUmUi_QJEgb0c11KlSzJ0iMa6a1XBXFJBlQ1&amp;t=637455983131717566" type="text/javascript"></script>

	<script type="text/javascript">
	//<![CDATA[
	function WebForm_OnSubmit() {
	if (typeof(ValidatorOnSubmit) == "function" && ValidatorOnSubmit() == false) return false;
	return true;
	}
	//]]>
	</script>
	
	<div>
	
	<input type="hidden" name="__VIEWSTATEGENERATOR" id="__VIEWSTATEGENERATOR" value="7776B57C" />
	<input type="hidden" name="__EVENTVALIDATION" id="__EVENTVALIDATION" value="/wEdACBohdeWEAijqdLNQn27YeSPwRnicAGLHKVtWn5XBNfjct2HDrZlYa5MSq4dxcwCajIf0FhYEw8q7XWXbBvFWGxRtQVtALdVSFWQYiSZBPv6BcicghsOVVUp4EdKG/V01ZcXBrk1Uub0z9WUNruiIMK8/A0DQQnej1G7REyUNiXQmlBcAkbYSQ+fvYh5eKD2ielpaABEdDIZeKnJVPk9wfMf5olmJ0HbsMwWr0zlGJ2UZ1UtslkFQ+JVOHyN4uhR5wwYLkpRK0j6dPZ6vRE2/2RypqxY5Gw1uruizXvQPQNLUrjAji25fgrjgt3qN0ZYntR27bWWgUoRUuvm7xxRUw9lpMiCHXA15DyDeBllllHXi3iaB3vWMSXWhhUIkeFXuQKW9c91nW/0rbVpU+plS/hiRmAlSsyCoby5ftELRG09wrc7I/ixT7bTd6VM0rr3Fr92yEtLxjWkQcZt6RDDhA8vz/ZW3kKlV/Eo5Ba+TIrWe74qgmYF0bowXjERq3Uarg/adLHGyw1vvbKEUnqYkSRRY1CHe7gNXaHx8cn0r2e6kk1oxBRznd4c+d3aF1VpbsAgadZ5pjSm6I3sctwNjIPY0oz8FROtqfuL3PHdWIXjIy3saMdx2BHtZMGPhc1Cg4y0cHPY9PhsqytS53lENG8UlUn5vOE2ezqnzWRkda6dxiKIwSs3wU1z327aW2J0wXio3jU7" />
	</div> 
	<div id="UAcontainer">
	<div id="UAmain">
	<div id="UAheader">
	
	
	
	<div id="nx-a-header1">
	
	<div id ="divIBEAppended" style="padding: 10px; border: 1px solid transparent; border-radius: 4px; color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6; font-size:large; text-align:center; display:none">
	You have completed the enrollment process. Welcome to NextGen Patient Portal!
	<button type="button" style="border:none;background-color:inherit;color:lightgray; float:right; font-size:large" onclick ="javascript: handleIBE('0');">x</button>
	</div>
	
	
	
	<div id="dbheader">
	
	<div class="header1"> 
	
	</div>
	<div class="header2">
	
	
	</div>
	</div>
	<input type="hidden" name="ctl00$Header1$IBEAppended" id="ctl00_Header1_IBEAppended" value="0" />
	</div>
	
	<script> 
	
	$(document).ready(function () {
	
	if ($("#ctl00_Header1_IBEAppended").val() == "1") {
	
	$("#divIBEAppended").css("display","block");
	}
	}
	);
	
	function handleIBE(hideshow) {
	$.ajax({
	type: "POST",
	url: "https://www.nextmd.com/ud2/Login/Login.aspx/IBEClose",
	data: JSON.stringify({ show: hideshow }),
	dataType: 'json',
	contentType: 'application/json; charset=utf-8',
	success: function (response) {
	$("#divIBEAppended").css("display", "none");
	
	},
	error: function (errorThrown) {
	$("#divIBEAppended").css("display", "none");
	},
	async: false
	});
	return false;
	}
	
	$("#ctl00_Header1_liAccountSettings").focusout(function () {
	
	var $elem = $(this);
	// let the browser set focus on the newly focused elem before check
	setTimeout(function () {
	if (!$elem.find(':focus').length) { 
	
	$elem.children("a").removeClass("open");
	$elem.children("a").attr('aria-expanded', "false");
	$elem.children("ul").hide();
	}
	}, 0);
	});
	
	$("#appmenu > li").each(function () {
	var submenuLength = $(this).find("ul li").length;
	if (submenuLength == 0) {
	$(this).removeClass("has-submenu");
	$(this).find("a").find("img").remove();
	}
	});
	
	
	$("li.has-submenu > a").each(function () {
	$(this).on("click", function (event) {
	
	if (!$(this).hasClass("open")) {
	$(this).addClass("open");
	$(this).next("ul").show();
	$(this).attr('aria-expanded', "true");
	}
	else {
	$(this).removeClass("open");
	$(this).next("ul").hide();
	$(this).attr('aria-expanded', "false");
	}
	
	event.preventDefault();
	return false;
	});
	});
	
	$("li.has-submenu").each(function () {
	$(this).on("mouseenter", function () {
	
	$(this).children("a").addClass("open");
	$(this).children("ul").show();
	$(this).children("a").attr('aria-expanded', "true");
	});
	
	$(this).on("mouseleave", function (event) {
	
	$(this).children("a").removeClass("open");
	$(this).children("ul").hide();
	$(this).children("a").attr('aria-expanded', "false");
	});
	});
	
	$("#appmenu > li > a").each(function () {
	$(this).focus(function () {
	$(this).parent().prev("li").children("ul").hide();
	
	if ($(this).parent().prev("li").children("a").attr("aria-expanded") == "true") {
	$(this).parent().prev("li").children("a").attr("aria-expanded", "false");
	$(this).parent().prev("li").children("a").removeClass("open");
	}
	
	$(this).parent().next("li").children("ul").hide();
	
	if ($(this).parent().next("li").children("a").attr("aria-expanded") == "true") {
	$(this).parent().next("li").children("a").attr("aria-expanded", "false");
	$(this).parent().next("li").children("a").removeClass("open");
	}
	});
	});
	</script>
	</div> 
	<div id="UAcontent">
	
	<script type="text/javascript">
	$(document).ready(function () {
	$("#msgBanner").hide();
	var verificationStatus = $.trim($('#ctl00_ContentPlaceHolder1_hdnVerificationStatus').val());
	if (verificationStatus.length > 0) {
	var message = "";
	if (verificationStatus == "AccountEmailVerified") {
	message = "We have verified your email. Please log in again.";
	showSuccessFailureMessage(message, "Success");
	}
	if (verificationStatus == "VerificationLinkExpired") {
	message = "Your email validation link has expired. To validate your account email, please login again.";
	showSuccessFailureMessage(message, "Error");
	}
	if (verificationStatus == "InvalidVerificationToken") {
	message = "Your email verification link is invalid.";
	showSuccessFailureMessage(message, "Error");
	}
	if (verificationStatus == "EmailAddressAlreadyUsed") {
	message = "This email address is associated with another existing account. Please use a different email address.";
	showSuccessFailureMessage(message, "Error");
	}
	
	$('#ctl00_ContentPlaceHolder1_hdnVerificationStatus').val('');
	removeQueryString();
	}
	
	//on close hide banner and skiptocontent click
	$("#btnCloseTopBanner, #lnkSkipToContent").click(function () {
	$("#msgBanner").hide();
	
	});
	});
	// Removing account email verification token from querystring
	function removeQueryString() {
	var uri = window.location.toString();
	if (uri.indexOf("?") > 0) {
	var clean_uri = uri.substring(0, uri.indexOf("?"));
	window.history.replaceState({}, document.title, clean_uri);
	}
	}
	</script>
	
	<div id="loginBox"> 
	
	<input name="ctl00$ContentPlaceHolder1$hdnVerificationStatus" type="hidden" id="ctl00_ContentPlaceHolder1_hdnVerificationStatus" />
	
	<div id="ctl00_ContentPlaceHolder1_welcomeMessageContainer" class="welcomeMessageContainer">
	<div>
	<span id="ctl00_ContentPlaceHolder1_lblWelcomeMessage" class="welcomeMessage">Welcome to Patient Portal, Your Medical Home on the Web</span>
	</div>
	<div class="marginTop10px">
	<span id="ctl00_ContentPlaceHolder1_lblWelcomeMessageDescription" class="welcomeMessageDescription">With Patient Portal, you can connect with your doctor through a convenient, safe and secure environment.</span>
	</div>
	</div>
	
	
	<div class="innerDiv" id="innerDiv">
	
	<div class="divTopImage">
	<a href="#" id="ctl00_ContentPlaceHolder1_leftLink" target="_blank" title="left link" style="display:none;">
	<img src="../App_Images/spacer.gif" alt="" style="border:0;height:0; width:0; visibility:hidden" /><strong>left link</strong>
	<!-- <img src="../App_Themes/Ardent/Images/PayBill.jpg" alt="Pay Your Bill Online" border="0" class="loginImage"/>-->
	<!-- <img src="../App_Themes/Ardent/Images/FAQ.jpg" alt="Pay Your Bill Online" border="0" class="loginImage"/> -->
	</a>
	</div>
	
	<div class="divTopImage">
	<a href="#" id="ctl00_ContentPlaceHolder1_faqlink" target="_blank" style="display:none;">

	<img src="../App_Images/spacer.gif" alt="" style="border:0;height:0; width:0;" /><strong>FAQ link</strong>
	<!--<img src="../App_Themes/Ardent/Images/PayBill.jpg" alt="Pay Your Bill Online" border="0" class="loginImage"/>-->
	</a>
	</div>
	
	<div class="divTopImage">
	<a href="#" id="ctl00_ContentPlaceHolder1_link2" target="_blank" style="display:none;">

	<img src="../App_Images/spacer.gif" alt="" style="border:0;height:0; width:0;" /><strong>link</strong>
	<!-- <img src="../App_Themes/Ardent/Images/FAQ.jpg" alt="Pay Your Bill Online" border="0" class="loginImage"/> -->
	</a>
	</div> 
	
	<div class="divTopImage">
	<a href="#" id="ctl00_ContentPlaceHolder1_rightLink" target="_blank" title="right link" style="display:none;">
	<img src="../App_Images/spacer.gif" alt="" style="border:0;height:0; width:0;" /><strong>right link</strong>
	<!--<img src="../App_Themes/Ardent/Images/FAQ.jpg" alt="Pay Your Bill Online" border="0" class="loginImage"/> -->
	</a>
	</div>
	</div>
	
	
	<div id="loginPageMsg" class="loginSessionExpired sessionExpired">
	
	</div>
	<div class="loginControl">
	
	<script type="text/javascript" src="../App_Scripts/jquery.watermark.min.js"></script>

	<script type="text/javascript">
	
	function areCookiesEnabled() {
	var cookieEnabled = navigator.cookieEnabled;
	var lblID = 'ctl00_ContentPlaceHolder1_Login2_lblCookiesFlag';
	var label = document.getElementById(lblID);
	
	// When cookieEnabled flag is present and false then cookies are disabled.
	if (cookieEnabled === false) {
	label.style.display = 'block'; //show Please enable cookies message 
	return false;
	}
	
	// try to set a test cookie if we can't see any cookies and we're using 
	// either a browser that doesn't support navigator.cookieEnabled
	// or IE (which always returns true for navigator.cookieEnabled)
	if (!document.cookie && (cookieEnabled === null || /*@cc_on!@*/false)) {
	document.cookie = "testcookie=1";
	
	if (!document.cookie) {
	label.style.display = 'block'; //show Please enable cookies message 
	return false;
	} else {
	document.cookie = "testcookie=; expires=" + new Date(0).toUTCString();
	}
	}
	
	return true;
	}
	</script>
	
	<script type="text/javascript">
	$(document).ready(function ($) {
	
	OnErrorDescribedByChromeVoxFix();
	
	$('#ctl00_ContentPlaceHolder1_Login2_txtUserName').watermark($('#ctl00_ContentPlaceHolder1_Login2_ut').val());
	$('#ctl00_ContentPlaceHolder1_Login2_txtPassword').watermark($('#ctl00_ContentPlaceHolder1_Login2_pt').val());
	
	if ($("#ctl00_ContentPlaceHolder1_Login2_lblErrorMessage").text() != "") {
	var isPIEMessage = $.trim($("#ctl00_ContentPlaceHolder1_Login2_hdnIsPIEMessage").val());
	if (isPIEMessage != 'Yes') {
	$('#ctl00_ContentPlaceHolder1_Login2_txtUserName').addClass("errorControl");
	$('#ctl00_ContentPlaceHolder1_Login2_txtPassword').addClass("errorControl");
	}
	}
	
	var contentWidth = $('#divnewEnrollmentContainer').width() + 110; 
	$('#ctl00_ContentPlaceHolder1_Login2_divfraudWarning').width(contentWidth);
	})
	
	function hasElementId(elem, ID) {
	var elementId = $(elem).attr("id");
	if (elementId != undefined && elementId != null) {
	return elementId.toString().endsWith(ID);
	}
	return false;
	}
	</script>
	<script type="text/javascript">
	<!--
	function setTimezone() {
	
	var rightNow = new Date();
	var date1 = new Date(rightNow.getFullYear(), 0, 1, 0, 0, 0, 0);
	var date2 = new Date(rightNow.getFullYear(), 6, 1, 0, 0, 0, 0);
	var temp = date1.toGMTString();
	var date3 = new Date(temp.substring(0, temp.lastIndexOf(" ") - 1));
	var temp1 = date2.toGMTString();
	var date4 = new Date(temp.substring(0, temp.lastIndexOf(" ") - 1));
	var hoursDiffStdTime = (date1 - date3) / (1000 * 60 * 60);
	if (hoursDiffStdTime > 0) hoursDiffStdTime = "+" + hoursDiffStdTime;
	var hoursDiffDaylightTime = (date2 - date4) / (1000 * 60 * 60);
	/*if (hoursDiffDaylightTime == hoursDiffStdTime) { 
	alert("Time zone is GMT " + hoursDiffStdTime + ".\nDaylight Saving Time is NOT observed here.");
	} else {
	alert("Time zone is GMT " + hoursDiffStdTime + ".\nDaylight Saving Time is observed here.");
	} */
	document.getElementById("ctl00_ContentPlaceHolder1_Login2_visiterTimeZone").value = "GMT " + hoursDiffStdTime;
	
	}
	// -->
	function Clear() {
	if ($.browser.msie) {
	document.getElementById("ctl00_ContentPlaceHolder1_Login2_txtUserName").value = "";
	}
	}
	
	//Login button validation
	function btnLogin() {
	
	var isValid = Page_ClientValidate();
	
	if (isValid) {
	ClearRedBorder();
	}
	else {
	
	OnErrorApplyRedBorder(); 
	
	$("#ctl00_ContentPlaceHolder1_Login2_lblErrorMessage").hide();
	
	//For this page the fields will be invalid only when they are empty
	if ($.trim($("#ctl00_ContentPlaceHolder1_Login2_txtUserName").val()) == "") { //username field is empty
	$("#ctl00_ContentPlaceHolder1_Login2_txtUserName").attr("aria-describedby", "ctl00_ContentPlaceHolder1_Login2_vldSummary_Login");
	$("#ctl00_ContentPlaceHolder1_Login2_txtPassword").removeAttr("aria-describedby");
	}
	else { //password field is empty
	$("#ctl00_ContentPlaceHolder1_Login2_txtUserName").removeAttr("aria-describedby");
	$("#ctl00_ContentPlaceHolder1_Login2_txtPassword").attr("aria-describedby", "ctl00_ContentPlaceHolder1_Login2_vldSummary_Login");
	}
	}
	}
	function TextBoxesInput(sender, args) {
	
	var v = document.getElementById('ctl00_ContentPlaceHolder1_Login2_txtUserName').value;
	var x = document.getElementById('ctl00_ContentPlaceHolder1_Login2_txtPassword').value;
	
	if (v == '' || x == '') {
	args.IsValid = false; // both fields are 
	OnErrorApplyRedBorder();
	}
	else {
	args.IsValid = true;
	}
	
	}
	</script>
	
	<input name="fkPwrd" style="display: none;" type="password" title="password" />
	
	<input name="ctl00$ContentPlaceHolder1$Login2$cltOffset" type="hidden" id="ctl00_ContentPlaceHolder1_Login2_cltOffset" value="red" style="display: none" />
	<div style="clear: both"></div>
	
	<div id="ctl00_ContentPlaceHolder1_Login2_Step_LoginPassword">
	
	
	<!--LOGIN BOX-->
	<div id="boxLogin" class="formBox">
	
	<div id="ctl00_ContentPlaceHolder1_Login2_divloginbox">
	<h1 class="h1">
	<span id="ctl00_ContentPlaceHolder1_Login2_lblHeading">Log into Patient Portal</span>
	</h1> 
	
	
	<div class="pushMoreT30">
	<div style="position:relative;">
	
	<div id="ctl00_ContentPlaceHolder1_Login2_vldSummary_Login" class="fontValidation validationsummaryIcon" style="color:Red;display:none;">
	
	</div>
	</div>
	<div id="ctl00_ContentPlaceHolder1_Login2_divLoginError">
	<span id="ctl00_ContentPlaceHolder1_Login2_lblErrorMessage" class="fontValidation" style="display:inline-block;width:100%;"></span>
	</div>
	</div>
	
	<div class="label">
	<label for="ctl00_ContentPlaceHolder1_Login2_txtUserName" id="ctl00_ContentPlaceHolder1_Login2_lblUserName">Username</label>
	</div>
	<div>
	
	<input name="ctl00$ContentPlaceHolder1$Login2$txtUserName" type="text" maxlength="50" id="ctl00_ContentPlaceHolder1_Login2_txtUserName" class="txtBox" onclick="Clear();" autocomplete="off" aria-required="true" />
	</div>
	
	<div class="pushLessT">
	<span id="ctl00_ContentPlaceHolder1_Login2_rfvUserName" class="fontValidation" style="display:none;"></span>
	</div>
	<div>
	<a id="ctl00_ContentPlaceHolder1_Login2_lnkForgotUsername" class="fontStandardLink2" href="javascript:__doPostBack(&#39;ctl00$ContentPlaceHolder1$Login2$lnkForgotUsername&#39;,&#39;&#39;)">Forgot username?</a>

	
	</div>
	<div class="label">
	<label for="ctl00_ContentPlaceHolder1_Login2_txtPassword" id="ctl00_ContentPlaceHolder1_Login2_lblPassword">Password</label>
	</div>
	<div>
	
	<input name="ctl00$ContentPlaceHolder1$Login2$txtPassword" type="password" maxlength="200" id="ctl00_ContentPlaceHolder1_Login2_txtPassword" class="txtBox" aria-required="true" />
	</div>
	<div class="pushLessT">
	<span id="ctl00_ContentPlaceHolder1_Login2_rfvPassword" class="fontValidation" style="display:none;"></span>
	</div>
	<div> 
	
	
	
	<div>
	<a id="ctl00_ContentPlaceHolder1_Login2_lnkForgotPassword" class="fontStandardLink2" href="javascript:__doPostBack(&#39;ctl00$ContentPlaceHolder1$Login2$lnkForgotPassword&#39;,&#39;&#39;)">Forgot password?</a> 

	</div>
	
	<div class="havingTrouble">
	<span id="ctl00_ContentPlaceHolder1_Login2_lblHavingTrouble"></span>
	</div>
	</div>
	<div class="pushMoreT30">
	<input type="submit" name="ctl00$ContentPlaceHolder1$Login2$btnLogin1" value="Log In" onclick="setTimezone();btnLogin();WebForm_DoPostBackWithOptions(new WebForm_PostBackOptions(&quot;ctl00$ContentPlaceHolder1$Login2$btnLogin1&quot;, &quot;&quot;, true, &quot;&quot;, &quot;&quot;, false, false))" id="ctl00_ContentPlaceHolder1_Login2_btnLogin1" class="fontStandardButton LoginPageButton" style="height:45px;width:100%;" />
	</div>
	
	<div class="pushLessT">
	<a id="ctl00_ContentPlaceHolder1_Login2_lnkHavePasswordResetToken" class="fontStandardLink2" href="javascript:__doPostBack(&#39;ctl00$ContentPlaceHolder1$Login2$lnkHavePasswordResetToken&#39;,&#39;&#39;)">I have my password reset token</a>

	</div>
	<div class="pushMoreT30">
	<h2 class="lineHeading">
	<span id="ctl00_ContentPlaceHolder1_Login2_Label1" class="bodyTxt">I am new here</span>
	</h2>
	</div>
	<div class="txtC pushMoreT30">
	<a onclick="setTimezone();" id="ctl00_ContentPlaceHolder1_Login2_lnkCreateAccount" class="linkBig" href="javascript:__doPostBack(&#39;ctl00$ContentPlaceHolder1$Login2$lnkCreateAccount&#39;,&#39;&#39;)">CREATE ACCOUNT</a>

	</div>
	
	<div style="display: inline;">
	<span id="ctl00_ContentPlaceHolder1_Login2_lblServertime" style="display: none">Current time: 4/13/2024 7:49:26 PM</span>
	</div>
	<div class="divErrorblock">
	<span id="ctl00_ContentPlaceHolder1_Login2_lblCookiesFlag" class="fontErrorMessage" style="display: none">Your browser's cookie functionality is turned off. Please turn it on.</span>
	</div>
	</div> 
	<div id="divOnlineHelp">
	<a id="ctl00_ContentPlaceHolder1_Login2_lnkOnlineHelp" title="Opens a new window" class="fontStandardLink1" href="https://www.nextmd.com/OnlineHelp/" target="_blank">Online Patient Portal Help</a>
	</div>
	</div>
	<div style="clear: both"></div>
	
	<div class="clear"></div>
	<input name="ctl00$ContentPlaceHolder1$Login2$visiterTimeZone" type="hidden" id="ctl00_ContentPlaceHolder1_Login2_visiterTimeZone" style="display: none" />
	<input name="ctl00$ContentPlaceHolder1$Login2$isMobile" type="hidden" id="ctl00_ContentPlaceHolder1_Login2_isMobile" style="display: none" />
	<input name="ctl00$ContentPlaceHolder1$Login2$ut" type="hidden" id="ctl00_ContentPlaceHolder1_Login2_ut" value="Username" />
	<input name="ctl00$ContentPlaceHolder1$Login2$pt" type="hidden" id="ctl00_ContentPlaceHolder1_Login2_pt" value="Password" />
	<input name="ctl00$ContentPlaceHolder1$Login2$hdnIsPIEMessage" type="hidden" id="ctl00_ContentPlaceHolder1_Login2_hdnIsPIEMessage" />
	
	
	
	<div id="divAlertEmails" class="pushMoreT30">
	<span class="fontStandardLabel">
	<a id="lnkemail" class="fontStandardLink1" href="#" onclick="popupOpen();popUp('lnkemail',event,'t4','ctl00_ContentPlaceHolder1_Login2_btnClose');return false;">
	<span id="ctl00_ContentPlaceHolder1_Login2_Label2">I am not receiving email notifications</span></a></span>
	</div>
	
	<!--EMAILS pop up -->
	<div id="t4" class="floatingPopup" role="dialog" aria-labelledby="ctl00_ContentPlaceHolder1_Login2_lblEmails" aria-describedby="divemails" style="left: 200px; top: 393px; display: none; width: 400px;" tabindex="-1">
	<table id="ctl00_ContentPlaceHolder1_Login2_Table1" role="presentation" style="width: 100%; border-spacing: 0px; border-collapse: separate;">
	<tr style="height: 28px; vertical-align: top;">
	<td class="floatingPopupHeader" style="vertical-align: middle; text-align: left; padding: 1px;">
	<h2>&nbsp;<span id="ctl00_ContentPlaceHolder1_Login2_lblEmails">Are Patient Portal emails being received?</span>
	</h2>
	</td>
	<td style="vertical-align: middle; text-align: right; padding: 1px;" class="floatingPopupHeader">
	<input type="image" name="ctl00$ContentPlaceHolder1$Login2$btnClose" id="ctl00_ContentPlaceHolder1_Login2_btnClose" src="../App_Themes/NextMDTheme/Images/close.gif" alt="Close" onclick="popUp(&#39;lnkemail&#39;,event,&#39;t4&#39;); popupClose();return false;WebForm_DoPostBackWithOptions(new WebForm_PostBackOptions(&quot;ctl00$ContentPlaceHolder1$Login2$btnClose&quot;, &quot;&quot;, true, &quot;&quot;, &quot;&quot;, false, false))" style="border-color:Black;border-width:0px;border-style:Solid;" />
	<img id="ctl00_ContentPlaceHolder1_Login2_Image1" src="../App_Images/spacer.gif" alt="" style="width:3px;border-width:0px;" />
	</td>
	</tr>
	<tr>
	<td colspan="2" style="padding: 1px;">
	<table role="presentation" style="width: 100%; border-spacing: 0px; border-collapse: separate; border: 0px none;">
	<tr>
	<td class="floatingPopupContent" style="padding: 0px; vertical-align: bottom;">
	<div id="divemails">
	<span id="ctl00_ContentPlaceHolder1_Login2_lblEmailPopup" class="fontstandardlabel" style="display:inline-block;width:100%;">It has been known that spam blocking software used by email providers such as AOL and Netzero may be blocking legitimate emails. To ensure that you are receiving Patient Portal emails please do the following:<br /><br />Add NextMD.com to your contact list, address list, safe list, or "Do Not Block" list.<br /><br />If you are using your own spam filtering software, please be sure that you are not filtering out email from NextMD.com.</span>
	</div>
	</td>
	</tr>
	</table>
	</td>
	</tr>
	</table>
	
	</div>
	
	
	</div>
	
	
	
	<!--WARNING this is account locked warning pop up -->
	<div id="dialogLocked" style="display: none;" role="dialog" aria-describedby="divmsg" aria-hidden="true" aria-label="warning">
	<div class="clear"></div>
	<div id="divmsg">
	<p>
	<span id="ctl00_ContentPlaceHolder1_Login2_lblPreLockedWarning">Account will be locked for 20 minutes after 4 failed login attempts. Please remember that password is case sensitive.</span>
	</p>
	</div>
	<br />
	<div style="text-align: center;">
	<input type="submit" name="ctl00$ContentPlaceHolder1$Login2$btnCloseHelp" value="Close" onclick="CloseThisForm(); return false;WebForm_DoPostBackWithOptions(new WebForm_PostBackOptions(&quot;ctl00$ContentPlaceHolder1$Login2$btnCloseHelp&quot;, &quot;&quot;, true, &quot;&quot;, &quot;&quot;, false, false))" id="ctl00_ContentPlaceHolder1_Login2_btnCloseHelp" class="fontStandardButton" style="height:30px;width:100px;" />
	<br />
	<br />
	<a id="ctl00_ContentPlaceHolder1_Login2_lnkNeedHelp" class="NeedHelpLink" href="javascript:__doPostBack(&#39;ctl00$ContentPlaceHolder1$Login2$lnkNeedHelp&#39;,&#39;&#39;)">Click here to Reset My Password or Username</a>

	</div>
	</div>
	
	<script type="text/javascript">
	if (isMobile.any()) {
	document.getElementById("ctl00_ContentPlaceHolder1_Login2_isMobile").value = "true";
	}
	else {
	document.getElementById("ctl00_ContentPlaceHolder1_Login2_isMobile").value = "false";
	}
	//account locked warning
	function ShowPopup1(message) {
	
	
	};
	// close account locked modal
	function CloseThisForm() {
	$("#dialogLocked").dialog('close');
	$("div#dialogLocked").attr("aria-hidden", "true");
	}
	
	//email popup - open
	function popupOpen() {
	$('#t4').show();
	$("#t4").attr("aria-hidden", "false");
	$("#ctl00_ContentPlaceHolder1_Login2_btnClose").focus();
	
	HideMainContentFromScreenReader();
	
	$("#loginLangDD").attr("aria-hidden", "true");
	$("#divWelcome").attr("aria-hidden", "true");
	$("#ctl00_ContentPlaceHolder1_divWelcomeOld").attr("aria-hidden", "true");
	$("#ctl00_ContentPlaceHolder1_welcomeMessageContainer").attr("aria-hidden", "true");
	$("#innerDiv").attr("aria-hidden", "true");
	$("#loginPageMsg").attr("aria-hidden", "true");
	$("#boxLogin").attr("aria-hidden", "true");
	$("#boxwrapperEnroll").attr("aria-hidden", "true");
	$("#divAlertEmails").attr("aria-hidden", "true");
	$("div.loginPrivacyPolicy").attr("aria-hidden", "true");
	}
	
	//email popup - close
	function popupClose() {
	
	ShowMainContentToScreenReader();
	
	$("#loginLangDD").removeAttr("aria-hidden");
	$("#divWelcome").removeAttr("aria-hidden");
	$("#ctl00_ContentPlaceHolder1_divWelcomeOld").removeAttr("aria-hidden", "true"); 
	$("#ctl00_ContentPlaceHolder1_welcomeMessageContainer").removeAttr("aria-hidden");
	$("#innerDiv").removeAttr("aria-hidden");
	$("#loginPageMsg").removeAttr("aria-hidden");
	$("#boxLogin").removeAttr("aria-hidden");
	$("#boxwrapperEnroll").removeAttr("aria-hidden");
	$("#divAlertEmails").removeAttr("aria-hidden");
	$("div.loginPrivacyPolicy").removeAttr("aria-hidden");
	
	$('#t4').hide();
	$("#t4").attr("aria-hidden", "true");
	$("#lnkemail").focus();
	}
	
	//wcag - close popup
	$(document).keydown(function (event) {
	if (GetKeyCode(event) == escapeKeyCode) {
	if ($("#t4").is(':visible')) {
	popUp('lnkemail', event, 't4');
	popupClose();
	}
	
	$('div#dialogLocked').attr("aria-hidden", "true");
	}
	});
	
	$(document).ready(function () {
	$("#lnkemail").keydown(function (event) {
	
	var keycode = GetKeyCode(event);
	
	if (keycode == enterKeyCode) {
	event.preventDefault();
	event.stopPropagation();
	popupOpen();
	popUp('lnkemail', event, 't4');
	}
	
	});
	
	$("#ctl00_ContentPlaceHolder1_Login2_btnClose").keydown(function (event) {
	
	var keycode = GetKeyCode(event);
	
	//if close is button then both enter and space key should work
	if (keycode == enterKeyCode || keycode == spaceKeyCode) {
	event.preventDefault();
	event.stopPropagation();
	popUp('lnkemail', event, 't4');
	popupClose();
	}
	});
	
	
	});
	
	$(document).bind('keyup click', function (e) {
	var keycode = GetKeyCode(e);
	if ($("#t4").is(':visible') && !document.getElementById("t4").contains(eventUtil.eventTarget(e)) && keycode != escapeKeyCode) {
	$("#ctl00_ContentPlaceHolder1_Login2_btnClose").focus();
	}
	});
	</script>
	
	</div>
	<div class="loginPrivacyPolicy">
	
	<table class="tablePrivacyPolicy_new" style="border-spacing: 0px; border-collapse: separate; border: 0px none;" role="presentation">
	<tr>
	<td style="padding:0px; vertical-align: top;">
	<div style="padding: 5px;" class="bodyTxt">
	<span id="ctl00_ContentPlaceHolder1_PrivacyPolicy2_lblPrivacyPolicyTitle">Your security is important.</span>
	
	<span id="ctl00_ContentPlaceHolder1_PrivacyPolicy2_lblPrivacyPolicyPart1">We use technology to encrypt, safeguard, and secure your personal information. Please view our</span>
	
	<a id="ctl00_ContentPlaceHolder1_PrivacyPolicy2_lnkPrivacyPolicy" class="fontStandardLink1" href="javascript:__doPostBack(&#39;ctl00$ContentPlaceHolder1$PrivacyPolicy2$lnkPrivacyPolicy&#39;,&#39;&#39;)">Privacy Policy</a>

	
	
	<span id="ctl00_ContentPlaceHolder1_PrivacyPolicy2_lblPrivacyPolicyPart3">for more information</span>
	
	</div>
	</td>
	<td style="vertical-align:middle; text-align: right; padding: 0px;">
	<div style="display:none;">
	<img id="ctl00_ContentPlaceHolder1_PrivacyPolicy2_imageVeriSignLogo" alt="" src="../App_Images/logoNewVeriSign.gif" style="border-width:0px;" />

	</div>
	</td>
	</tr>
	</table>
	
	</div>
	</div>
	
	</div> <!-- end content -->
	</div> <!-- end main -->
	<div id="UAfooter">
	
	<script type="text/javascript">
	function handleAPIBanner(hideshow) {
	$.ajax({
	type: "POST",
	url: "https://www.nextmd.com/ud2/Login/Login.aspx/HandleAPIBanner",
	data: JSON.stringify({ showBanner: hideshow }),
	dataType: 'json',
	contentType: 'application/json; charset=utf-8',
	success: function (response) {
	if (response.d === "true")
	{
	if (hideshow === "1") {
	$("#ctl00_Footer1_apibanner").show();
	}
	else
	{
	$("#ctl00_Footer1_apibanner").hide();
	}
	}
	else
	{
	
	}
	},
	error: function (errorThrown) {
	
	//alert('errorThrown: ' + errorThrown.responseText);
	},
	async: false
	});
	return false;
	}
	</script>
	<div id="footer">
	<div id="ctl00_Footer1_apibanner" class="apibanner row" style="display:none;">
	<div class="col-11">
	<span id="ctl00_Footer1_lblapiBanner">Your Patient Portal account enables you to access your data through other apps and websites using the NextGen API with the following practice(s): {0}. For more information, click</span>
	<a id="lnkapi" class="info" title="Opens a new window" href="https://www.nextgen.com/api/patientapi" target="_blank">

	here.
	</a>
	</div>
	<div class="col-1">
	<a class="jqmClose modal_tools_close modalCloseX xlink" href="#" aria-label="Close" role="button" onclick="javascript: handleAPIBanner('0');">X</a>
	</div>
	</div>
	<div class="leftsection" style="padding: 5px;">
	<div class="copyright pushR5">
	
	<span id="ctl00_Footer1_lblCopyright" class="lblCopyright">�1996-2024 NXGN Management, LLC</span>
	
	<div style="display: none;">
	<span id="ctl00_Footer1_lblVersion"></span>&nbsp;
	
	
	</div>
	</div>
	<div class="copyrightimg">
	<div id="divcopyrightimg"></div>
	</div>
	<div class="prodVersion">
	<span id="ctl00_Footer1_lblProdVersion">v5.3.0</span>
	</div>
	
	</div>
	<div style="float:right;" class="txtM">
	<ul style="display:inline-flex">
	
	
	<li>
	<a id="ctl00_Footer1_lnkSiteMap" class="fontFooterLink" href="javascript:__doPostBack(&#39;ctl00$Footer1$lnkSiteMap&#39;,&#39;&#39;)">Site Map</a>
	<span aria-hidden="true"> | </span>
	</li>
	
	<li>
	<a id="ctl00_Footer1_lnkPrivacyPolicy" class="fontFooterLink" href="javascript:__doPostBack(&#39;ctl00$Footer1$lnkPrivacyPolicy&#39;,&#39;&#39;)">Privacy Policy</a>
	<span id="ctl00_Footer1_lnkPrivacyPolicySpan" aria-hidden="true"> | </span>
	</li>
	<li id="ctl00_Footer1_aMobileSiteLi">
	<a id="ctl00_Footer1_aMobileSite" class="fontFooterLink" href="https://www.nextmd.com/m/">Mobile Site</a>

	
	</li>
	
	</ul> 
	
	<span aria-hidden="true">&nbsp;</span>
	<select name="ctl00$Footer1$lstLanguage" onchange="javascript:setTimeout(&#39;__doPostBack(\&#39;ctl00$Footer1$lstLanguage\&#39;,\&#39;\&#39;)&#39;, 0)" id="ctl00_Footer1_lstLanguage" aria-label="Language" style="margin:5px;">
	<option selected="selected" value="en-US">English</option>
	<option value="es-MX">Espa&#241;ol</option>
	<option value="zh-CN">简体中文</option>
	<option value="zh-HK">繁體中文</option>
	
	</select>
	<label for="ctl00_Footer1_lstLanguage" id="ctl00_Footer1_lbllLanguage" class="nonvisibletext">Language</label>
	</div>
	</div>
	<!-- the footer has to be outside of container for sticky footer to work -->
	</div>
	
	</div>
	
	
	<script src="../App_Scripts/browserSupport.js"></script>

	
	
	<input type="hidden" name="ctl00$BrowserSupport$hdnSessionPopup" id="ctl00_BrowserSupport_hdnSessionPopup" />
	<!--Browser support pop up -->
	<div class="displayNone">
	<div id="browserSupport" role="dialog">
	<h2 id="ctl00_BrowserSupport_h2PopupHeading" style="text-align:center"></h2>
	<div class="browserLayout">
	<a href="../App_UserControls/#" id="ctl00_BrowserSupport_IELink" class="column">

	<div class="browser"><div class="header ie"></div>
	<div class="name"><span id="ctl00_BrowserSupport_lblInternetExplorer">Internet Explorer</span></div>
	<input type="hidden" name="ctl00$BrowserSupport$hdnIEVersion" id="ctl00_BrowserSupport_hdnIEVersion" /></div>
	</a>
	<a href="../App_UserControls/#" id="ctl00_BrowserSupport_ChromeLink" class="column"><div class="browser">
	<div class="header chrome"></div>
	<div class="name"><span id="ctl00_BrowserSupport_lblGoogleChrome">Google Chrome</span></div>
	<input type="hidden" name="ctl00$BrowserSupport$hdnChromeVersion" id="ctl00_BrowserSupport_hdnChromeVersion" />
	</div>
	</a>
	<a href="../App_UserControls/#" id="ctl00_BrowserSupport_FireFoxLink" class="column"><div class="browser">
	<div class="header mozilla"></div>
	<div class="name"><span id="ctl00_BrowserSupport_lblMozillaFirefox">Mozilla Firefox</span></div>
	<input type="hidden" name="ctl00$BrowserSupport$hdnFirefoxVersion" id="ctl00_BrowserSupport_hdnFirefoxVersion" />
	</div></a>
	<a href="../App_UserControls/#" id="ctl00_BrowserSupport_SafLink" class="column lastCol"><div class="browser">
	<div class="header safari"></div>
	<div class="name"><span id="ctl00_BrowserSupport_lblAppleSafari">Apple Safari</span></div>
	<input type="hidden" name="ctl00$BrowserSupport$hdnSafariVersion" id="ctl00_BrowserSupport_hdnSafariVersion" />
	</div></a>
	</div>
	</div>
	</div>
	<script type="text/javascript">
	$(document).ready(function () {
	if (cookiesEnabled()) {
	var sessionBrowserSupport = $('#ctl00_BrowserSupport_hdnSessionPopup').val();
	
	if (sessionBrowserSupport == "False") {
	var bsupport = checkBrowser().split(','),
	currVersion = bsupport[0],
	browser = bsupport[1],
	minVersion = 0,
	needBrowserSupport = false;
	
	if (browser == "internetExplorer") {
	minVersion = parseInt($('#ctl00_BrowserSupport_hdnIEVersion').val());
	if (currVersion < minVersion) { needBrowserSupport = true; }
	}
	else if (browser == "chrome") {
	minVersion = parseInt($('#ctl00_BrowserSupport_hdnChromeVersion').val());
	if (currVersion < minVersion) { needBrowserSupport = true; }
	} else if (browser == "firefox") {
	minVersion = parseInt($('#ctl00_BrowserSupport_hdnFirefoxVersion').val());
	if (currVersion < minVersion) { needBrowserSupport = true; }
	} else if (browser == "safari") {
	minVersion = parseInt($('#ctl00_BrowserSupport_hdnSafariVersion').val());
	if (currVersion < minVersion) { needBrowserSupport = true; }
	} else {
	needBrowserSupport = true;
	}
	
	if (needBrowserSupport) {
	ShowBrowserPolicyPopup();
	}
	}
	}
	
	});
	
	function cookiesEnabled() {
	var cookieEnabled = navigator.cookieEnabled;
	// When cookieEnabled flag is present and false then cookies are disabled.
	if (cookieEnabled === false) {
	return false;
	}
	
	// try to set a test cookie if we can't see any cookies and we're using 
	// either a browser that doesn't support navigator.cookieEnabled
	// or IE (which always returns true for navigator.cookieEnabled)
	if (!document.cookie && (cookieEnabled === null || false)) {
	document.cookie = "testcookie=1";
	if (!document.cookie) {
	return false;
	}
	}
	
	return true;
	}
	</script>
	
	
	<img id="imgSessionAlive" style="display:none;" width="1" height="1" alt="" src="../App_Themes/NextMDTheme/Images/magicdot.gif" />

	
	<script type="text/javascript">
	//<![CDATA[
	var Page_ValidationSummaries = new Array(document.getElementById("ctl00_ContentPlaceHolder1_Login2_vldSummary_Login"));
	var Page_Validators = new Array(document.getElementById("ctl00_ContentPlaceHolder1_Login2_rfvUserName"), document.getElementById("ctl00_ContentPlaceHolder1_Login2_rfvPassword"));
	//]]>
	</script>
	
	<script type="text/javascript">
	//<![CDATA[
	var ctl00_ContentPlaceHolder1_Login2_vldSummary_Login = document.all ? document.all["ctl00_ContentPlaceHolder1_Login2_vldSummary_Login"] : document.getElementById("ctl00_ContentPlaceHolder1_Login2_vldSummary_Login");
	ctl00_ContentPlaceHolder1_Login2_vldSummary_Login.headertext = "Please enter both user name and password to proceed.";
	ctl00_ContentPlaceHolder1_Login2_vldSummary_Login.displaymode = "SingleParagraph";
	var ctl00_ContentPlaceHolder1_Login2_rfvUserName = document.all ? document.all["ctl00_ContentPlaceHolder1_Login2_rfvUserName"] : document.getElementById("ctl00_ContentPlaceHolder1_Login2_rfvUserName");
	ctl00_ContentPlaceHolder1_Login2_rfvUserName.controltovalidate = "ctl00_ContentPlaceHolder1_Login2_txtUserName";
	ctl00_ContentPlaceHolder1_Login2_rfvUserName.focusOnError = "t";
	ctl00_ContentPlaceHolder1_Login2_rfvUserName.display = "None";
	ctl00_ContentPlaceHolder1_Login2_rfvUserName.evaluationfunction = "RequiredFieldValidatorEvaluateIsValid";
	ctl00_ContentPlaceHolder1_Login2_rfvUserName.initialvalue = "";
	var ctl00_ContentPlaceHolder1_Login2_rfvPassword = document.all ? document.all["ctl00_ContentPlaceHolder1_Login2_rfvPassword"] : document.getElementById("ctl00_ContentPlaceHolder1_Login2_rfvPassword");
	ctl00_ContentPlaceHolder1_Login2_rfvPassword.controltovalidate = "ctl00_ContentPlaceHolder1_Login2_txtPassword";
	ctl00_ContentPlaceHolder1_Login2_rfvPassword.focusOnError = "t";
	ctl00_ContentPlaceHolder1_Login2_rfvPassword.display = "None";
	ctl00_ContentPlaceHolder1_Login2_rfvPassword.evaluationfunction = "RequiredFieldValidatorEvaluateIsValid";
	ctl00_ContentPlaceHolder1_Login2_rfvPassword.initialvalue = "";
	//]]>
	</script>
	
	
	<script type="text/javascript">
	//<![CDATA[
	areCookiesEnabled();//]]>
	</script>
	<script type="text/javascript"> var id = document.getElementById('ctl00_ContentPlaceHolder1_Login2_cltOffset'); var now = new Date(); id.value= now.getTimezoneOffset ( ) / 60 * ( -1 );</script>
	<script type="text/javascript">
	//<![CDATA[
	
	var Page_ValidationActive = false;
	if (typeof(ValidatorOnLoad) == "function") {
	ValidatorOnLoad();
	}
	
	function ValidatorOnSubmit() {
	if (Page_ValidationActive) {
	return ValidatorCommonOnSubmit();
	}
	else {
	return true;
	}
	}
	//]]>
	</script>
	</form> 
	</body>
	</html>
	

