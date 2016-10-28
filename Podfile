# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

def testing_pods
  pod 'Quick', '~> 0.10.0'
  pod 'Nimble', '~> 5.1.0'
end

target 'chat' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for chat
  pod 'SwiftyJSON', '3.1.1'
  pod 'SnapKit', '~> 3.0.2'
  pod 'RealmSwift', '2.0.2'
  pod 'RxRealm', '0.2.6'
  
  pod 'RxSwift', '3.0.0'
  pod 'RxCocoa', '3.0.0'
  
  pod 'Moya', '8.0.0-beta.3'
  pod 'Moya/RxSwift', '8.0.0-beta.3'

  pod 'Alamofire', '4.0.1'
  pod 'Then', '~> 2.1'

  target 'chatTests' do
    inherit! :search_paths
    testing_pods
  end

  target 'chatUITests' do
    inherit! :search_paths
    testing_pods
  end

end
