# frozen_string_literal: true

namespace :ci do
  desc 'Create a release PR for current branch'
  task :create_release_pr do |_task, _args|
    current_branch = ENV['GITHUB_REF'].gsub('refs/heads/', '')
    pp current_branch
  end
end


