# coding: utf-8
# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    # 使用するboxファイル
    config.vm.box = "bento/centos-7"

    # ゲストOSのホスト名とプライベートIP
    config.vm.define "laravelvm" do |lvm|
        lvm.vm.network "private_network", ip: "192.168.16.132"
    end

    # ゲストOS毎に異なる公開鍵を使用しない
    config.ssh.insert_key = false
end
