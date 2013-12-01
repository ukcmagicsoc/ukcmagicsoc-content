/*
 Title: Join Us
 */

## Join the UKC Magic Society

<div class="row">
 <div class="large-6 columns">
 	<img src="http://toolkit.ukcmagicsoc.org/projects/you%20plus%20magic/brand/brand_primary.png" alt="You + Magic">
 </div>
 <div class="large-6 columns">
 	<div class="error"></div>
 	
 	<div class="row">
   <div class="large-12 columns">
    <form action="http://ukcmagicsoc.org/lists/?p=subscribe&amp;id=1" method="post" name="subscribeform">
    	<input name="htmlemail" value="1" type="hidden">
    	<input name="list[6]" value="signup" type="hidden">
    	<input name="listname[6]" value="join" type="hidden">
    	<div style="display:none"><input name="VerificationCodeX" value="" size="20" type="text"></div>
    	
    	<p style="font-size:smaller">Required inputs are indicated by a <strong>*</strong></p>

    	<div class="row">
      <div class="large-4 columns">
       <label for="attribute1">First Name *</label>
       <input type="text" name="attribute1" required>
       <script language="Javascript" type="text/javascript">addFieldToCheck("attribute1","First Name");</script>
      </div>
      <div class="large-4 columns">
       <label for="attribute2">Last Name *</label>
       <input type="text" name="attribute2" required>
       <script language="Javascript" type="text/javascript">addFieldToCheck("attribute2","Last Name");</script>	
      </div>
      <div class="large-4 columns">
       <label for="attribute3">StudentID</label>
       <input type="text" name="attribute3">
      </div>
    	</div>
    	
    	<div class="row">
      <div class="large-12 columns">
       <label for="email">Email Address *</label>
       <input type="text" name="email" required>
       <script language="Javascript" type="text/javascript">addFieldToCheck("email","Email address");</script>
      </div>
    	</div>
    	
    	<div class="row">
      <div class="large-6 columns">
       <label for="pivacy">
       	<input name="pivacy" type="checkbox" required> I have read, and agree to the <a href="http://ukcmagicsoc.org/privacy/">privacy policy</a>. *
       </label>
      </div>
      <div class="large-6 columns">
       <input name="subscribe" value="Join" onclick="return checkform();" type="submit" class="button expand">
      </div>
    	</div>
    </form>
   </div>
 	</div>
 </div>
</div>

<script language="Javascript" type="text/javascript">function checkform(){for(i=0;i<fieldstocheck.length;i++)if("checkbox"==eval("document.subscribeform.elements['"+fieldstocheck[i]+"'].type")){if(!document.subscribeform.elements[fieldstocheck[i]].checked)return alert("Please enter your "+fieldnames[i]),eval("document.subscribeform.elements['"+fieldstocheck[i]+"'].focus()"),!1}else if(""==eval("document.subscribeform.elements['"+fieldstocheck[i]+"'].value"))return alert("Please enter your "+fieldnames[i]),eval("document.subscribeform.elements['"+fieldstocheck[i]+"'].focus()"),!1;for(i=0;i<groupstocheck.length;i++)if(!checkGroup(groupstocheck[i],groupnames[i]))return!1;return!0}function addFieldToCheck(a,b){fieldstocheck[fieldstocheck.length]=a,fieldnames[fieldnames.length]=b}function addGroupToCheck(a,b){groupstocheck[groupstocheck.length]=a,groupnames[groupnames.length]=b}function compareEmail(){return document.subscribeform.elements.email.value==document.subscribeform.elements.emailconfirm.value}function checkGroup(a,b){for(option=-1,i=0;i<document.subscribeform.elements[a].length;i++)document.subscribeform.elements[a][i].checked&amp;&amp;(option=i);return-1==option?(alert("Please enter your "+b),!1):!0}var fieldstocheck=new Array,fieldnames=new Array,groupstocheck=new Array,groupnames=new Array;</script>

All you have to do is join the mailing list, and we'll send you the need to know information not only about the UKC Magic Society, but some insider knowledge on how to make the most out of your first week at [Kent](http://kent.ac.uk).

It's freshers week and we know that you're trying to find out as much about, as much as possible, as fast as possible. We've made it **super easy** to learn about us, and still have time to enjoy the [freshers experience](http://www.kentunion.co.uk/freshers/).