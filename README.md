

Note: Wiki markdown and Docs markdown should be identical because we implement a custom renderer in Docsify for Wiki markdown

CI script in Docs repo has a Webhook on Wiki update:

update submodule
copy wiki updates to docs folder
push to Docs repo

Now need to add CI script to update Wiki when PRs to Docs are merged:

git checkout -b wiki_changes