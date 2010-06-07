source 'http://rubygems.org'

DATAMAPPER = 'git://github.com/datamapper'
SNUSNU     = 'git://github.com/snusnu'

RAILS_VERSION = '~> 3.0.0.beta3'
DM_VERSION    = '~> 1.0.0.rc3'
DO_VERSION    = '~> 0.10.3'

git 'git://github.com/rails/rails.git' do

  gem 'activesupport',              RAILS_VERSION, :require => 'active_support'
  gem 'actionpack',                 RAILS_VERSION, :require => 'action_pack'
  gem 'railties',                   RAILS_VERSION, :require => 'rails'

end

gem 'dm-core',                      DM_VERSION, :git => "#{DATAMAPPER}/dm-core.git"
gem 'dm-rails',                     DM_VERSION, :git => "#{DATAMAPPER}/dm-rails.git"
gem 'dm-active_model',              DM_VERSION, :git => "#{DATAMAPPER}/dm-active_model.git"
gem 'dm-migrations',                DM_VERSION, :git => "#{DATAMAPPER}/dm-migrations.git"

gem 'data_objects',                 DO_VERSION, :git => "#{DATAMAPPER}/do.git",               :require => nil
gem 'dm-do-adapter',                DM_VERSION, :git => "#{DATAMAPPER}/dm-do-adapter.git",    :require => nil
gem 'dm-mysql-adapter',             DM_VERSION, :git => "#{DATAMAPPER}/dm-mysql-adapter.git", :require => nil

gem 'dm-types',                     DM_VERSION, :git => "#{DATAMAPPER}/dm-types.git"
gem 'dm-constraints',               DM_VERSION, :git => "#{DATAMAPPER}/dm-constraints.git"
gem 'dm-aggregates',                DM_VERSION, :git => "#{DATAMAPPER}/dm-aggregates.git"
gem 'dm-serializer',                DM_VERSION, :git => "#{DATAMAPPER}/dm-serializer.git"
gem 'dm-timestamps',                DM_VERSION, :git => "#{DATAMAPPER}/dm-timestamps.git"
gem 'dm-validations',               DM_VERSION, :git => "#{DATAMAPPER}/dm-validations.git"
gem 'dm-is-remixable',              DM_VERSION, :git => "#{DATAMAPPER}/dm-is-remixable.git"
gem 'dm-transactions',              DM_VERSION, :git => "#{DATAMAPPER}/dm-transactions.git"

gem 'dm-is-self_referential',       DM_VERSION, :git => "#{SNUSNU}/dm-is-self_referential.git"
gem 'dm-is-localizable',            DM_VERSION, :git => "#{SNUSNU}/dm-is-localizable.git"
gem 'dm-accepts_nested_attributes', DM_VERSION, :git => "#{SNUSNU}/dm-accepts_nested_attributes.git"

gem 'dm-pager',                     '~> 1.1.0'

gem 'rails_metrics',                '~> 0.1', :git => 'git://github.com/snusnu/rails_metrics', :branch => 'datamapper-compatibility'
gem 'mustache',                     '~> 0.11.2'
gem 'thin',                         '~> 1.2.7'
gem 'sinatra',                      '~> 1.0'
gem 'nokogiri',                     '~> 1.4.1'
gem 'rdiscount',                    '~> 1.6.3'
gem 'json',                         '~> 1.2.4'
gem 'rest-client',                  '~> 1.4.2'
gem 'tzinfo',                       '~> 0.3'
gem 'isaac',                        '~> 0.2.6', :require => nil
gem 'rake',                         '~> 0.8.7'

group :development do
  gem 'rack-bug',                   '~> 0.2.2.pre', :git => "git://github.com/galetahub/rack-bug.git", :require => 'rack/bug'
end