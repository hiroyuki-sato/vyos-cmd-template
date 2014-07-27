## VyOS command template 

VyOS command template without autoconf.


## Usage

clone source 

```
git clone https://github.com/hiroyuki-sato/vyos-cmd-template
```

rename project 

```
bin/rename_proj <your_project_name>
```

Edit README and Changelog.

Add command definition in template-{cfg,op}.

## Package build

```
debuild -uc -us
```
