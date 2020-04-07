# test for lfs

## config

instructions to setup custom agent https://weirdbearddev.com/resources/learning/configuring-git-lfs-to-use-dropbox/

Example for .git/config with gozilla

    [lfs "customtransfer.goz-lfs"]
        path = path_to_binary/gozilla-lfs
        args = --subject *userid* --repo *repo_for_files* --url *gozilla_url* --user *gozilla_user* --apikey *gozilla_apikey*
    [lfs]
        standalonetransferagent = goz-lfs


