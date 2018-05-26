# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'FoodTaskerMobile' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for FoodTaskerMobile

  # target 'FoodTaskerMobileTests' do
  #  inherit! :search_paths
    # Pods for testing
  # end

  # target 'FoodTaskerMobileUITests' do
  #   inherit! :search_paths
    # Pods for testing
  # end

  pod 'Stripe'
  pod 'FBSDKCoreKit'
  pod 'FBSDKLoginKit'
  pod 'FBSDKShareKit'
  pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git'
  pod 'SwiftyJSON', :git => 'https://github.com/BaiduHiDeviOS/SwiftyJSON.git', :branch => 'swift3'
  pod 'Charts', :git => 'https://github.com/danielgindi/Charts.git'
  plugin 'cocoapods-keys', {
      :project => "FoodTaskerMobile",
      :keys => [
        "ClientSecret"
      ]}
end
