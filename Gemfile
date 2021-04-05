# frozen_string_literal: true

# source "https://mirrors.tuna.tsinghua.edu.cn/rubygems"
source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "cocoapods", "1.10.1"
gem "fastlane", "2.179.0"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
