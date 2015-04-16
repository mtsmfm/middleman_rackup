This repository's files created by `middleman init . --rack` except Gemfile*.

    BUNDLE_GEMFILE=Gemfile-mm338 bundle install
    BUNDLE_GEMFILE=Gemfile-mm339 bundle install
    BUNDLE_GEMFILE=Gemfile-mmedge bundle install

    BUNDLE_GEMFILE=Gemfile-mm338 bundle exec rackup  # work
    BUNDLE_GEMFILE=Gemfile-mm339 bundle exec rackup  # doesn't work
    BUNDLE_GEMFILE=Gemfile-mmedge bundle exec rackup # doesn't work
