<h1 align="center"><em>Fresh </em><img src="https://raw.githubusercontent.com/xscriptor-colors/web/main/public/svg/icons/fresh.svg" width="30" alt="Fresh Colors logo" />
</h1>
<div align="center">
    <img src="https://img.shields.io/github/license/xscriptor-colors/fresh?style=flat-square" alt="MIT License" />
    <img src="https://img.shields.io/github/stars/xscriptor-colors/fresh?style=flat-square" alt="GitHub Stars" />
    <img src="https://img.shields.io/github/v/release/xscriptor-colors/fresh?style=flat-square" alt="Release" />
    <img src="https://img.shields.io/github/last-commit/xscriptor-colors/fresh?style=flat-square" alt="Last Commit" />
    <img src="https://img.shields.io/github/repo-size/xscriptor-colors/fresh?style=flat-square" alt="Repo Size" />
    <img src="https://img.shields.io/badge/Built%20for-Fresh-1EAE9B?style=flat-square" alt="Fresh" />
    <img src="https://img.shields.io/badge/Rust-1.70+-dea584?style=flat-square&logo=rust" alt="Rust" />
</div>

<p align="center"><em>Essential settings to improve accessibility of Fresh using the Xscriptor themes.</em></p>

<!-- Contents -->
<ul>
  <li><a href="#overview">Overview</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#uninstall">Uninstall</a></li>
  <li><a href="#manual-installation">Manual Installation</a></li>
  <li><a href="#available-themes">Available Themes</a></li>
  <li><a href="#colors">Colors</a></li>
  <li><a href="#notes">Notes</a></li>
  <li><a href="#related-documents">Related Documents</a></li>
  <li><a href="#related-repos">Related Repos</a></li>
  <li><a href="#x">X</a></li>
</ul>

<!-- Previews -->
<h2 align="center"><em>Previews</em></h2>
<img src="https://xscriptor-colors.github.io/web/images/gifs/fresh/fresh-demo.gif" width="900" alt="Fresh Demo" >

<details>
  <summary>More</summary>

  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview1.jpg" alt="Preview 1" width="380"/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview2.jpg" alt="Preview 2" width="380"/>
  <br/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview3.jpg" alt="Preview 3" width="380"/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview4.jpg" alt="Preview 4" width="380"/>
  <br/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview5.jpg" alt="Preview 5" width="380"/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview6.jpg" alt="Preview 6" width="380"/>
  <br/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview7.jpg" alt="Preview 7" width="380"/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview8.jpg" alt="Preview 8" width="380"/>
  <br/>
  <img src="https://raw.githubusercontent.com/xscriptor/xassets/main/xrepos/fresh/preview9.jpg" alt="Preview 9" width="380"/>
</details>


<!-- Overview -->
<h2 align="center" id="overview">Overview</h2>
<p>Custom color themes for Fresh, the terminal text editor. This repository contains multiple JSON theme files compatible with Fresh.</p>
<p>Install them into <code>~/.config/fresh/themes</code>.</p>

<!-- Installation -->
<h2 align="center" id="installation">Installation</h2>
<p>Run the installer remotely with either curl or wget:</p>
<pre><code class="language-bash">curl -fsSL https://raw.githubusercontent.com/xscriptor-colors/fresh/main/installer.sh | bash
</code></pre>
<pre><code class="language-bash">wget -qO- https://raw.githubusercontent.com/xscriptor-colors/fresh/main/installer.sh | bash
</code></pre>
<p>The installer creates <code>~/.config/fresh/themes</code> if it does not exist and copies all themes there.</p>

<!-- Uninstall -->
<h2 align="center" id="uninstall">Uninstall</h2>
<p>Remove the installed themes with:</p>
<pre><code class="language-bash">curl -fsSL https://raw.githubusercontent.com/xscriptor-colors/fresh/main/uninstaller.sh | bash
</code></pre>
<pre><code class="language-bash">wget -qO- https://raw.githubusercontent.com/xscriptor-colors/fresh/main/uninstaller.sh | bash
</code></pre>
<p>This removes the themes provided by this repository. If the directory becomes empty, it is removed.</p>

<!-- Manual Installation -->
<h2 align="center" id="manual-installation">Manual Installation</h2>
<pre><code class="language-bash">mkdir -p ~/.config/fresh/themes
cp -f themes/*.json ~/.config/fresh/themes/
</code></pre>

<!-- Available Themes -->
<h2 align="center" id="available-themes">Available Themes</h2>
<ul>
    <li>berlin</li>
    <li>bogota</li>
    <li>helsinki</li>
    <li>lahabana</li>
    <li>london</li>
    <li>madrid</li>
    <li>miami</li>
    <li>oslo</li>
    <li>paris</li>
    <li>praha</li>
    <li>tokio</li>
    <li>x</li>
</ul>

<!-- Notes -->
<h2 align="center" id="notes">Notes</h2>
<ul>
    <li>Fresh should read themes from <code>~/.config/fresh/themes</code>. Refer to Fresh’s documentation for selecting a theme inside the editor.</li>
    <li>No elevated privileges are required. All operations target your home directory.</li>
</ul>



<h2 align="center" id="colors">Colors</h2>


<div align="center">
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_x.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_x.svg" height="100" alt="X"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_madrid.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_madrid.svg" height="100" alt="Madrid"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_lahabana.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_lahabana.svg" height="100" alt="Lahabana"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_miami.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_miami.svg" height="100" alt="Miami"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_paris.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_paris.svg" height="100" alt="Paris"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_tokio.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_tokio.svg" height="100" alt="Tokio"/></a>
</div>
<div align="center">
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_oslo.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_oslo.svg" height="100" alt="Oslo"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_helsinki.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_helsinki.svg" height="100" alt="Helsinki"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_berlin.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_berlin.svg" height="100" alt="Berlin"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_london.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_london.svg" height="100" alt="London"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_praha.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_praha.svg" height="100" alt="Praha"/></a>
  <a href="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_bogota.svg"><img src="https://raw.githubusercontent.com/xscriptor-colors/assets/main/media/palettes/palette_bogota.svg" height="100" alt="Bogota"/></a>
</div>

<h2 align="center" id="related-documents">Related Documents</h2>

<ul>
  <li><a href="./docs/themes.md">Theme System</a></li>
  <li><a href="./colors.md">Palettes</a></li>
  <li><a href="./LICENSE">License</a></li>
  <li><a href="./CODE_OF_CONDUCT.md">Code of Conduct</a></li>
  <li><a href="./CONTRIBUTING.md">Contributions</a></li>
  <li><a href="./ROADMAP.md">Roadmap</a></li>
</ul>


<h2 align="center" id="related-repos">Related Repos</h2>
<ul>
  <li><a href="https://github.com/xscriptor-colors/terminal">Terminal </a></li>
  <li><a href="https://github.com/xscriptor-colors/nvim">Nvim </a></li>
  <li><a href="https://github.com/xscriptor-colors/jetbrains">Jetbrains </a></li>
  <li><a href="https://github.com/gitnapse/gitnapse">Gitnapse </a></li>
  <li><a href="https://github.com/xscriptor-colors/obsidian">Obsidian </a></li>
  <li><a href="https://github.com/xfetch-cli/xfetch">XFetch </a></li>
  <li><a href="https://github.com/xscriptor-colors/vscode">Vscode </a></li>
</ul>

<div id="x" align="center">
<h2>X</h2>

<a href="https://xscriptor.io">Dev</a>
 & 
<a href="https://github.com/xscriptor">github</a>
 & 
<a href="https://www.xscriptor.com">X</a>

</div>