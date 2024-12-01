***Release Script***

**Usage**

Script create_release.sh requires 4 parameters:

repository name, github-api token, path to the apk to be uploaded and a version.

```./create_release.sh hhadzimahmutovic/test_repository <api-key> <path_to_file> <version>```

The script is used to create a new release for the repository if the provided version of release does not exist, then upload the file to the release which was created in the previous step.



