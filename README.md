# serkaneken.github.io

## Setup

```bash
brew install rbenv ruby-build
echo 'eval "$(rbenv init - zsh)"' >> ~/.zshrc
source ~/.zshrc
rbenv install 3.3.0
rbenv global 3.3.0
gem install bundler
bundle install
```

## Local dev

```bash
bundle exec jekyll serve
```

Open <http://localhost:4000>.
