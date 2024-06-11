> ℹ️ Issues for this repository are tracked on [Phabricator](https://phabricator.wikimedia.org/project/board/5563/) - ([Click here to open a new one](https://phabricator.wikimedia.org/maniphest/task/edit/form/1/?tags=wikibase_cloud
))

# mediawiki-tars
These tarballs contain Wikibase releases, cloned with submodules but stripped of git-related data.

## How to use
- run the GitHub Action workflow to create a new tarball: https://github.com/wbstack/mediawiki-tars/actions/workflows/packager.yml

## Background
We tried to use the extension archives distributed by the WMF https://phabricator.wikimedia.org/T361202#9739913

But they don't seem to be kept long enough around for us https://github.com/wbstack/mediawiki/pull/443
