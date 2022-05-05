# How to use the config
1. Clone this repository to your local machine
2. Add `Include <CLONE_DIRECTORY>/wato_ssh_config/wato` to your `~/.ssh/config` file[^1], where `<CLONE_DIRECTORY>` is the directory in which you cloned this repository
3. Open `<CLONE_DIRECTORY>/wato_ssh_config/wato` and replace `<YOUR_CLUSTER_USERNAME>` with the username you chose on https://watonomous.github.io/infra-config/onboarding-form/

[^1]: If you do not have such a file, simply create one: `touch ~/.ssh/config`. To learn about SSH config files, see this [article](https://linuxize.com/post/using-the-ssh-config-file/).
