
begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

task :default => 'test:run'
task 'gem:release' => 'test:run'

Bones {
  name  'tanning_bed_solr'
  authors  'Rob Kaufman'
  email    'rob@notch8.com'
  url      'http://notch8.com'
  ignore_file  '.gitignore'
}

