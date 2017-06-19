task default: :server

desc 'Start a local dev server'
task :server do
  exec "ruby -run -ehttpd ."
end

desc 'Start the sass compiler'
task :sass do
  exec "bin/sass --watch sass:css"
end
