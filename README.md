# Chirpy Starter

[![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

When installing the [**Chirpy**][chirpy] theme through [RubyGems.org][gem], Jekyll can only read files in the folders
`_data`, `_layouts`, `_includes`, `_sass` and `assets`, as well as a small part of options of the `_config.yml` file
from the theme's gem. If you have ever installed this theme gem, you can use the command
`bundle info --path jekyll-theme-chirpy` to locate these files.

The Jekyll team claims that this is to leave the ball in the user’s court, but this also results in users not being
able to enjoy the out-of-the-box experience when using feature-rich themes.

To fully use all the features of **Chirpy**, you need to copy the other critical files from the theme's gem to your
Jekyll site. The following is a list of targets:

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

To save you time, and also in case you lose some files while copying, we extract those files/configurations of the
latest version of the **Chirpy** theme and the [CD][CD] workflow to here, so that you can start writing in minutes.

## Usage

Check out the [theme's docs](https://github.com/cotes2020/jekyll-theme-chirpy/wiki).

## Contributing

This repository is automatically updated with new releases from the theme repository. If you encounter any issues or want to contribute to its improvement, please visit the [theme repository][chirpy] to provide feedback.

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE

### to do
-[ ] `Site Verification Settings`
```python
# Site Verification Settings
webmaster_verifications:
  google: # fill in your Google verification code
  bing: # fill in your Bing verification code
  alexa: # fill in your Alexa verification code
  yandex: # fill in your Yandex verification code
  baidu: # fill in your Baidu verification code
  facebook: # fill in your Facebook verification code

# ↑ --------------------------
# The end of `jekyll-seo-tag` settings
```
## my blog

```mermaid
flowchart TB
    %% Data Analysis
    DA["Data Analysis"]
    DA --> Visualization["Visualization"]
    DA --> Statistics["Statistics"]
    DA --> Cleaning["Data Cleaning"]
```
```mermaid
flowchart TB
    %% Machine Learning
    ML["Machine Learning"]
    ML --> Mathematics["Mathematics"]
    ML --> SKLearn["Scikit‑Learn Workflow"]
    ML --> NN["NN"]
```
```mermaid
flowchart TB
    %% Web Development
    WD["Web Development"]
    WD --> Jekyll["Jekyll"]
    WD --> React["React"]
    WD --> NextJS["Next.js"]
```
```mermaid
flowchart TB
    %% Hobbies
    HB["Hobbies"]
    HB --> Gallery["Electronic Art Gallery"]
    HB --> Music["Music"]
```
```mermaid
flowchart TB
    %% Tools
    Tools["Tools"]
    Tools --> Git["Version Control (Git)"]
    Tools --> Docker["Virtual Env (Docker)"]
    Tools --> SQL["Database (SQL)"]
    Tools --> MermaidDiag["Flow Diagrams (Mermaid)"]
    Tools --> Markdown["Markdown"]
    Tools --> Jupyter["Jupyter Presentations"]
```
