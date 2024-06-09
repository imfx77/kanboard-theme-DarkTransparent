<h1 name="user-content-readme-top" align="center">DarkTransparent theme for Kanboard</h1>

<p align="center">
    <a href="https://github.com/kanboard/kanboard" title="Kanboard - Kanban Project Management Software">
        <img src="https://img.shields.io/badge/Theme%20for-kanboard-D40000?style=for-the-badge&labelColor=000000" alt="Kanboard">
    </a>
</p>
<p align="center">
    <a href="https://github.com/imfx77/kanboard-theme-DarkTransparent/blob/master/LICENSE" title="Read License">
        <img src="https://img.shields.io/github/license/imfx77/kanboard-theme-DarkTransparent?style=for-the-badge" alt="kanboard-theme-DarkTransparent">
    </a>
    <a href="https://github.com/imfx77/kanboard-theme-DarkTransparent/stargazers" title="View Stargazers">
        <img src="https://img.shields.io/github/stars/imfx77/kanboard-theme-DarkTransparent?logo=github&style=for-the-badge" alt="kanboard-theme-DarkTransparent">
    </a>
    <a href="https://github.com/imfx77/kanboard-theme-DarkTransparent/discussions">
        <img src="https://img.shields.io/github/discussions/imfx77/kanboard-theme-DarkTransparent?style=for-the-badge&color=blue" alt="GitHub Discussions" title="Read Discussions">
    </a>
</p>

---

