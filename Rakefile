require "rubygems"
gem 'hoe', '>= 2.1.0'
require 'hoe'

Hoe.plugin :gemspec # `gem install hoe-gemspec`

Hoe.spec 'arel' do
  developer('Aaron Patterson', 'aaron@tenderlovemaking.com')
  developer('Bryan Halmkamp', 'bryan@brynary.com')
  developer('Emilio Tagua', 'miloops@gmail.com')
  developer('Nick Kallen', 'nick@example.org') # FIXME: need Nick's email

  self.readme_file      = 'README.markdown'
  self.extra_rdoc_files = FileList['README.markdown']
  self.extra_dev_deps << ['rspec', '~> 1.3.0']
  self.testlib = :rspec
end

desc "Default task is to run specs"
task :default => :spec
