# Translation files
If you want to contribute to translating Owler's layout, follow the instructions below.

You can request a additional language (in this case, a blank file so you can edit it) via a Github issue.

## How can I translate?
You can translate the .po file by a tool called **poedit**. There are other tools too, but **poedit** is used for us because it is more intuitive, but it's your choice.
When you think it's enough, you can make a pull request with the edited file. To do this, you need to fork this repository, make the changes, then do a pull request.

### Notice
Editing manually using a text editor is **not recommended**, since it can cause problems.
If you're editing it manually, using a text editor, please do only edit the `msgstr` for the translation and leave the `msgid` intact. If you edit the `msgid`, the file won't work.

## How to make a good translation?

Choose a text style and be consistent in it, for example in "What Are You Doing?", you have to choose if you will follow the lettering or if you're gonna translate it in another way, for example "What are you doing?".

Don't use translators unless you already know the language and just want to save time. Always review strings that have been translated by Google Translate or another tool. 

 It is not recommended to use translators on strings that contain HTML or variables, as they may be cut off. You cannot edit the HTML tags or variable names, only move them if really necessary. You also cannot rename entities, for example changing the name Owler to John Doe. New lines can be ignored. If you make a malicious translation, which aims to insert additional scripts or HTML, or which has strings that don't make sense just to harm the site, you will be banned from contributing and your Owler account will be suspended, if you have an account there.

You DON'T need to translate all the strings. You just need to translate 10% of the strings to your pull request be accepted in the repository, obviously, a great translation rate (75% or more) is preferable. It's recommended to give priority on strings that you will see more on the website.