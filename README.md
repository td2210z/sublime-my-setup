Installation

1. Download the folder above
2.Go to Sublime and select Preferences -> Browe Package
3. Copy all the folders you just downloaded into that file.

Good luck!!


Screenshots

Dark Theme
![](https://github.com/Tieucuc2210/sublime-my-setting/blob/master/short/dark.png)

Light Theme

![](https://github.com/Tieucuc2210/sublime-my-setting/blob/master/short/light.png)


Trans Theme
![](https://github.com/Tieucuc2210/sublime-my-setting/blob/master/short/trans.png)




Tools Build C++


<pre>


{
  "cmd": ["g++.exe", "-std=c++17", "${file}",
      "-o", "${file_base_name}.exe",
      "&&", "${file_base_name}.exe<nhap.in"],
  "shell":true,
  "working_dir":"$file_path",
  "selector":"source.cpp"
}

</pre>


