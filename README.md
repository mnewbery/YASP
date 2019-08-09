 ======================================================================================<br>
                    YASP - Self Paced Assembly Language Training
                                        README
 
 GOAL:
 -----
 This training material consists of several files of assembly code, each with extensive documentation/comments 
 explaining what the code is doing. By pasting them into YASP, a web-based compiler and simulator for the code,
 readers can see what this code is doing behind the scenes and develop an idea as to what assembly code looks
 like and how it can be utilized.
 
 In building familiarity with this particular assembly code language, readers can develop skills that will help
 them learn future assembly languages much faster, or at least be able to read or follow code, such as might be
 presented in the optional Anomaly Analysis training for the Dandelion group.
 
 
 INSTRUCTIONS FOR TRAINING:
 --------------------------
 1. Open http://www.yasp.me/ and ENABLE SCRIPTS (there should be an option in the top-right of the screen with firefox).
 2. Press the "Demo" link in the top-left corner of the page (in green text).
 3. Delete the text/code on the demo page, and copy & paste the full contents of the relevant training text files into 
        the page. Start, of course, with #1 and move through them when ready.
 4. Read through the page, the comments, and follow the instructions at the bottom of the training material to 
        understand how to run the program and see how memory is being modified.
 5. If you have any questions at any time, ask me (Stuart Barker) for help. Please look for the answer to your 
        question in the comments/text of the training material first, though.
  
  
 BASIC THEORY:
 -------------
 Assembly code is a very low-level form of coding, and each assembly language is SPECIFIC to a particular form of
 computer/processor architecture. It is very closely related to 'machine code', the lowest level of code in a
 computer, which acts as the foundations of memory and data manipulation which all other forms of software
 and code (including the operating system) is built on.
 
 Assembly code is integral to the core functionality of a computer, and directly interacts with individual bytes of
 data - in something like YASP you can physically see the memory (in binary digits, even) being altered. Typically
 you see very small amounts of data being used/altered in assembly - in YASPs version, we deal with a small number of
 'byte' and 'word' registers, each only able to carry 1 or 2 bytes of data respectively. By default, each byte is shown
 as a hexadecimal value. One byte can be shown in binary as a value between 0000 0000 and 1111 1111, or Hexadecimal 
 between 00 and FF. 
 (Hex can be counted as such: 1, 2, 3, ..., 9, A, B, C, D, E, F, 10, 11, ..., 19, 1A, 1B, 1C, 1D, 1E, 1F, 20, ...)
 
 Assembly code is also an EXCELLENT way to teach the basis of how a computer actually handles data on a binary level.
 From Wikipedia: 
 "Assembly language is still taught in most computer science and electronic engineering programs. Although few programmers 
 today regularly work with assembly language as a tool, the underlying concepts remain very important. Such fundamental topics 
 as binary arithmetic, memory allocation, stack processing, character set encoding, interrupt processing, and compiler design 
 would be hard to study in detail without a grasp of how a computer operates at the hardware level. Since a computer's behavior 
 is fundamentally defined by its instruction set, the logical way to learn such concepts is to study an assembly language."
 
 More information can be found or inferred in the training material.
 
 
 ANOMALY ANALYSIS:
 -----------------
 In Anomaly Analysis - analysing and investigating malware or possible malware - it is very likely you will come across
 some form of assembly language and may want to learn how to inspect what it might be trying to do. Overwrite registry
 locations? Access sensitive locations? Delete software components? Viruses and various forms of malware often exploit
 assembly code, as it ensures it stays extremely lightweight (small in file size, which may help in avoiding detection 
 or more easily dropping it onto a computer), harder to detect, or to give it precise control over systems closer
 to the hardware level (such as re-writing or altering a device driver, such as to manipulate how a microphone or 
 camera might be functioning).
 
 Also, there are times when you may have been able to retrieve binary (low-level) files of possible malware that
 has obfuscated its source code. Obfuscating (hiding) source code is, to some degree, completely normal - you probably
 can't find the source code for a video game in its files in a human-readable format, can you? However, it is 
 sometimes possible to 're-create' files in an assembly code-like structure by checking exactly what kind of manipulations
 and changes it is making to your computer on a memory level. In doing so, you can 'boil down' an obfuscated program, by 
 using certain tools, into the essence of what it's trying to do. Hopefully. This isn't far removed from what certain
 individuals do to try to fight copy protection, as well, and not very different to "ROM-hacking" which led to the ability 
 to alter or 'mod' old video games, by altering them on an assembly-code level.
 
 SPECIAL THANKS:
 ---------------
 
 Thanks to Oliver for the suggestion to use YASP 
 Thanks to Owen for pointing out a handul of bugs and issues in the initial training material 
 Thanks to Julie for early proof-reading of these exercises

 
 
 
 
