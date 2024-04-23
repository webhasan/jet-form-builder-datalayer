# Jet form Tracking with Google Tag Manager - Jet Form GTM Data Layer
## For Ajax / Non-Ajax Both Types of Gravity Form 

### How to use 
1. In Google Tag Manager, create a new tag as a custom HTML tag.
2. Inside the tag, paste the entire code from the `jet-form-datalayer.html` file provided in this repository. 
3. Set the trigger to fire on all page views.

Once you've configured this setup, you'll begin receiving Google Tag Manager dataLayer events as `jet_form_submit`. You will get the form ID as ***form_id*** and all other form inputs.
