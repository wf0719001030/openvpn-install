
1. opensetup()
   1. user check(need root)
   2. chekc kernel
   3. check_os()
      1. ubuntu, debian, centos, fedora
   4. check_os_ver()
   5. tun check
   6. check /etc/openvpn/server/server.conf
      1. not installed openvpn
         1. check_nftables()
            centos特殊处理
         2. check parmeter
            
         3. install_wget
         4. install_iproute
         5. show_start_setup
         6. detect_ip
         7. check_nat_ip
         8. show_config
         9. detect_ipv6
         10. select_protocol
         11. select_port
         12. select_dns()
         13. enter_client_name()
            validate name
         14. confirm_setup()
         15. install openvpn(with apt-get/yum/....)
         16. firewall set(if installed)
         17. download/install easy-rsa(作为PKI 签发根证书使用)
             1.  

      2. 
   7. asdf 
   8. 