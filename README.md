# Network Password Checker (netpw)
Tool written in Bash with which you can check the password of the network you specify. Also, you can perform brute force dictionary attacks.

## Installing
```bash
git clone https://github.com/h3g0c1v/netpw
cd netpw
chmod u+x netpw
./netpw
```

## Use
Its use is as follows

```bash
./netpwn -n <Network Name> -p <Network Password>
```

![Checking the network password](https://github.com/user-attachments/assets/7659e79d-51e9-4865-b29f-d09bbf9b8fbd)

If you want to perform a brute force attack, you can use it as follows.

```bash
./netpwn -n <Network Name> -d <Password Dictionary>
```

![Brute Force Attack](https://github.com/user-attachments/assets/1dca81ca-300c-4b25-920c-5ee0b040f112)

I hope it helps you <3
