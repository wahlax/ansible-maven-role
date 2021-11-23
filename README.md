# Maven with Ansible

Role for installing and configuring Maven and a JDK dependency

## Optional Parameters

 * `mvm_version` - Version of JDK
 * `mvn_download_url` - URL of tar.gz for release
 * `mvn_download_sha256` - Checksum of tar.gz for release

Optional ansible-jdk-role parameters:
 * `jdk_version` - Version of JDK
 * `jdk_download_url` - URL of tar.gz for release
 * `jdk_download_sha256` - Checksum of tar.gz for release

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```
