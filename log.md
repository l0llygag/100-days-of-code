# 100 Days Of Code - Log

### Day 1: June 29, 2020

**Today's Progress**: Made progress with implementing HTTP/1.1 server. Server perfectly handles all GET requests to text/* mime-types.

**Thoughts**: I am facing a very weird issue where all non-"text/*" mime-types are not rendered properly by the browser. Potentially because of how I am writing to the socket. I have to find it's cause and solution tommorrow.

**Link(s) to work**: https://github.com/l0llygag/kota

### Day 2: June 30, 2020

**Today's Progress**: Fixed the issue faced yesterday. Added gradle build configuration, logging and readme.md and made the project public.

**Thoughts**: The issue was due to using PrintWriter class to write to the socket, which is used for writing text. I instead used OutputStream and now write directly bytes to the socket. Have to add documentation to the project.

**Link(s) to work**: https://github.com/l0llygag/kota
