use_frameworks!
inhibit_all_warnings!

#////////////////////////////////////////////////////////////////////////////////
#////////////////////////////////////////////////////////////////////////////////
def common_ios

    pod 'Aspects',    '1.4.1'
    pod 'SDWebImage', '3.7.3'

end

#////////////////////////////////////////////////////////////////////////////////
#////////////////////////////////////////////////////////////////////////////////
def common

    pod 'KTCenterFlowLayout', :git => 'git@github.com:mlloyd/KTCenterFlowLayout.git'

end

#////////////////////////////////////////////////////////////////////////////////
#// Targets
#////////////////////////////////////////////////////////////////////////////////
target :PodExample do
    platform :ios, '8.0'
    common
    common_ios
end

#////////////////////////////////////////////////////////////////////////////////
#////////////////////////////////////////////////////////////////////////////////
target :PodExampleCore do
    platform :ios, '8.0'
    common
    common_ios
end

#////////////////////////////////////////////////////////////////////////////////
#////////////////////////////////////////////////////////////////////////////////
target :PodExample_tvOS do
    platform :tvos, '9.0'
    common
end

#////////////////////////////////////////////////////////////////////////////////
#////////////////////////////////////////////////////////////////////////////////
target :PodExampleCore_tvOS do
    platform :tvos, '9.0'
    common
end
