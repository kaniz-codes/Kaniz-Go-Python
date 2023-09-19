# Kaniz-Go-Python
-  This code creates a simple web browser application using PyQt5. It features navigation buttons (Back, Forward, Reload), a URL input field, and a web browser view that allows users to browse websites. It's a basic example of how to build a web browser-like application in Python.

1️⃣ 𝐈𝐦𝐩𝐨𝐫𝐭𝐢𝐧𝐠 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐝 𝐌𝐨𝐝𝐮𝐥𝐞𝐬:

![codeimage-snippet_19](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/5bb3aa3f-94d7-489d-bb08-4f202aa3c1bb)

- 'sys' is imported to access command-line arguments.
  𝐐𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧, 𝐐𝐌𝐚𝐢𝐧𝐖𝐢𝐧𝐝𝐨𝐰, 𝐐𝐖𝐞𝐛𝐄𝐧𝐠𝐢𝐧𝐞𝐕𝐢𝐞𝐰, and other classes from PyQt5 are imported for building the GUI application.

2️⃣ 𝐂𝐫𝐞𝐚𝐭𝐢𝐧𝐠 𝐭𝐡𝐞 𝐌𝐚𝐢𝐧 𝐖𝐢𝐧𝐝𝐨𝐰:

![codeimage-snippet_19 (1)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/aad781dc-203e-4aa8-8489-d588c016e814)

- This code defines a custom class 𝐌𝐚𝐢𝐧𝐖𝐢𝐧𝐝𝐨𝐰 that inherits from 𝐐𝐌𝐚𝐢𝐧𝐖𝐢𝐧𝐝𝐨𝐰. This class will represent the main window of the application.

3️⃣ 𝐒𝐞𝐭𝐭𝐢𝐧𝐠 𝐔𝐩 𝐭𝐡𝐞 𝐖𝐞𝐛 𝐁𝐫𝐨𝐰𝐬𝐞𝐫 𝐕𝐢𝐞𝐰:

![codeimage-snippet_19 (2)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/e30c248d-ca4c-48f3-b40a-ce130db6572c)

- 𝐐𝐖𝐞𝐛𝐄𝐧𝐠𝐢𝐧𝐞𝐕𝐢𝐞𝐰() creates a web browser view widget.
.𝐬𝐞𝐭𝐔𝐫𝐥(𝐐𝐔𝐫𝐥('𝐡𝐭𝐭𝐩://𝐠𝐨𝐨𝐠𝐥𝐞.𝐜𝐨𝐦')) sets the initial URL for the web browser to "𝐡𝐭𝐭𝐩://𝐠𝐨𝐨𝐠𝐥𝐞.𝐜𝐨𝐦."
𝐬𝐞𝐥𝐟.𝐬𝐞𝐭𝐂𝐞𝐧𝐭𝐫𝐚𝐥𝐖𝐢𝐝𝐠𝐞𝐭(𝐬𝐞𝐥𝐟.𝐛𝐫𝐨𝐰𝐬𝐞𝐫) sets the browser view as the central widget of the main window.
𝐬𝐞𝐥𝐟.𝐬𝐡𝐨𝐰𝐌𝐚𝐱𝐢𝐦𝐢𝐳𝐞𝐝() maximizes the main window.

4️⃣ 𝐂𝐫𝐞𝐚𝐭𝐢𝐧𝐠 𝐭𝐡𝐞 𝐍𝐚𝐯𝐢𝐠𝐚𝐭𝐢𝐨𝐧 𝐓𝐨𝐨𝐥𝐛𝐚𝐫:

![codeimage-snippet_19 (4)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/681433dc-f609-4448-bb4a-eb46dff11530)

- This code creates a toolbar (𝐧𝐚𝐯𝐛𝐚𝐫) and adds it to the main window.

5️⃣ 𝐀𝐝𝐝𝐢𝐧𝐠 𝐍𝐚𝐯𝐢𝐠𝐚𝐭𝐢𝐨𝐧 𝐀𝐜𝐭𝐢𝐨𝐧𝐬 (𝐁𝐮𝐭𝐭𝐨𝐧𝐬):

![codeimage-snippet_19 (5)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/5d85f9b1-5c09-44d8-9f4d-5e912fdca0df)


- Similar blocks of code create navigation buttons for "Back," "Forward," and "Reload." These buttons are added to the toolbar and connected to corresponding functions.

6️⃣ 𝐀𝐝𝐝𝐢𝐧𝐠 𝐚 𝐔𝐑𝐋 𝐈𝐧𝐩𝐮𝐭 𝐅𝐢𝐞𝐥𝐝:

![codeimage-snippet_19 (6)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/cb99d2aa-9d00-4b8e-9859-b57926dc5326)


This code creates a QLineEdit widget for entering URLs and adds it to the toolbar. The 𝐫𝐞𝐭𝐮𝐫𝐧𝐏𝐫𝐞𝐬𝐬𝐞𝐝 signal of the input field is connected to the 𝐧𝐚𝐯𝐢𝐠𝐚𝐭𝐞_𝐭𝐨_𝐮𝐫𝐥 function.

7️⃣ 𝐔𝐩𝐝𝐚𝐭𝐢𝐧𝐠 𝐔𝐑𝐋 𝐢𝐧 𝐭𝐡𝐞 𝐈𝐧𝐩𝐮𝐭 𝐅𝐢𝐞𝐥𝐝:

![codeimage-snippet_19 (7)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/a8f56270-7798-4b1c-b51d-c2d45a218f1c)

This line connects the 𝐮𝐫𝐥𝐂𝐡𝐚𝐧𝐠𝐞𝐝 signal of the web browser to the 𝐮𝐩𝐝𝐚𝐭𝐞_𝐮𝐫𝐥 function. It ensures that the URL input field gets updated when the web page URL changes.

8️⃣ 𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐈𝐧𝐢𝐭𝐢𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐄𝐱𝐞𝐜𝐮𝐭𝐢𝐨𝐧:

![codeimage-snippet_19 (8)](https://github.com/kaniz-codes/Kaniz-Go-Python/assets/138873297/bc03aa71-7021-45f1-949d-171773e6675c)

The 𝐐𝐀𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧 class is initialized with 𝐬𝐲𝐬.𝐚𝐫𝐠𝐯 and given the application name "Kaniz GO."
An instance of the 𝐌𝐚𝐢𝐧𝐖𝐢𝐧𝐝𝐨𝐰 class is created.
Finally, the application enters the event loop with app.exec(), allowing the GUI to run.



