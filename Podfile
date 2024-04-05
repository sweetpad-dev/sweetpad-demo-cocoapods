platform :ios, '15.0'

target 'sweetpad-demo-cocoapods' do
  pod 'SwiftUIWebView', '~> 1.0.8'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
   target.build_configurations.each do |config|
    config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '15.0'
   end
  end
 end