# contact-form-processor

This contact form backend is meant to provide services for serveral similar website and uses AWS Lambda and SES. Each unique site/page is distinguished by formKey (integer), which can be inserted by a hidden input in the form <input id="formKey" name="formKey" type="hidden" value="FORM-KEY-HERE"> if there are no security concerns.

# Environment Variables
Substitute 0 for the site's form key and repeat for each unique site.
* FROM_ADDRESS_0 - The from email address for the email that goes to TO_ADDRESS
* TO_ADDRESS_0 - The email address to send the form data to.
* APP_0 - The human-readable name of the application or website that the form was submitted on, for example, the URL where the form is located.
