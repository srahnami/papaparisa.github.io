---
id: 13
title: astra
date: '2022-10-15T00:33:56+00:00'
author: admin
layout: revision
guid: 'https://papaparisa.com/?p=13'
permalink: '/?p=13'
---

/\* WPForms fixes \*/  
/\* Initial field looks \*/  
.wpforms-container input\[type=date\],  
.wpforms-container input\[type=datetime\],  
.wpforms-container input\[type=datetime-local\],  
.wpforms-container input\[type=email\],  
.wpforms-container input\[type=month\],  
.wpforms-container input\[type=number\],  
.wpforms-container input\[type=password\],  
.wpforms-container input\[type=range\],  
.wpforms-container input\[type=search\],  
.wpforms-container input\[type=tel\],  
.wpforms-container input\[type=text\],  
.wpforms-container input\[type=time\],  
.wpforms-container input\[type=url\],  
.wpforms-container input\[type=week\],  
.wpforms-container select,  
.wpforms-container textarea {  
 background: #fff;  
 border-width: 0 0 1px 0;  
 color: var(–ast-global-color-2);  
 opacity: 0.5;  
}  
/\* On focus \*/  
.wpforms-container input:focus,  
.wpforms-container select:focus,  
.wpforms-container textarea:focus {  
 outline: none;  
 opacity: 1;  
 border-color: var(–ast-global-color-0);  
}  
/\* Don’t allow resizing the Message box \*/  
.wpforms-container textarea {  
 resize: none;  
}  
/\* Message box fixed height \*/  
.wpforms-container .wpforms-field-textarea textarea.wpforms-field-medium {  
 height: 136px;  
}  
/\* Button size &amp; font size \*/  
.wpforms-container button {  
 padding: 15px 34px;  
 font-size: 15px;  
}  
/\* WPForms done \*/  
/\* Footer 2 big columns on sides and 1 small one in the middle \*/  
.ast-builder-grid-row-3-equal .ast-builder-grid-row {  
 grid-template-columns: 3fr 1fr 3fr;  
}