# Sublime Text 3 Puppet Module for Boxen

Install [Sublime Text 3](http://www.sublimetext.com/3/), a text-editor/IDE for Mac

## Usage

```puppet
include sublime_text_3
sublime_text_3::package { 'Emmet':
  source => 'sergeche/emmet-sublime'
}
```

## Required Puppet Modules

None.
