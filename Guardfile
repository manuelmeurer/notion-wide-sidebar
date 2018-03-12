coffeescript_options = {
  input:    '.',
  output:   'extension',
  patterns: [/\.coffee\z/]
}

guard 'coffeescript', coffeescript_options do
  coffeescript_options[:patterns].each(&method(:watch))
end

guard :haml, output: 'extension' do
  watch /\.haml\z/
end

guard :sass, output: 'extension' do
  watch /\.scss\z/
end
