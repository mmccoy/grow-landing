# Grown Landing Theme
-------------------

Setting up the Google Form
--------------------------

In order to make the signup form work, a little legwork is needed to create two Google documents.

1. A google form with one field, 'Email Address'.
2. A google spreadsheet to collect the email address submissions.

Once this is done, replace the variables 'form_key' and 'field_id' in home.md with your values.

## form_key
This is a string that identifies the Google Form to post to.

**Example:** _1x_rILp6UvJXVLiYMY9Ux8HB5OVQRwWIUeLW1kfZEwxU_

## field_id
This is a value of the 'name' attribute on email field of the rendered form.

**Example:** entry.1234567890
