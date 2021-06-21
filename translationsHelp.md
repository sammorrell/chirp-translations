# Languages and localisation
To contribute to adding translations to Chirp we've decided to use gitlocalise to enable people to add translations. 

Everything is stored on the git https://github.com/sammorrell/chirp-translations.

Note: In this document you'll see text be refered to as strings, these are the same thing, so every time you see the word string, think a chunk of text.

## Getting started
Go to the link https://gitlocalize.com/repo/6185 and you'll be presented with a list of languages and the current status of them. 

![Chirp Languages](images/chirpLanguages.png "A list of languages on chirp")
Click the language you wish to edit and click through to the en.json file. If you don't see the language you would like to translate please email sam[dot]cooper[AT]ligo[dot]org with the subject line "Chirp Language Request" and we can add the language to the project. 

Type on the right hand side of the box, screenshot included. 
![Edit languages](images/editLanguages.png "Editing langugages")
The left hand side of the image is the English text to be translated, the right hand side is the translated text - note this will default to English if there's no translation. Click on the white box e.g. "LIGO Hanford" on the right hand side

![Editing a translation](images/gitLocalise.png "How to edit translations")

Enter the translation - we'd prefer it if you didn't use machine translations as these can be inaccurate especially with larger volumes of text. Click submit once you've made a change and edit the other fields. 

Once this has been done you'll need to get an administrator or a moderator to review your request, once this has been merged the newly translated text will make it's way into the app.   

![Review Request](images/reviewRequestTranslations.png/ "Review requests for languages")
Add a comment to describe the translations that you've changed (just as you would for a git commit / merge request) and a moderator will review your translations. E.g. I've translated every string for German, or, I've translated these certain strings for Dutch. 

If you wish to become a moderator, please email sam[dot]cooper [AT]ligo[dot]org with the subject "Chirp Language moderator request" and I'll add you to the project. Anyone can contribute to the languages but we want to ensure that the translations are accurate and there is no malicoius intent in the translations - as the main developers will not be able to easily check the validity of the translations. 

## FAQ
### What happens when we update the strings?
Git localise pulls the new strings and flags the new strings for translations, older strings that are not by the string change do not need to be re-translated. 

### I want to help translate but I can't see the language I wish to translate listed
Get in touch by emailing sam[dot]cooper[AT]ligo[dot]org with the subject line "Chirp Language Request" - this helps Sam sort though his inbox and ensures that he will actually read your email and reply quicker. 

### I think I should be a moderator to approve translations. 
Great, we need moderators and translators - currnetly we're adding moderators that one of the developers knows or is in the LVK collaboration. If you want to become a moderator please email sam[dot]cooper[AT]ligo[dot]org with the subject "Chirp Language Moderator Request" and Sam will reply to you and add you moderator status if appropriate. Anyone is free to translate the app, however, if you are not a moderator you will have to create merge requests.

### I've spotted a mistake or typo in a translation
Oh no! Thanks for spotting the mistake, email with the subject line "Chirp Language Mistake" to sam[dot]cooper[AT]ligo[dot]org with the bit of text and the language that's affected - note we'll need the page on the app and the box it's near e.g. the "about LIGO" text has an error on it, it should read "example" instead. 

### Can you send me a list of text to translate (as I don't have a Github account)
At the moment, we're not looking to go down this path as we like having version control (Github accounnts are free!).
