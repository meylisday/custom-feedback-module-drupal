## The repo includes a custom feedback form module for drupal 8.

1. Install 

```
composer require drupal/smtp
composer require drupla/simple_mail
```

1. Enable  modules

```
drush en smtp
drush en simple_mail
```

For sending email uses function:

```
simple_mail_send($from, $to, $subject , $body);
```