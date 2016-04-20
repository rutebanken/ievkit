# Ievkit

[![Code Climate](https://codeclimate.com/github/afimb/ievkit/badges/gpa.svg)](https://codeclimate.com/github/afimb/ievkit)
[![Dependency Status](https://gemnasium.com/afimb/ievkit.svg)](https://gemnasium.com/afimb/ievkit)
[![Gem Version](https://badge.fury.io/rb/ievkit.svg)](https://badge.fury.io/rb/ievkit)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ievkit'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ievkit

## Usage


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run
`rake iev_import_file='metz-gtfs_current.zip' iev_import_params='importgtfs.json' iev_export_params='exportneptune.json' iev_validate_params='validategtfs.json'`
to run the tests.
You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/ievkit.


## License

This project is licensed under the CeCILL-B license, a copy of which can be found in the [LICENSE](./LICENSE.md) file.

