# 🖥️ Bit Manipulation and Subroutines -8086 Assembly

<a href="https://github.com/harismuneer"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=harismuneer&style=flat-square" width="125"/></a>
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Bit-Manipulation-and-Subroutines-8086_Assembly.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/harismuneer/Bit-Manipulation-and-Subroutines-8086_Assembly/fork)
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Bit-Manipulation-and-Subroutines-8086_Assembly.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Bit-Manipulation-and-Subroutines-8086_Assembly/issues)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)


I solved all these questions and shared the solutions here so that you can have a strong grip on these concepts with ready to run interesting solved problems.

## Reference Book

*The questions are taken from the book [Assembly Language Programming by Belal Hashmi and Junaid Haroon](https://onlinebookpoint.blogspot.com/2016/10/assembly-language-programming-delivered.html)*

Its an excellent book for understanding the language and concepts of 8086 Assembly. It starts from the very basics and then takes you to advanced concepts in an efficient manner. Highly Recommended!

## How to Run
1- Download this code and move the 'assembly_code' folder to C: directory.

2- Install DOSBOX from this link: [Download DOSBOX Emulator](https://www.dosbox.com/download.php?main=1)

3- After complete installation, go to DOSBOX installation directory and run "DOSBox 0.74 Options.bat". This will save you from the pain       of searching the configuration file yourself and will open that file for you.
Copy these lines at the end of that file:
```
mount c: c:\assembly_code 
```  
```
c:
```
4- Now to run any question (say named 'chp4_03.asm'), run DOSBOX 0.74 and type
```
nasm chp4_03.asm -o chp4_03.com  
```

To run the code, type:

```
chp4_03.com
```

To examine step by step working of the code, type

```
afd chp4_03.com
```


## Problems Solved

### Question 1: (Exercise of Chp 4 - Bit Manipulation)
* Q-1. Write a program to swap every pair of bits in the AX register.
* Q-3. Write a program to swap the nibbles in each byte of the AX register.
* Q-4. Calculate the number of one bits in BX and complement an equal number of least significant bits in AX.
* Q-5. Write a program to multiply two 32bit numbers and store the answer in a 64bit location.
* Q-6. Declare a 32byte buffer containing random data. Consider for this problem that the bits in these 32 bytes are numbered from 0 to 255.     Declare another byte that contains the starting bit number. Write a program to copy the byte starting at this starting bit number in the AX register. Be careful that the starting bit number may not be a multiple of 8 and therefore the bits of the desired byte will be split into two bytes.
* Q-7. AX contains a number between 0-15. Write code to complement the corresponding bit in BX. For example if AX contains 6; complement the 6th bit of BX.
* Q-8. AX contains a non-zero number. Count the number of ones in it and store the result back in AX. Repeat the process on the result (AX) until AX contains one. Calculate in BX the number of iterations it took to make AX one.

### Question 2: (Exercise of Chp 5 - Subroutines)
* Q-3. Write a recursive function to calculate the Fibonacci of a number. The number is passed as a parameter via the stack and the calculated Fibonacci number is returned in the AX register. A local variable should be used to store the return value from the first recursive call. Fibonacci function is defined as follows: Fibonacci(0) = 0 Fibonacci(1) = 1 Fibonacci(n) = Fibonacci(n-1) + Fibonacci(n-2)
* Q-4. Write the above Fibonacci function iteratively.
* Q-5. Write a function switch_stack meant to change the current stack and will be called as below. The function should destroy no registers. push word [new_stack_segment] push word [new_stack_offset] call switch_stack
* Q-8. Make an array of 0x80 bytes and treat it as one of 0x400 bits. Write a function myalloc that takes one argument, the number of bits. It p, and returns in AX the index of the first bit. Write another function myfree that takes two arguments, index of a bit in the array, and the number of bits. It makes that many consecutive bits zero, whatever their previous values are, starting from the index in the first argument.


<br>
<hr>


## Author
You can get in touch with me on my LinkedIn Profile: [![LinkedIn Link](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=linkedin&longCache=true&style=social&label=Follow)](https://www.linkedin.com/in/harismuneer)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/harismuneer)

If you liked the repo then kindly support it by giving it a star ⭐ and share in your circles so more people can benefit from the effort.

## Contributions Welcome
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Bit-Manipulation-and-Subroutines-8086_Assembly.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Bit-Manipulation-and-Subroutines-8086_Assembly/issues)

If you find any bugs, have suggestions, or face issues:

- Open an Issue in the Issues Tab to discuss them.
- Submit a Pull Request to propose fixes or improvements.
- Review Pull Requests from other contributors to help maintain the project's quality and progress.

This project thrives on community collaboration! Members are encouraged to take the initiative, support one another, and actively engage in all aspects of the project. Whether it’s debugging, fixing issues, or brainstorming new ideas, your contributions are what keep this project moving forward.

With modern AI tools like ChatGPT, solving challenges and contributing effectively is easier than ever. Let’s work together to make this project the best it can be! 🚀

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2018-present, harismuneer                                 

<!-- PROFILE_INTRO_START -->

<hr>

<h1> <a href="#"><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="Waving hand" width="28"></a>
Hey there, I'm <a href="https://www.linkedin.com/in/harismuneer/">Haris Muneer</a> 👨🏻‍💻
</h1>


<a href="https://github.com/harismuneer"><img src="https://img.shields.io/github/stars/harismuneer" alt="Total Github Stars"></a>
<a href="https://github.com/harismuneer?tab=followers"><img src="https://img.shields.io/github/followers/harismuneer" alt="Total Github Followers"></a>

<hr>

- <b>🛠️ Product Builder:</b> Agile Product Manager with 5+ years of hands-on experience delivering SaaS solutions across sales, recruiting, AI, social media, and public sector domains. Background in Computer Science, with a proven track record of scaling products from inception to $XXM+ ARR, launching 3 top-ranking tools on Product Hunt, and developing solutions adopted by 250+ B2B clients in 40+ countries.  
 
- <b>🌟 Open Source Advocate:</b> Passionate about making technology accessible, I’ve developed and open-sourced several software projects for web, mobile, desktop, and AI on my <a href="https://github.com/harismuneer">GitHub profile</a>. These projects have been used by thousands of learners worldwide to enhance their skills and knowledge.

- <b>📫 How to Reach Me:</b> To learn more about my skills and work, visit my <a href="https://www.linkedin.com/in/harismuneer">LinkedIn profile</a>. For collaboration or inquiries, feel free to reach out via <a href="mailto:haris.muneer5@gmail.com">email</a>. For Cyfy Labs related queries, please contact us through our <a href="https://www.cyfylabs.com">company website</a>.

<hr>

<h2 align="left">🤝 Follow my journey</h2>
<p align="left">
  <a href="https://www.linkedin.com/in/harismuneer"><img title="Follow Haris Muneer on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/harismuneer"><img title="Follow Haris Muneer on GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.youtube.com/@haris_muneer?sub_confirmation=1"><img title="Subscribe on YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a> 
  <a href="mailto:haris.muneer5@gmail.com"><img title="Email" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>



<!-- PROFILE_INTRO_END -->




