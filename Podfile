# Uncomment this line to define a global platform for your project
install! 'cocoapods',
:deterministic_uuids => false

def database
    pod 'RealmSwift', '~>2.8.1'
end
def ui
    pod 'SDWebImage', '~>3.8.2'
end
def tracking
    pod 'Fabric', '~>1.6.11'
    pod 'Crashlytics', '~>3.8.4'
    pod 'Mixpanel', '~>3.1.2'
end

target 'Randomizer' do
    platform :ios, '9.0'
    use_frameworks!
    database
    ui
    tracking
end

