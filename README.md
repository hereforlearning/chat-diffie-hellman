[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# CryptChat
> CryptChat is a secure chat between an Android client and Java server based on TCP/IP socket connection.

This chat uses the Diffie-Hellman algorithm for the exchange of public keys and the AES algorithm for the encryption/decryption of messages. The public key carries different parameters which can be seen by anyone, it is needed to generate a common secret key. Both client and server generate a key pair, the public key mentioned before and private key used to decrypt every message. The common secret key (generated by the Diffie-Hellman algorithm) encrypts the messages. The message sent over the network socket are encoded in BASE64.

Client             |  Server
:-------------------------:|:-------------------------:
![](https://github.com/ejupialked/CryptChat/blob/master/art/client.gif?raw=true)  | ![](https://github.com/ejupialked/CryptChat/blob/master/art/server.gif?raw=true)

## Motivation
This personal project was created in my final year of high school in 2017. I presented this project during my final oral exam which was about Computer Security. After high school my coding skills have improved, that's why I decided to refactor the code making the chat more secure. 

## Project Status

This project is currently in development. Currently I'm working on making the code more readable and maintainable. If there are any issues let me know or open a pull request. Very soon I will upload a guide on how to run and clone this repo on your machine so that you can use it and learn.

## Screenshots
### Client
![Client](https://github.com/EjupiAlked/CryptChat/blob/master/art/art.PNG?raw=true)
### Server
![Server](https://github.com/EjupiAlked/CryptChat/blob/master/art/artServer.png?raw=true)
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

Alked Ejupi - ejupialked@outlook.com
