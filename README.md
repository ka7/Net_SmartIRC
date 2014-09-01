# [Net_SmartIRC](http://pear.php.net/package/Net_SmartIRC/)

[Docs](http://pear.php.net/package/Net_SmartIRC/docs) -
[Bugs](http://pear.php.net/package/Net_SmartIRC/bugs) -
[Downloads](http://pear.php.net/package/Net_SmartIRC/download) -
[Roadmap](http://pear.php.net/bugs/roadmap.php?package=Net_SmartIRC)

## What is this?
Net_SmartIRC is a PHP package that helps you communicate with IRC networks
in whatever way you might need, whether in a CLI program or as part of a web page.
It's also well suited for bot development.

## Goals
- To be a fast and full-featured way to interface your PHP code with IRC networks.
- To provide a concise, easy-to-use module API to make it do exactly what you want.

## Future plans
This package was originally written for PHP 4 (and the code shows it). My aim is
to fix all submitted bugs, update the code structure as much as I can without
breaking backward compatibility, and implement whatever new features are fairly
simple to add. This package will likely be used as a starting point for a new
IRC library that uses better OO principles and is even easier to use.
- Garrett W., current maintainer

## How to contribute
1. Read the TODO file or the roadmap on the main package homepage to see what needs doing
2. Fork the repo
3. Make code changes using PEAR Coding Standards
4. Submit pull request
5. Pat yourself on the back

## People involved
- [Mirco 'meebey' Bauer] (https://github.com/meebey)
- [Amir Mohammad Saied] (http://gluegadget.com/)
- [Garrett Whitehorn] (https://github.com/garrettw)
- See the package homepage for the official list

## Files included
- Net/
  - SmartIRC/
    - defines.php (Necessary message code defines)
    - irccommands.php (Basic outgoing message functions)
    - messagehandler.php (Basic incoming message handlers)
  - SmartIRC.php (The class itself)
- docs/
  - examples/
    - example.php (a very basic bot that simply responds to a message)
    - example2.php (how to output number of channel users in a webpage)
    - example3.php (another basic bot that uses the channel user list to find ops)
    - example4.php (examines realnames of users in channel)
    - example5.php (kicks other users on command)
    - example6.php (greets users when they join the channel)
    - example7.php (shows how to use timers to do things rather than events)
  - HTML/ (the full documentation of SmartIRC)
  - DOCUMENTATION (Appendix to the HTML documention for developers)
  - HOWTO (Mini howto with detailed information, step by step)
- tests/
- composer.json (Eventually this package will be on packagist.org)
- package.xml (Package info file generated by PEAR packager)
