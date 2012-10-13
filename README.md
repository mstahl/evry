# evry

A really simple command for running a command periodically, at set intervals.

## Install

Install with `gem`...

    gem install evry

...or throw it into your Gemfile, thusly...

    gem 'evry'

## Usage

    evry [options] [time](s|sec|secs|m|min|h|hr|hrs) [command]

## Allowed options

  * `-c`: Clear the screen between intervals

## Example

    + [23:06:45](max@lola)(~)$ ~> evry 13s date
    Fri Oct 12 23:06:58 CDT 2012
    Fri Oct 12 23:07:11 CDT 2012
    Fri Oct 12 23:07:24 CDT 2012
    Fri Oct 12 23:07:37 CDT 2012

## Contributing to evry
 
  * Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
  * Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
  * Fork the project.
  * Start a feature/bugfix branch.
  * Commit and push until you are happy with your contribution.
  * Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
  * Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 max thom stahl. See LICENSE.txt for
further details.

