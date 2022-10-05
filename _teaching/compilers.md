---
layout: archive
permalink: /teaching/compilers/
title: "C++ Compilers Installation"
author_profile: true
#collection: teaching
---

Each student should install a C++ compiler on your local computer. Depending on the operating systems, students should download and install different compilers.

For Windows OS users, install Visual Studio 2022 community.
---
* You can download the software [here](https://visualstudio.microsoft.com/vs/). Choose "Download Visual Studio Community 2022". This is the free version.
* When installing the software, choose the "Desktop development with C++" workload.
* To run C++ code on VS2022, you must build projects with VS2022 first. Here are step-by-step instructions. The tutorials are made using VS2019, but you can follow the same steps to run C++ with VS 2022.
    * Create a blank project and run C++ [post](https://www.pic.ucla.edu/getting-started-with-microsoft-visual-studio-2019/)
    * A video on how to create projects and run C++ code [video](https://drive.google.com/open?id=19SgBvEt8olEaTbo6WnGIYxqb3IbekJiz)
    * A video on run existing C++ code snippets with Visual Studio 2022 (Spoiler alert: you must create a project first) [video](https://drive.google.com/open?id=1b5zSI4H9nNv3_vJtRCPuPtnRG3qPV-zy)

For Mac OS users, install Xcode (any version).
---
* Some MacBook computers may have installed Xcode already. If not, you can download the most recent Xcode [here](https://developer.apple.com/xcode/)
* To run C++ code on Xcode, you must create a project first. Here are demo videos made by Prof. [Micheal Andrews](https://www.math.ucla.edu/~mjandr/) on how to run C++ code with Xcode. (Spoiler alert: you must create projects with Xcode first.)
    * Creating a blank project and run C++ code [video](https://drive.google.com/open?id=1zu-fbDBu1w86CDrXtcA9-J4LrkIX7eBA)
    * Create a project using code snippets [video](https://drive.google.com/open?id=1nYun2gefcHs0_EqmaZJcfVhztcMTQncw)

Official compiler -- Visual Studio 2022
---
There are subtle differences between different compilers when it comes to compiling C++ code. Some code will compile with one compiler but not another one. To avoid the discrepancy between compilers, we will use "Visual Studio 2022" as the "official" compiler to grade homework and all course-related materials. 

Mac OS is not compatible with Visual Studio 2022 Community edition. For Mac users, to make sure your code work with the official compiler, double check the code with a Windows computer installed with Visual Studio 2022. You can find Windows desktops available in PIC lab or UCLA libraries. 

Common questions related to compilers (IMPORTANT! Please read!)
---
* Do I have to own a Windows computer to take this class? Do I have to at least own a computer to take this class?
* NO and NO. Having your own computer would be handy in doing homework, but you don't have to own a computer to take this class. There are computers available for students to use in PIC Lab (Mathematical Sciences Building 2000) and UCLA libraries, and these computers have installed Visual Studio 2022 already. You don't need to bring laptops to classes or exams.

* Somehow I can't run my code with VS2022 (or Xcode). Why is this happening?
* There are multiple reasons that can lead to that, but the most common reason is as follows. To run C++ code with Visual Studio or Xcode, users must create projects (solutions) first before running the code. If you don't know how to build projects, see step-by-step demo videos above to find out how to create C++ projects from scratch and how to create projects for existing code snippets.

* I'm a Mac user. What if my code works with Xcode but does not work with Visual Studio 2022? Do I lose points for my homework because of that?
* We will only use Visual Studio 2022 to grade your homework. If your code does not compile with VS2022, you will lose points for the homework, no matter if your code compiles with Xcode. To avoid such situations, always test your code with a Windows computer which has installed VS2022 before homework submission. If no error is detected, you are ready to submit your homework, but if error is detected, revise your code according to the error message until the code compiles and gives you the satisfactory results.

* I'm a Mac user. I see there is "Visual Studio 2022 for Mac" or "Visual Studio Code" available online. Can I use those instead?
* "Visual Studio 2022 for Mac" does not support C++ language, so you can't use it for this course. ("Visual Studio 2022 for Mac" supports C# but C# is not C++). "Visual Studio Code" is only a code editor (not a compiler), so you cannot use it on its own and it can't replace a real compiler (like Xcode or VS2022).
