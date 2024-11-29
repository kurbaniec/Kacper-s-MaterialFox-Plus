Firefox's UI by [user1189731](https://superuser.com/a/1608642)
============

To inspect Firefox's UI you can use the [Browser Toolbox](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox).

Enable the Browser Toolbox
--------------------------

1.  Press F12 to open the [Page Inspector](https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector).  
    **Alternate**: Right click the page then "Inspect Element (Q)".
    
2.  Press F1 to open the [Page Inspector Settings](https://developer.mozilla.org/en-US/docs/Tools/Settings).  
    **Alternate**: In the top right of the Page Inspector next to the close button; press the "⋯" button then "Settings".
    
3.  Ensure the following settings are checked:
    
    *   "Enable Browser chrome and add-on debugging toolbox"
    *   "Enable remote debugging"

Open the Browser Toolbox
------------------------

1.  Press alt, "Tools", "Web Developer" then "Browser Toolbox".  
    **Alternate**: Press ctrlaltshifti

Extensions
==========

You can use the Browser Toolbox to inspect extensions. Additionally you can inspect extensions through [`about:debugging`](https://developer.mozilla.org/en-US/docs/Tools/about:debugging).

1.  Navigate to `about:debugging`.
2.  Go to the "This Firefox" page.
3.  Find the extension you want to inspect.
4.  Press "Inspect".