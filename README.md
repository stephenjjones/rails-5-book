
## Install Ruby (OSX)
```
$ brew install rbenv ruby-build
$ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
$ source ~/.bash_profile
$ rbenv install 2.3.1
$ rbenv global 2.3.1
$ ruby -v
```

`$ bin/rails/server -b 0.0.0.0`

`$ bin/rails generate scaffold Product title:string description:text`
`$ bin/rails db:migrate`
`$ bin/rails test`
`$ bin/rails db:seed`
`$ bin/rails db:rollback`
