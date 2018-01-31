# SMSP-Compiler-For-Mathematica

SMSP(Standard Musical String Protocol) is a set of rules on how to interpret text into music. [SMSP编译器测试.nb](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/SMSP编译器测试.nb) is a Mathematica version realization (compiler) about this idea. This compiler is capable of converting the TXT inputs into music files (format MID or WAV).

[SMSP入门手册-未完成.docx](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master//SMSP入门手册-未完成.docx) describes the grammar of SMSP and how to use this compiler to create music.

## Demo projects

File [例子.nb](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/例子.nb) shows how to use this compiler to create real music works, demo songs are:

- [helloworld.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/helloworld.txt)
- [字母歌.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/字母歌.txt)
- [字母歌KS.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/字母歌KS.txt)
- [幻化成风.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/幻化成风.txt)
- [AlphaChord示范曲.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/AlphaChord示范曲.txt).

The last one was created by [@LePtC](https://github.com/LePtC), for more detail please check his [AlphaChord](https://github.com/LePtC/AlphaChord/) project.

## Include files

[beats.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/chords.txt) and [chords.txt](https://github.com/yxlllc/SMSP-Compiler-For-Mathematica/raw/master/chords.txt) are necessary include files for the demo projects. These include files were also created by [@LePtC](https://github.com/LePtC). The author deeply appreciate his great contribution to SMSP.

## Recommended configuration environment

At least 10.0 version of Mathematica can successfully compile all project files except [字母歌KS.txt]，which needs at least 11.0 version of Mathematica. 
It is unclear whether it will work properly under the Linux or Mac Os operating system.
So the recommended configuration environment now is: 11.0(+) Mathematica + Windows 10
