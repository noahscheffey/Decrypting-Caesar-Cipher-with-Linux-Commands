<h1>Decrypting Caesar Cipher with Linux Commands</h1>

<h2>Objective:</h2>

To decrypt Caesar cipher-encrypted files within a home directory using Linux commands, thereby recovering the hidden messages they contain. This demonstrates the application of command-line tools for basic cryptanalysis and data recovery.

<h2>Procedure</h2>

**Directory Exploration and File Examination:**

The contents of the home directory were explored using the 'ls' command to identify files, including hidden ones.

<img src="https://i.imgur.com/bureEsB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The 'cat' command was used to read the contents of a file, allowing for initial inspection of the encrypted data.

<img src="https://i.imgur.com/LLqGXek.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   
**Hidden File Decryption:**

A hidden file containing a Caesar cipher-encrypted message was located (likely using ls -a).

A Python script or the 'tr' command was used to perform the Caesar cipher decryption with a shift of 3. For example, the 'tr' command can be used as follows: 'tr' 'DEFGHIJKLMNOPQRSTUVWXYZABCdefghijklmnopqrstuvwxyzabc' 'ABCDEFGHIJKLMNOPQRSTUVWXYZABCdefghijklmnopqrstuvwxyzabc' < encrypted_file > decrypted_file

<img src="https://i.imgur.com/bE9qNSB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The decrypted message was then displayed.

**Encrypted Data File Decryption and Message Recovery:**

Another encrypted data file was located and decrypted using the same Caesar cipher decryption method (shift of 3).

A Python script or the 'tr' command was used to perform the Caesar cipher decryption with a shift of 3. For example, the tr command can be used as follows: tr 'DEFGHIJKLMNOPQRSTUVWXYZABCdefghijklmnopqrstuvwxyzabc' 'ABCDEFGHIJKLMNOPQRSTUVWXYZABCdefghijklmnopqrstuvwxyzabc' < encrypted_file > decrypted_file

The decrypted data was then examined to reveal the hidden message.

<h2>Tools Used:</h2>

'ls': To list directory contents.

'cat': To display file contents.

'tr': To perform character substitution (Caesar cipher decryption).

'Python': Could also be used to write a decryption script.

<h2>Findings:</h2>

The Caesar cipher encryption was successfully reversed using Linux commands. The hidden messages within the files were recovered, demonstrating the vulnerability of this simple cipher.

<h2>Conclusion:</h2>

This exercise demonstrates a basic example of cryptanalysis using Linux commands. While the Caesar cipher is easily broken, it illustrates the fundamental principles of encryption and decryption. This process highlights the importance of using strong encryption algorithms to protect sensitive data.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
