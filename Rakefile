include FileUtils

LayoutFiles = {
    OSX: 'Workman-LP.bundle/'
}

task :install do |t|
    cp_r LayoutFiles[:OSX], "#{Dir.home}/Library/Keyboard Layouts", verbose: true
end

task :uninstall do |t|
    rm_r "#{Dir.home}/Library/Keyboard Layouts/#{LayoutFiles[:OSX]}", verbose: true
end

