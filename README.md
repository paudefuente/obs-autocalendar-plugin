# obs-autocalendar-plugin
Plugin or Script with differents features for the creation of calendars within Obsidian software.


## About the Plugin

Docs plugin Obsidina [here](https://docs.obsidian.md/Home)



## Installation

In order to start building our plugin we have to follow a set of steps:

1. The first step we have to do is to create or use a secondary vault, instead of using our personal or main one, due to preventing errors in our main vault.

2. We'll have to open a terminal window in our IDE or the operative system native one and change the proyect director to the`plugins` directory.

```shell
cd path/to/vault
mkdir .obsidian/plugins
cd .obsidian/plugins
```
3. Clone the sample plugin using Git.

```shell 
git clone https://github.com/obsidianmd/obsidian-sample-plugin.git
```

4. Now we have to build the plugin. In this step, we'll compile the sample plugin so that Obsidian can load it. First thing to do is to natvigate to the plugin directory.

```shell
cd obsidian-sample-plugin
```

5. Install dependencies

```shell
npm install
```

6. Compile the source code. The folling commnad keeps running in the terminal and rebuilds the plugin when you moodify the source code

```shell
npm run dev
```

## Usage




## Roadmap