This is a dark transparent material theme, with dynamically reloading non-moveable background image.
It is intended for use with the [Customizer plugin](https://github.com/creecros/Customizer) for [Kanboard](https://github.com/kanboard/kanboard).

⚠️ **DISCLAIMER !**  
The theme mostly presents customizations to `my own liking` and is distributed **AS IS**.  
So please, review the description and screenshots below, and consider using it or not for yourself !

✅ And if you actually like it and use it, then please, give a ⭐ to this repository !

## Compatibility

- Requires [Kanboard](https://github.com/kanboard/kanboard "Kanboard - Kanban Project Management Software") ≥`1.2.33`
- Requires [Customizer plugin](https://github.com/creecros/Customizer) for Kanboard ≥`1.14.2`

## Features

The theme is a modified version of the [Galaxy.css](https://github.com/creecros/Customizer/blob/master/Assets/css/themes/Galaxy.css)
from the `Customizer plugin` (which in turn is a modification of the [nebula.css](https://github.com/kenlog/Nebula/blob/master/Assets/css/nebula.css)).

Apart from the obvious changes of the primary highlight color (from `lime green` to `dimmed blue`),
the more subtle, yet significant, differences to the `Galaxy.css` as base comparison are listed hereby:

- there is a non-movable `background image`, which is dark greyscale and semi-transparent
  - a `@media` override is provided for `orientation`, so that the image would show decently on mobile devices in `portrait mode`
  - ⚠️the background image changes on each page reload !    
  - it's been a while since the [Unsplash URL APP](https://source.unsplash.com/random)
doesn't really work, so now using this image source instead
    ```
    https://picsum.photos/1920/1080?grayscale&blur=2
    ```
- the `background color` for all meaningful elements is dark and semi-transparent
- tasks' `background and border colors` are darker shades of their `category color`
- ⚠️ tasks' `priority`, `age`, `dates` and `estimation` are **HIDDEN** !
- ⚠️ tasks' `category label` is moved in the up-right corner, just in left of the `user pic` !
- 🗜️ both the above aim to make the tasks vertically compact (see **Task** in **Screenshots**) !

## Screenshots

Well, the changes described above are much easier to see with examples.  
Please, observe next pairs of screenshots with the `Galaxy` example first, and the `DarkTransparent` example following !

<details><summary><strong>Task Board</strong></summary>

![galaxy-task-board](Screenshots/galaxy-task-board.png "galaxy-task-board")  
![dt-task-board](Screenshots/dt-task-board.png "dt-task-board")
</details>

<details><summary><strong>Task List</strong></summary>

![galaxy-task-list](Screenshots/galaxy-task-list.png "galaxy-task-list")  
![dt-task-list](Screenshots/dt-task-list.png "dt-task-list")
</details>

<details><summary><strong>Task Details</strong></summary>

![galaxy-task-details](Screenshots/galaxy-task-details.png "galaxy-task-details")  
![dt-task-details](Screenshots/dt-task-details.png "dt-task-details")
</details>

<details><summary><strong>Task</strong></summary>

![galaxy-task-single](Screenshots/galaxy-task-single.png "galaxy-task-single")  
![dt-task-single](Screenshots/dt-task-single.png "dt-task-single")
</details>

<details><summary><strong>Settings &#10562; Application</strong></summary>

![galaxy-settings-app](Screenshots/galaxy-settings-app.png "galaxy-settings-app")  
![dt-settings-app](Screenshots/dt-settings-app.png "dt-settings-app")
</details>

<details><summary><strong>Settings &#10562; Plugins</strong></summary>

![galaxy-settings-plugins](Screenshots/galaxy-settings-plugins.png "galaxy-settings-plugins")  
![dt-settings-plugins](Screenshots/dt-settings-plugins.png "dt-settings-plugins")
</details>

<details><summary><strong>Wiki Page</strong></summary>

![galaxy-wiki-page](Screenshots/galaxy-wiki-page.png "galaxy-wiki-page")  
![dt-wiki-page](Screenshots/dt-wiki-page.png "dt-wiki-page")
</details>

<details><summary><strong>Todo Notes</strong></summary>

![galaxy-todo-notes](Screenshots/galaxy-todo-notes.png "galaxy-todo-notes")  
![dt-todo-notes](Screenshots/dt-todo-notes.png "dt-todo-notes")
</details>

## Installation

- Make sure you have a properly installed `Kanboard` and `Customizer plugin` !
- Download the [DarkTransparent.css](DarkTransparent.css "Dark Transparent theme") theme.
- Go to `Settings` &#10562; `Customizer` &#10562; `Manage Themes` &#10562; `Upload a theme` :
  - (1) `Browse` to the file you just downloaded.  
  - (2) Then `Add Theme`. 
- Now, just above it, in `Manage Themes` &#10562; `Global Themes` :
  - (3) Select the newly uploaded theme from the dropdown.
  - (4) `Save` the settings.
- That's it! Enjoy 🎈

![install](Screenshots/install.png "install")

## Authors & Contributors

- [Im[F(x)]](https://github.com/imfx77) - Author
- [Everyone else](https://github.com/creecros/Customizer/graphs/contributors) that made it possible 🙏 

## Credits & References

- [Kanboard](https://github.com/kanboard/kanboard)
- [Customizer plugin](https://github.com/creecros/Customizer)
- [Nebula plugin](https://github.com/kenlog/Nebula)

## License

- This theme is distributed under the [MIT License](LICENSE "Read The MIT license")

<p align="right">[<a href="#user-content-readme-top">&#8593; Top</a>]</p>

---

<p align="center">
    <a href="https://github.com/imfx77/kanboard-theme-DarkTransparent/blob/master/LICENSE" title="Read License">
        <img src="https://img.shields.io/github/license/imfx77/kanboard-theme-DarkTransparent?style=flat-square" alt="kanboard-theme-DarkTransparent">
    </a>
    <a href="https://github.com/imfx77/kanboard-theme-DarkTransparent/stargazers" title="View Stargazers">
        <img src="https://img.shields.io/github/stars/imfx77/kanboard-theme-DarkTransparent?logo=github&style=flat-square" alt="kanboard-theme-DarkTransparent">
    </a>
    <a href="https://github.com/imfx77/kanboard-theme-DarkTransparent/discussions" title="Read Discussions">
        <img src="https://img.shields.io/github/discussions/imfx77/kanboard-theme-DarkTransparent?style=flat-square" alt="kanboard-theme-DarkTransparent">
    </a>
</p>

<a name="user-content-readme-bottom"></a>
