# vagrant-debian-rust: a Vagrant box for building Rust binaries for GNU/Linux (Debian)

# VAGRANT CLOUD

https://app.vagrantup.com/mcandre/boxes/vagrant-debian-rust

# EXAMPLE

```console
$ vagrant up
$ vagrant ssh -c "cd /vagrant && rustc hello.rs && ./hello"
Hello World!
```

# REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* A VM provider, such as [VirtualBox](https://www.virtualbox.org), [VMware](https://www.vmware.com), or [libvirt](https://libvirt.org)

# EXPORT

```console
$ vagrant destroy -f; vagrant up && vagrant package --output vagrant-debian-rust.box
```