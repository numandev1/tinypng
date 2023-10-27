# Image compression software
Based on TinyPNG Api compression software, it can be installed and run directly without relying on any third-party packages and libraries.


Daily development often uses [tinypng.org](https://tinypng.org/) image batch compression. The average compression rate of TinyPNG can reach 60%. The loss of image quality that can be observed by the naked eye is minimal, which improves page loading speed and experience. , saving user traffic and shrinking the program package are of great help.

When there were too many pictures in the project, compression through the official website was inefficient and cumbersome, so I initially used Go to write a CLI program based on the TinyPNG API. The operation was not very convenient. With my love for form software and a learning mentality, I decided to write a GUI in C++. program.


##### download:
[Download the installer for Windows>>](https://github.com/yongplus/tinypng/releases/tag/1.0.1)
[Download the installer for MacOS>>](https://github.com/yongplus/tinypng/releases/tag/1.0.1)

### Screenshots
 
<img src="./assets/Screenshot3.png" width="600px" />
<img src="./assets/Screenshot1.png" width="600px" />
<img src="./assets/Screenshot2.png" width="600px" />


##### MacOS version

<img src="./assets/mac2.jpeg" width="600px" />
<img src="./assets/mac1.jpeg" width="600px" />


### Configuration
~~TinyPNG Key is free. In order to use it directly after installation, there are already 2 Keys in the software source code. After installation, one will be randomly configured for use. Each Key can be compressed 500 times for free per month. If it is not enough, you can apply for a few more (application is very simple, just fill in your email and nickname, you will receive an email, just follow the link in the email to create a key);~~
Since the TinyPNG server is abroad, domestic access is slow. If you have a foreign agent, you can configure it to speed it up.
**2021/08/11 Added key-free mode, now you don’t need to apply for a key. (The original KEY mode is retained at the same time)**

### Usage
  There are two ways to add the files:
  1.Click the button on the top-left to choose one or more files or a folder.
  2.Recommended way, For more convenient and efficient, The software supports the object can be dragged directly into the area of table in the window.
  3. push the button by a shortcut key associated with the button, For example: press Ctrl+O to add object, Ctrl+S to start task.
  4.Double-Clicking the any row in the table, the picture associated with row will preview in system image previewer.
  5.Either right-Clicking on the any rows or selecting rows and pressing key Del delete the rows.

  Remark: If the object you gave is a folder, the software will list automatically recursively all the image files in that folder.


### Comparisons
The following is the image compression test data for the product details page of the e-commerce project. The improvement in both page size and access speed is significant.
![Screenshot](https://github.com/yongplus/tinypng/blob/master/assets/compared.png?raw=true)


##### Disclaimer
This warehouse is only for learning. For commercial purposes, please purchase the official pro version: https://tinify.com/checkout/web-pro

This Repo is only for study.
