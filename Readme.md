# **File Sharing Application Project (May 20, 2021)**

## Information

In this project, designed and implemented a peer-to-peer file sharing application for the Computer Networks project.

## How To Run

This python program works with 4 processes: ChunkAnnouncer, ContentDiscovery, DownloadChunk, and UploadChunk.

- The file to be transferred should be inside the python project file.
- The user should change some parts of the python files.
- In the UploadChunk.py, the user should replace line 18 with their Hamachi IPv4 address.
- In the ContentDiscovery.py, the user should replace line 24 with their Hamachi IPv4 address.

- First, you need to run ChunkAnnouncer.py and write the name of the file you want to upload (i.e., name.png). It will open a file called 'Chunk_Files'. This file contains 5 chunks. Then, you will write your username to the console. It will start to send broadcast UDP messages periodically once per minute.
- Next, you should run UploadChunk.py to start the server and upload the chunks.
- Then, you should run ContentDiscovery.py. It will create a Users.txt file. In this file, you can see all chunks that are uploaded by users in the same network.
- Finally, run DownloadChunk.py. In the console, you can see the names of the files shared in the network and the IP addresses of senders. Write the name of the file (i.e., name.png) to the console. It will open a file called 'Downloads', which contains all files you download.

- 'Client_Success.log' file shows the chunks downloaded by you.
- 'Success.log' file shows the chunks available in the network.

**Regards!**
