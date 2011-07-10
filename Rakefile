desc 'Generate HTML and CSS files'

task :generate do
  `haml src/index.html.haml > index.html && sass src/application.css.scss > styles/application.css`
end

task :default => :generate
