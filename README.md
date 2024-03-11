# electron

Breaking changes in Electron 23 version for net library network calls. ( Server is no more receiving the cookie whenver 302 redirect happen in server side)

Steps to reproduce - 1. Server is no more receiving cookie in electron 23 version whenever the api is doing 302 redirect, 2. Electron 22 version is sending the cookie properly ...Please note you need to enable 302 redirect whenever you want to replicate the issue. Below are code which i using - 
<img width="863" alt="image" src="https://github.com/electron/electron/assets/5560623/6c72402e-55cc-4ecc-b8bc-3e224aa29285">....Please let me know if you need more details

Whenever server is doing 302 redirect electron version should send the cookie ...In electron version 22 its working as expected.
