> ## Anti-Racism Announcement!
> ### WE ABSOLUTELY DISALLOW PROVIDING OUR SERVICE/PRODUCT/WHITE-LABEL TO ANY RACIST OR RACIST-SUPPORTED BUSINESS.
> ### ESPECIALLY AGAINST A NOTORIOUS RACIST JESSE NICKLES, HE IS ABSOLUTELY ON OUR BLACKLIST FOREVER!
> ### TO KNOW WHO JESSE NICKLES IS AND WHAT HE IS DOING, PLEASE CHECK THIS REVIEW POSTED BY A VICTIM:
> https://wpjohnny.com/littlebizzy-jesse-nickles-fraud-slander-alert/
>
> https://slickstack.icu/
> ### OR THIS CLAIM(TO TAKE DOWN HIS INDEX ON GOOGLE) SUBMITTED BY ANOTHER VICTIM
> https://www.lumendatabase.org/notices/28558356
> ### OR THIS LAWSUIT AGAINST HIM BY HIS ALMA MATER
> https://cite.case.law/frd/304/594/
> ### JESSE NICKLES' GITHUB USERNAME: jessuppi

# Expert-Advisor-Cpp-Compiler

This is a Nodejs package to help Fintechee's users compile C/C++/MQL source codes(to make the expert advisors runnable on browser). It will be installed on your local PC. So, network is not required to compile your C/C++/MQL source files.

To know more details about Fintechee, please access our official website: https://www.fintechee.com or our main Github repo: https://github.com/fintechee/Expert-Advisor-Studio

![Fintechee C/C++/MQL compiler](https://github.com/fintechee/Expert-Advisor-Cpp-Compiler/blob/main/cpp.png)
![Fintechee C/C++/MQL compiler](https://raw.githubusercontent.com/fintechee/Expert-Advisor-Cpp-Compiler/main/cppcompiler.png)

## Prerequisite
Emscripten is required to compile C/C++/MQL files.
So, you need to install it in advance.
https://emscripten.org/docs/getting_started/downloads.html#installation-instructions

## Usage
1. Installation

- Download the git repo, and then extract the zip file.
- cd the directory
- npm i

2. Run

- node app.js
- Access https://www.fintechee.com/web-trader/
- Click the "Console" on the menubar(on the left of the page).
- Choose "C/C++" tab on the panel.
- Open your C/C++ file and then click "Generate Indicator" or "Generate EA". C/C++ source codes and a JSON string will be generated. You can modify your original source codes by the generated codes. The generated parts are used to define the meta information of your program, such as the variables and data output and can be helpful to make your original codes compilable.
- Click "Compile Indicator" or "Compile EA" after you finish modifying your original codes.
- Use plugin_for_mql to load the output js(and WebAssembly) that is generated by the "Compile" step. The generated JSON string will be used as the parameter of the plugins.

Please access this page to know more details: https://www.fintechee.com/compatible-with-mql/

The tool in the page: https://www.fintechee.com/compatible-with-mql/ is an alternative generator to the "Generate Indicator" or "Generate EA" function.

3. Output files

- The output files(js and WebAssembly) will be stored in the sub-directory: ./static
- you can access ./static via http://127.0.0.1:3000/js/[your_output_js_file_name] (/js refers to ./static)

## Tutorials
The tutorials will be coming soon.

## License

### Fintechee License

Fintechee License = MIT License + Restrictions for Racists
