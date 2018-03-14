# Configs Rubocop

Dans le fichier `Gemfile` :

```ruby
gem "rubocop", "X.X.X", require: false
```

Dans le fichier `.rubocop.yml` :

```yaml
inherit_from: http://rubocop.agilidee.com/X.X.X.yml
```

Attention : il y a un délai entre le push sur Github et le moment où
les changements sont répercturés sur http://rubocop.agilidee.com/.
