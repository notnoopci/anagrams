require 'rake/testtask'

Rake::TestTask.new do |t|
  t.pattern = 'test/**/*_spec.rb'
end

task :default do
  Rake::Task['test'].invoke
end
