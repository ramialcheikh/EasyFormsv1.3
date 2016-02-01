# EasyFormsv1.3


    Form Builder
        Build any type of online forms: Contact forms, Order forms, Registration forms, Online surveys, Trivias and more.
        Drag-and-drop your form elements to rearrange them. No coding skills required.
        W3C-valid HTML5 Fields
        Built-in support for users on smartphones, tablets, and other mobile devices.
        Create Multi-Step Forms
        Add friendly hints and placeholders, making your forms easier and friendlier to fill out.
        Set a default value for certain fields. They’ll be submitted if the visitor doesn’t change them.
        Allow users to upload files
        Accept any file type
        Optionally limit the size or type of file you want
        Add advanced field validation
        Write your very own field validation rules using regular expressions
        Embed images, videos and maps
        Include Google reCAPTCHA in your forms
        Multiple reCAPTCHA theme options.
        Smart reCAPTCHA. Save the correct answer of a user. So, he don’t have to fill it again.
        Bootstrap CSS Support
        Set the positioning of your field labels across your form.
        Checkboxes and Radio Buttons can have images or icons
    Form Manager
        Use a unique URL to easily share/link a full-page form.
        Share frienly links to your forms
        Easily embed your form in your website, blog, shop—wherever you want it! No extra programming needed – just copy our code.
        Multiple embedding options and formats.
        Add a custom confirmation message or redirect to another website
        Load external javascript file
        Anti – Spam Protection (HoneyPot Technique)
        Limit Submission per Time Period
        Limit Submission by IP
        Auto-deactivation by dates
        Implement Save form & resume later
        Forms with Password Protection
    Themes & Templates
        Customize your forms’ branding.
        Theme & Template Managers
        Advanced CSS Editor with Form Live Preview
        Easy integration with the forms
        Template Promotion and Categories
        Comes with +10 pro-level themes
        Templates for event registration, contact forms, customer surveys, trivias, RSVPs, and more.
    Notifications
        Send Instant Notifications
        Be notified by email every time a form is submitted.
        Send confirmation messages (Email Auto-Responder)
        Send your customer a fully customizable email upon form submission. You can include data they entered in the message, too.
        Set up multiple recipients
        HTML / Plain Text Email
        File Attachment if your form has file upload fields
        Supply a custom “From” address for auto-response messages
        Use PHP mail() function
        Support for PHP SMTP Authentication. (Use your own SMTP mail server)
        Redirect your visitor to a specific URL after form submission.
        Send your submissions to another application or script
        Show your visitors or customer a custom message after submission.
    Rule Builder
        Create the conditional logic easily, no coding knowledge required.
        Intuitive interface
        Multiple rules, conditions and actions
        Show / Hide Fields
        Enable / Disable Fields
        Copy values from one field to another
        Perform math operations
        Format numbers to look like currency, percentages, times… easily
        Skip steps of multi step forms
    Submission Manager
        Advanced Submission Grid
        Alert new submissions
        View submission details
        View sender information (Google Map included)
        Edit and Delete each submission
        Export submissions
        Print form submissions
    Report Builder
        Build reports on form submission
        Use Row, Bar, Donut and Pie charts
        Move & Resize any chart
        Interact with your charts with one click
    Form Analytics
        Get an instant overview of form stats, including conversion rates.
        See how many people looked at your form.
        Know how many visits are made before your users send the form
        Improve the form and increase conversion rate
        Form Performance report
        Submissions Analytics report
        Track how many people started filling out your form.
        See the number of submissions for every form, in one single view!
        Disable form tracking on the fly
    User Management
        User Registration: Your users can register and create their own forms
        Login without password: Your users can test the application only with their email. After, they can create their own username and password
        Use captcha in your registration forms
        Set the default user role when a new user is registered
        User Roles: Admin, Advaced User and Basic User
        The “Advanced User” is able to create and manage his own forms and themes
        The “Admin” can grant access of each Form to each “Basic User”
        All users can be suspended
        Profiles
        Login by email or username
        Email confirmation
        Password recovery
    Add-ons
        Google Analytics: Track your visitors in Google Analytics
        Webhooks: Send submissions to another server
    Multi Language
        English, Spanish and Indonesian languages
        You can translate all the application to other languages easily
        You can set up each form to use a different language
        The user has the ability to change and select default language for his user account
    Other
        Responsive Design
        Based on Bootstrap 3 and Yii 2
        Glyphicons PRO 1.9.2

