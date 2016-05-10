source 'https://github.com/CocoaPods/Specs.git'

platform :osx, '10.8'
workspace 'CotEditor'


abstract_target 'app' do
    project 'CotEditor/CotEditor'

    pod 'OgreKit',
        :git => 'https://github.com/coteditor/OgreKit.git',
        :branch => 'coteditor-mod-nofindpanel'
    pod 'YAML-Framework',
        :git => 'https://github.com/coteditor/YAML.framework.git',
        :branch => 'coteditor-mod'
    pod 'NSHash'
    pod 'WFColorCode'


    target 'CotEditor' do
        pod 'Sparkle'
    end

    target 'CotEditor -AppStore'
end
