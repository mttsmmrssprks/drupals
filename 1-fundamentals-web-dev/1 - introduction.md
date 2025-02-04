# 1. Fundamentals of web development

This section addresses:
* Knowledge of HTML and CSS
* PHP programming concepts, including object-oriented programming
* Managing dependencies via Composer
* Javascript and jQuery programming concepts
* Git version control
* Responsive design concepts
* Automated testing, including PHPUnit

![alt text](<CleanShot 2025-02-04 at 16.09.32.jpg>)

## PHP Announce command

This is part of the ajax api documentation.

```php
// A string that contains the text to be announced by a screen reader.
$text = 'My Text';
// (optional) The priority that will be used for the announcement. Defaults to NULL which will not set a 'priority' in the response sent to the client and therefore the JavaScript Drupal.announce() default of 'polite' will be used for the message. Options: 'off','polite','assertive'. See https://www.w3.org/TR/wai-aria-1.1/#aria-live .
$priority = 'assertive';

$response->addCommand(new AnnounceCommand($text, $priority));
```

That's all! 🎉

