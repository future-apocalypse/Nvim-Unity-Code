<h1 id="nvimunitycode">Nvim-Unity-Code</h1>
<p>This is a very simple file that will help you to open <a href="https://github.com/neovim/neovim"><strong>Neovim</strong></a> to edit C# scripts for <a href="https://unity.com/"><strong>Unity Game Engine</strong></a>.</p>
<p><strong>Targets Linux distributions.</strong></p>
<hr />
<h3 id="dependencies">Dependencies</h3>
<ul>
<li><a href="https://github.com/mhinz/neovim-remote">Neovim-Remote</a></li>
</ul>
<hr />
<h3 id="installation">Installation</h3>
<p><strong>1) Just run this command in your terminal, this will add my script in your nvim folder.</strong></p>
<pre><code class="bash language-bash">git clone https://github.com/Ares2048/Nvim-Unity-Code ~/.config/nvim/Nvim-Unity-Code
</code></pre>
<p><strong>2) After this you need to make script to be executable.</strong></p>
<pre><code class="bash language-bash">cd ~/.config/nvim/Nvim-Unity-Code/Script/
chmod +x nvim-unity-code
</code></pre>
<p><strong>3) Now go in Unity Hub, chose a random project and in unity editor go to "Edit>Preferences…>External Tools" look closely you will se a string called "External Script Editor", select this, and here you need to select Nvim-Unity-Code, chose (Open by file extension) select (Browse…) and go in your config folder of Neovim there you saved the script ~/.config/nvim/Nvim-Unity-Code/Script/ and chose neovim-unity-code executable file.</strong></p>
<p>(HERE IMG FILE LINK)</p>
<hr />
<h3 id="note">Note</h3>
<p>This will work only on Linux with Gnome DE, if you use another Linux with diferent desktop environment (example: KDE plasma) you will need to change a little bit the script that you installed.</p>
<p>1) Edit the script.</p>
<pre><code class="bash language-bash">cd ~/.config/nvim/Nvim-Unity-Code/Script/
</code></pre>
<pre><code class="bash language-bash">nano nvim-unity-code
</code></pre>
<p>2) In nano you need to delete "gnome-terminal" and paste <strong>"konsole",</strong></p>
<p><strong>ex: konsole --title="nvim-unity-code" -- nvr -s…</strong></p>
<p>After all of this hit (Ctrl + o) and Enter to save changes, and hit (Ctrl + x) to Exit. That's it .</p>
<hr />
<h3 id="license">License</h3>
<p><a href="https://choosealicense.com/licenses/mit/">MIT</a> </p>
