# jarbuilder
jRAT tool for exporting output as executable

Original author: bausshacker

Argument order
- Input file
- File name
- Icon file
- Title
- Description
- Company
- Product
- Copyright
- Trademark
- Version
- Assembly version

Output file is always written to %temp%

After ran and written the dropped jar to disk, it will try to execute it. JRE needs to be present on the system, and default for opening JAR files