Requirement

    Server Linux/Unix (Recommended), Windows or Mac OS X
    Web Server Apache (Recommended), Microsoft IIS or any similar web server
    PHP Version PHP v5.4 or above
    Database MySQL v5 or higher suggested
    CRON/Scheduled Tasks
Documentation

easyforms.baluart.com/docs
Demo Video

How To Create a Contact Form with Easy Forms
UPDATES

30.01.2016 - ver 1.3.1
    - Added: Console component
    - Deprecated: ConsoleHelper
    - Improved: Setup / Update modules
    - Improved: Cron
    - Improved: Tel field validation message
    - Fixed: Dashboard for advanced users
    - Fixed: Performance tool
    - Fixed: Required fields without labels
    - Fixed: Actions buttons for advanced users
    - Fixed: Google Analytics add-on event handler
28.01.2016 - ver 1.3
    - Added: User registration page
    - Added: Login page without password
    - Added: Enable / Disable user registration from Site Settings
    - Added: Add captcha to user registration from Site Settings
    - Added: Set a default user rol from Site Settings
    - Added: New user role: 'Advanced User' and 'User' now is 'Basic User'
    - Added: Display Form Manager 'Actions' button to all users
    - Added: Refresh cache tool
    - Added: HTTP and HTTPS protocols supported
    - Added: Print form submission
    - Added: Format Number action on Form Rules
    - Added: Indonesian language
    - Improved: Grid Views footer design
    - Improved: Check user permissions
    - Improved: Change login page when 'anyone can register' is enabled
    - Improved: Addons module can update each addon version
    - Improved: Install Process, update and uninstall addons
    - Improved: Addons module events
    - Improved: User module updated to new version
    - Improved: Upload File validation on Multi Step forms
    - Improved: Multi-Step forms pager
    - Improved: Button component now supports 'button' input type
    - Improved: Form Builder. Add images or icons to checkboxes or radio buttons
    - Improved: Form Builder. Add icons to buttons
    - Improved: Form Builder. New button input type: 'button'
    - Fixed: Setup module error message
    - Fixed: Export CSV file with 'file' fields
    - Fixed: Reset password email
    - Fixed: Delete multiple themes
    - Fixed: Delete multiple templates
    - Fixed: Default local IP for testing
    - Fixed: XSS vulnerability on Submission Manager
14.01.2016 - ver 1.2
    - Added: Pre-fill Form Widget with default values
    - Added: Forms with Password Protection
    - Added: Filters in Form Manager, Templates and Themes
    - Added: Rules Engine. If condition not accomplish, reset skip step
    - Improved: Form Builder with duplicated fields detector
    - Improved: Form Settings design
    - Improved: New migrations
    - Improved: Spanish language translation
    - Improved: Vendor's files has been updated.
    - Improved: Submission Event Handler with multiple cc and multiple bcc
    - Fixed: Email notifications with array value.
    - Fixed: Resize Form Widget on IE
    - Fixed: ThemeSearch table prefix
    - Fixed: UserSearch profile attribute
    - Fixed: Only validate by field type if input has a value
    - Fixed: Form Builder without mod_rewrite
    - Fixed: Delete Multiple Action on Form Manager
    - Fixed: Form Builder's checkbox and radio button edition on Firefox
    - Fixed: Dashboard Labels on Firefox
07.01.2016 - ver 1.1
    - Added: Webhooks Add-on
    - Added: Friendly urls of forms
    - Added: Update module
    - Added: Now Easy Forms works without mod_rewrite.
    - Added: 'record' param to Form Widget
    - Added: Cron jobs configuration with params
    - Added: Email delivery with PHP mail() function
    - Improved: Glyphicons version 1.9.2
    - Improved: Run migrations on background
    - Improved: Redirection and message after updating to a user
    - Improved: In-App Analytics configurations
    - Improved: Dashboard dates
    - Improved: Add icon to Rule Builder error message
    - Improved: Add icon to Report Builder success message
    - Improved: Spanish translation
    - Improved: Custom text of button on multi-step forms
    - Fixed: Show / hide columns on Submission Manager
    - Fixed: Form Manager with table prefix.
    - Fixed: Submission event handler.
    - Fixed: Log out link
    - Fixed: Export submissions as CSV file
29.12.2015 - Initial release
