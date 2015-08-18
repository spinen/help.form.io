---
title: Button
book: userguide
chapter: form-components
slug: button
weight: 20
---
<p>Buttons can be added to forms to do various actions on the form.</p>
<img src="/assets/img/button-display.png">
<h4>Label</h4>
<p>This is the label that will appear on the button.</p>
<h4>Action</h4>
<p>This is the action that will be performed. Currently there are four actions that can be performed.</p>
<h5>Submit</h5>
<p>A submit action submits the form to either the form.io server or a custom callback url if it was set on the form.</p>
<h5>Previous Page</h5>
<p>Move the form to the preview page of a multi-page form. (This functionality is not yet complete).</p>
<h5>Next Page</h5>
<p>Move the form to the next page of a multi-page form. (This functionality is not yet complete).</p>
<h5>Reset</h5>
<p>Reset the form back to its original state.</p>
<h4>Theme</h4>
<p>Set a theme for the button. These options currently map to <a href="http://getbootstrap.com">bootstrap</a> classes that will be added to the button.</p>
<h4>Size</h4>
<p>Set the size of the button. These options currently map to <a href="http://getbootstrap.com">bootstrap</a> classes that will be added to the button.</p>
<h4>Left Icon</h4>
<p>If you have an icon library and would like to include an icon to the left of the button label, you can do so by adding the icon class here.</p>
<h4>Right Icon</h4>
<p>If you have an icon library and would like to include an icon to the right of the button label, you can do so by adding the icon class here.</p>
<h4>Block</h4>
<p>If checked, the display of the button will be set to "block" which will cause it to span the full width of the container.</p>
<h4>Disable on Form Invalid</h4>
<p>If checked, this button will be disabled if any of the client side validation fails. This is useful for preventing the submission of a form that has invalid data entered.</p>