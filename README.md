# Steps

    1) Download the package via composer (barryvdh/laravel-dompdf).

    2) Copy the config dompdf.php file via command.

    3) Use providers & aliases on the app.php for dompdf package.

    4) Make route for generate pdf on the web.php or somewhere else.

    5) Load the view file to download & finally name it for download or steam.

    6) **N.B** : Must use public_path() not asset(). Using asset() will show loading status.