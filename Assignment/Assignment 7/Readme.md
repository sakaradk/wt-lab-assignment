Date :2022/06/19- 2022/06/20
What is PHP?
PHP (recursive acronym for PHP: Hypertext Preprocessor) is a widely-used open source general-purpose scripting language that is especially suited for web development and can be embedded into HTML.

Nice, but what does that mean? An example:

Example #1 An introductory example

<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
    </head>
    <body>

        <?php
            echo "Hi, I'm a PHP script!";
        ?>

    </body>

</html>
Why is PHP Still So Widely Used?
PHP (Hypertext Preprocessor) is known as a general-purpose scripting language that can be used to develop dynamic and interactive websites. It was among the first server-side languages that could be embedded into HTML, making it easier to add functionality to web pages without needing to call external files for data. Its use has evolved over the years, with regular upgrades (version 8.0 was released in November 2020) adding features and unlocking new capabilities.
virtual host setup
Virtual Host
A virtual host is used for hosting multiple domain names on a single server.

Create a folder in htdocs of xammp then write php code syntax: <?php> echo "Echo is use to print in php" ?>

Open apachi > conf >extra >httpd-vhosts.conf in notepad (run as administrator) Then add:

DocumentRoot "C:\xampp\htdocs\folder location"
ServerName name.local
</VirtualHost>
then save

Then open C:\Windows\System32\drivers\etc\hosts in notepad add 127.0.01 name.local then you are ready to go:search localhost/location of your directory
