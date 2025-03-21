![saplings](https://github.com/kanopi/saplings/assets/5177009/a6377e32-deb2-49d8-873a-f3dd5a36fa7c)

# Saplings - Password Policy - 90 Days

A Drupal recipe that installs and configures the Password Policy module and sets
a 90-day expiration default.

This recipe installs a Password Policy that has the following rules:

- Password must be changed every 90 days.
- Password can't be one of the 5 most recent passwords.
- Password must contain at least 1 letter character.
- Password must contain at least 1 special character.
- Password must contain at least 1 uppercase character.
- Password must contain at least 1 lowercase character.
- Password must contain at least 1 numeric character.
- Password character length must be at least 12 characters


## Requiring this Recipe

`composer require kanopi/saplings-password-policy-90-days`


## Applying this Recipe

`drush cr`
`drush recipe saplings-password-policy-90-days`

**or**

If you have our Docksal command in your project, run the following command:
`fin recipe-apply saplings-password-policy-90-days`


## Unpacking this Recipe

To unpack this recipe's dependencies to your site's composer.json, in the root
of your project run:

`composer unpack kanopi/saplings-password-policy-90-days`

If you have our Docksal command in your project, run the following command:
`fin recipe-unpack kanopi/saplings-password-policy-90-days`
