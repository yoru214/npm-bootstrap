# NPM for Theme Development using Bootstrap

A repo template I use when I develop themes using the bootstrap framework. It includes npm scripts that allows me to build and test on browser and build a distributable version which will automatically combine and minify my js and css files.

## Getting Started

### Prerequisites

#### Node JS - NPM

Node JS needs to be installed in you system or commputer for NPM to be of use. You can download at their official site at https://nodejs.org.

#### Git 

You need to install Git if you want to intall via Git Clone. Using Git will be beneficial if you also want to do versioning on the theme you are developing. It could also serve as cloud back up for your work.

### Install

Either you decided to use the template as your own repo or directly used my repo template, you can install the template using either of the to ways as follows:

#### Download Source

1. You can directly download the source by clicking the "Code" button just beside the "Use this template" button.
2. Download Zip.
3. After the download is finished, extract the files.
4. Open terminal or command prompt or powershell.
5. On the terminal, go to the directory where the file is extracted.
e.g. "cd npm-bootstrap"
6. Type "npm install".
7. It will then install all necessary modules.

#### Git Clone

1. Click the "Code" button just beside the "Use this template" button.
2. Copy the url path of the repo.
3. Open terminal or command prompt or powershell.
4. On the terminal, go to the directory that will serve as a parent directory to where you want your template will be saved.
5. Type "git clone repository-path my-template-folder". repository-path is the url you copied from the repo and my-template-folder can be any folder name you wish to name your development folder
6. Go to the directory where the file is extracted.
e.g. "cd my-template-folder".
7. Type "npm install".
8. It will then install all necessary modules.

### How to Use

There are 3 major comands that can be used and they are as follows:

#### Build

"npm run build"

This will build your template files that will be ready to be rendered.

#### Test

"npm run test"

This will build your template then serve a http-server which will allow you to render on the browser.

#### Distribute

"npm run dist"

This will build your template on a production ready state.

## Start Developing

### HTML Pages

HTML pages can be created on the "html" directory. you can also create subfolders if necessary to tidy your html files.

### CSS

CSS is made using SASS and the SASS files are located on the "sass" directory

### Javascript

Currently, it only supports a single javascript file which is located on the root directory named "app.js"

## Future Development

I plan on improving this template and eventualy transform into a boilerplate with some basic and probably complex modules that can make them development more faster and efficient. So if you have suggestions for a functionality, I am willing to listen and see if there is something I can do with it.
