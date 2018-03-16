##Drupal 7 simple coupone code generator
##Features:
- generating one-time/timeless keys;
- butch creating;
- keys admining page;
- adding description and prefix for keys;
- using by-key access to `Webform`s.
##How to use?
- Install and set enable as usual.
- Follow to the `admin/code-generator` for generating any amount of keys.
- Follow to the `admin/code-generator/list` for the codes viewing.
###If you want to use the module hand-by-hand with `Webform` for access by key to any form/forms
- add for needed form text field with **form-key** `code_field` and set as **Required**. Name the field as you want.
- if you need hide any other fields for viewing before key passing, set after the field `Page break` `Webform` Component.

When user enter its code into the field added above and press any submit button (it could be any form button: next page, submit etc.) the module compare the Key with codes generated early, and if code is valid user will see rest of form.

If code is not valid, user will see error message and move back to form start. 

If the user used one-time key for entering, he will see message about key deleting after greeting.

Enjoy! ;)
