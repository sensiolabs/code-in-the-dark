# Code in the Dark x SensioLabs
## Installation
For easier development process, the use of the Symfony CLI is recommended and all commands are presented as such.
* `git clone` this repository
* `cd citd-aperodev`
* `symfony composer install`

This application is made to work with SQLite. Please change the `DATABASE_URL` value in `.env` file to match yours.
* `symfony console doctrine:database:create`
* `symfony console doctrine:migrations:migrate`
* `symfony console doctrine:fixtures:load`

If using the Symfony CLI, you can start the dev server with `symfony serve -d`.

You can visualize the full result of the exercise on the branch `result`.
To reset the exercise between sessions, run `git reset --hard HEAD`.

**DO NOT COMMIT YOUR WORK**
