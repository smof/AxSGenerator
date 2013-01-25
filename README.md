AxSGenerator
------------

Creates an output file of userid to entitlements mappings, based on an input file of full names.  Useful for identity management provisioning
testing and analysis.
<br/>
<b>Example:</b>
<br/>
Input - Simon Moffatt
Output - Simon Moffatt, smoffatt1, "group1, group2, group3, group4"
<br/>
Entitlements list is via a dictionary file that can be edited accordingly for any access control list value.
<br/>
UUID formula is currently hardcoded to first letter of first name concatenated to lastname, with a trailing integer for duplicates.
<br/>
User to entitlement numbers can be randomized.
<br/>
A list of full names can be generated via <a href="http://www.github.com/smof/NameGenerator">NameGenerator</a>
<br/>
<b>Use as-is, not warranty.  Fork, copy, modify, distribute, as long as attribution is left in place</b>

