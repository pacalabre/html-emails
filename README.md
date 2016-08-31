Two kinds of emails:
html - mostly text rendered with HTML - allowing visual ques, images, and css styles
plaintext - text with no styles


e-mails are all tables based - just like webdev in the 90's

One to many e-mails - news letters, ad's etc:
Room for embellishment.

This include: README, Buy me, Join me type emails.


Transactional - receipts, account notification, etc...
style should be minimal

Transactional emails should be:
-focused
- short but comprehensive
- appropriate
- practical

- if an action is required there should be a BIG OBVIOUS CALL TO ACTION
- if its the type of e-mail that would be filed, it should be readable and printable.


// FONTS

Fonts are limited in emails. Fonts that are compatible are:
Sans-Serif:
- Arial
- Arial Black
- Tahoma
- Trebuchet MS
- Verdana

Serif Fonts:
- Courier
- Courier New
- Georgia
- Times
- Times New Roman


//EMBEDDING IMAGES

You need to host images on a web server and pull them into your e-mail using absolute paths.

You can't rely soley on images since most e-mail clients block images by default for first time recipients - therefore the text is often the best chance that you have to make a good impression.

// CALL TO ACTIONS

Make this more descriptive than just "click here." For example - use 'Shop Now' or 'Add a Profile.' Use verbs to show why they want to click on the button.

// LAYOUT

E-mails work best when the max width is around 600px(though up to 800px should work okay.) This is because many e-mail clients have narrow preview windows.

// TECHNICAL BEST PRACTICES

- Its all about tables HTML tags.
  - Unlike with websites, the table tag is not just used for tabular data, its all you use for consisten structure.
Table refresher - since who really has used a table lately:
<table>
tables
  <tr>
  "table row" - every table has at least one row, and they span the width of the table.
    <td>
      "table data" defines a data cell within a table. This is how the table is vertically structured. This is the container that will hold everything else - images, text, and other HTML elements.
    </td>
  </tr>
</table>
- You should ignore 'best practices' for the browser such as avoiding inline styles.
- It is in best practice to code out buttons rather than use images so that the e-mail provider does not block the image used for the button




