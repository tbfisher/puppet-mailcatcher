# Puppet Module: Mailcatcher

MailCatcher runs a super simple SMTP server which catches any message sent to
it to display in a web interface. http://mailcatcher.me/

## Requirements

-   [puppetlabs-gcc](https://github.com/puppetlabs/puppetlabs-gcc.git)

## Usage

    include mailcatcher

To use with PHP you'll need to set `sendmail_path` to "/usr/local/bin/catchmail".
