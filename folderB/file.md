This file is in folderB

[file in C (md relative link)](folderC/file.md)

[file in C (md absolute link)](/folderB/folderC/file.md) this doesn't work, the MD file link will be used

{{ "/folderB/folderC/file.md" | relative_url }}

{{ "folderB/folderC/file.md" | relative_url }}

{{ "/folderB/folderC/file.md" | absolute_url }}

{{ "folderB/folderC/file.md" | absolute_url }}
