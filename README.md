<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Glimesh.tv</font></font></h1><a id="user-content-glimeshtv" class="anchor" aria-label="永久链接：Glimesh.tv" href="#glimeshtv"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/glimesh/glimesh.tv/workflows/Elixir%20CI/badge.svg"><img src="https://github.com/glimesh/glimesh.tv/workflows/Elixir%20CI/badge.svg" alt="Elixir CI" style="max-width: 100%;"></a>
<a href="https://coveralls.io/github/Glimesh/glimesh.tv?branch=dev" rel="nofollow"><img src="https://camo.githubusercontent.com/ab4f0f84be5df4f79f00b7938110e60e0753013732986c71d220b8897ab2383e/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f6769746875622f476c696d6573682f676c696d6573682e74762f62616467652e7376673f6272616e63683d646576" alt="覆盖状态" data-canonical-src="https://coveralls.io/repos/github/Glimesh/glimesh.tv/badge.svg?branch=dev" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Glimesh 是一个由社区为社区打造的新一代流媒体平台。我们的平台致力于提高内容创作者的曝光度，并采用最新的流媒体技术来创造公平的竞争环境。我们了解内容创作者与粉丝之间互动的重要性，并致力于创新新方法，让社区更加紧密地联系在一起。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库包含 Glimesh.tv 后端和浏览器前端。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h2><a id="user-content-table-of-contents" class="anchor" aria-label="固定链接：目录" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#development-installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发安装</font></font></a>
<ul dir="auto">
<li><a href="#general-dependencies"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常规依赖项</font></font></a></li>
<li><a href="#cloning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆</font></font></a></li>
<li><a href="#windows-installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 安装</font></font></a></li>
<li><a href="#ubuntu-installation--including-wsl2---ubuntu-"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 安装（包括 WSL2 + Ubuntu）</font></font></a>
<ul dir="auto">
<li><a href="#configuring-postgres"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Postgres</font></font></a></li>
</ul>
</li>
<li><a href="#macos-installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 安装</font></font></a></li>
<li><a href="#preparing-to-run"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">准备运行</font></font></a></li>
<li><a href="#run-"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跑步！</font></font></a>
<ul dir="auto">
<li><a href="#ssl-https"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSL/HTTPS</font></font></a></li>
</ul>
</li>
<li><a href="#docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker</font></font></a></li>
<li><a href="#customizing-your-local-environment"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义本地环境</font></font></a></li>
</ul>
</li>
<li><a href="#developing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展</font></font></a>
<ul dir="auto">
<li><a href="#modifying-code"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">修改代码</font></font></a></li>
<li><a href="#running-static-code-analysis"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行静态代码分析</font></font></a></li>
<li><a href="#contributing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a></li>
</ul>
</li>
<li><a href="#testing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></a></li>
<li><a href="#help"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助</font></font></a></li>
<li><a href="#security-policy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全策略</font></font></a></li>
<li><a href="#license"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发安装</font></font></h2><a id="user-content-development-installation" class="anchor" aria-label="固定链接：开发安装" href="#development-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些说明可作为运行 Glimesh 的参考，无论您的本地机器类型如何，都可用于开发。某些说明可能特定于各种发行版，可能需要使用适合您配置的正确程序进行替换。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常规依赖项</font></font></h3><a id="user-content-general-dependencies" class="anchor" aria-label="永久链接：常规依赖项" href="#general-dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您将需要以下工具来克隆、构建和运行 Glimesh：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">git</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：源代码控制</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">erlang</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：运行时</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">elixir</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：语言和工具</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">postgresql</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：数据库</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nodejs / npm</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：前端包管理</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">inotify-tools</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：文件系统监控依赖关系，方便开发人员（观察变化）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您将需要这些可选依赖项来实现高级功能：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rsvg-convert</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：将 SVG 转换为 PNG 表情</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">svgo</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 表情的 SVG 优化</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能需要将这些精确的依赖关系转换为适合您的操作系统发行版的名称。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆</font></font></h3><a id="user-content-cloning" class="anchor" aria-label="永久链接：克隆" href="#cloning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要克隆 Glimesh.tv 的本地副本，请运行</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/Glimesh/glimesh.tv.git
<span class="pl-c"><span class="pl-c">#</span> or if you have permissions to the repository, or prefer to use SSH authentication</span>
<span class="pl-c"><span class="pl-c">#</span> git clone git@github.com:Glimesh/glimesh.tv.git</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/Glimesh/glimesh.tv.git
# or if you have permissions to the repository, or prefer to use SSH authentication
# git clone git@github.com:Glimesh/glimesh.tv.git" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：如果您使用的是 WSL2，请确保您在 WSL2 实例内部进行克隆（例如</font></font><code>/home/user/...</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），而不是在已安装的 Windows 驱动器内部进行克隆（例如</font></font><code>/mnt/c/Users/...</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），因为这会对性能产生重大的负面影响。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 安装</font></font></h3><a id="user-content-windows-installation" class="anchor" aria-label="永久链接：Windows 安装" href="#windows-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前尚不清楚如何在 Windows 上原生运行 Glimesh.tv。不过，您可以使用 WSL2 很好地运行该应用程序。如果您有兴趣原生运行 Glimesh.tv，请尝试一下并告诉我们！</font></font></p>
<p dir="auto"><a href="https://docs.microsoft.com/en-us/windows/wsl/install-win10" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">搭载 Ubuntu 18.04 和 20.04 的WSL2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已在 Windows 上成功测试开发。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 安装（包括 WSL2 + Ubuntu）</font></font></h3><a id="user-content-ubuntu-installation-including-wsl2--ubuntu" class="anchor" aria-label="永久链接：Ubuntu 安装（包括 WSL2 + Ubuntu）" href="#ubuntu-installation-including-wsl2--ubuntu"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在现代版本的 Ubuntu 上，您可以使用以下命令安装这些软件包：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>wget https://packages.erlang-solutions.com/erlang-solutions_2.0_all.deb <span class="pl-k">&amp;&amp;</span> sudo dpkg -i erlang-solutions_2.0_all.deb
sudo apt update
sudo apt install git esl-erlang elixir postgresql npm inotify-tools librsvg2-bin
sudo npm -g install svgo@2.8.0</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="wget https://packages.erlang-solutions.com/erlang-solutions_2.0_all.deb &amp;&amp; sudo dpkg -i erlang-solutions_2.0_all.deb
sudo apt update
sudo apt install git esl-erlang elixir postgresql npm inotify-tools librsvg2-bin
sudo npm -g install svgo@2.8.0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Postgres</font></font></h4><a id="user-content-configuring-postgres" class="anchor" aria-label="永久链接：配置 Postgres" href="#configuring-postgres"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 postgresql 包后，您可能需要启动 postgresql 服务器：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo pg_ctlcluster 12 main start</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo pg_ctlcluster 12 main start" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，您需要为默认</font></font><code>postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户添加密码，以便 Glimesh 服务可以访问数据库。Glimesh 在开发环境中默认使用的密码是</font></font><code>postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。默认情况下，Postgres 只允许来自本地主机的连接 - 对于开发环境，这通常是可以接受的。如果您更关心 Postgres 实例的安全，请考虑使用其他密码。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行以下命令进入 postgres 提示符：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo -u postgres psql</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo -u postgres psql" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当出现</font></font><code>postgres=#</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提示时，您可以运行</font></font><code>\password postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以更改 postgres 用户的密码。输入</font></font><code>postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为密码，再次输入以确认，然后输入
</font></font><code>\quit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以退出 postgres 提示符。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>postgres=# \password postgres
Enter new password:
Enter it again:
\quit
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="postgres=# \password postgres
Enter new password:
Enter it again:
\quit" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS 安装</font></font></h3><a id="user-content-macos-installation" class="anchor" aria-label="固定链接：macOS 安装" href="#macos-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://brew.sh" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用Homebrew</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装很简单</font><font style="vertical-align: inherit;">。首先，我们需要安装固定版本的 Elixir：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>brew install asdf
asdf plugin-add elixir
<span class="pl-c"><span class="pl-c">#</span> Adding elixir binary directory to ZSH shell. Change this if you use a different shell like bash, fish, etc.</span>
<span class="pl-c1">echo</span> -e <span class="pl-s"><span class="pl-pds">"</span>\n. <span class="pl-s"><span class="pl-pds">$(</span>brew --prefix asdf<span class="pl-pds">)</span></span>/asdf.sh<span class="pl-pds">"</span></span> <span class="pl-k">&gt;&gt;</span> <span class="pl-smi">${ZDOTDIR<span class="pl-k">:-</span>~}</span>/.zshrc
asdf install elixir <span class="pl-s"><span class="pl-pds">`</span>sed -n -e <span class="pl-s"><span class="pl-pds">'</span>s/ *elixir: "~&gt; \(.*\)",/\1/p<span class="pl-pds">'</span></span> mix.exs<span class="pl-pds">`</span></span>
<span class="pl-c1">source</span> <span class="pl-smi">${ZDOTDIR<span class="pl-k">:-</span>~}</span>/.zshrc
elixir --version</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="brew install asdf
asdf plugin-add elixir
# Adding elixir binary directory to ZSH shell. Change this if you use a different shell like bash, fish, etc.
echo -e &quot;\n. $(brew --prefix asdf)/asdf.sh&quot; >> ${ZDOTDIR:-~}/.zshrc
asdf install elixir `sed -n -e 's/ *elixir: &quot;~> \(.*\)&quot;,/\1/p' mix.exs`
source ${ZDOTDIR:-~}/.zshrc
elixir --version" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在让我们安装其他依赖项：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Required dependencies</span>
brew install imagemagick node
<span class="pl-c"><span class="pl-c">#</span> Optional dependencies</span>
brew install librsvg 
npm install -g svgo@2.8.0
<span class="pl-c"><span class="pl-c">#</span> Graphical Postgres, if you do not want a graphical Postgres, you are on your own!</span>
brew install --cask postgres-unofficial</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Required dependencies
brew install imagemagick node
# Optional dependencies
brew install librsvg 
npm install -g svgo@2.8.0
# Graphical Postgres, if you do not want a graphical Postgres, you are on your own!
brew install --cask postgres-unofficial" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完成这些安装步骤后，启动 Postgres.app 并初始化服务器。此时，您就可以运行 Glimesh.tv 了。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跑步！</font></font></h3><a id="user-content-run" class="anchor" aria-label="永久链接：快跑！" href="#run"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后，您可以运行以下命令来启动 Glimesh.tv 服务：
</font></font><code>cd</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进入您克隆 Glimesh.tv 的目录并运行：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./run.sh</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./run.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您可以</font></font><a href="http://localhost:4000" rel="nofollow"><code>localhost:4000</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从浏览器访问。作为第一项任务，深入研究</font></font><code>run.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脚本以查看它运行的脚本步骤以安装依赖项并启动服务器。您不需要为每种类型的更改重建所有这些步骤，因此弄清楚您需要为更改运行哪些步骤将加快您的开发反馈循环。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSL/HTTPS</font></font></h4><a id="user-content-sslhttps" class="anchor" aria-label="永久链接：SSL/HTTPS" href="#sslhttps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：为了使用 HTTPS 连接，您需要将生成的自签名证书添加到您的受信任存储区。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要在 Windows 上执行此操作，请找到</font></font><code>priv/cert/selfsigned.pem</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之前生成的文件。在 WSL2 中，您可以通过</font></font><code>\\wsl$</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Windows 资源管理器导航到您的 WSL2 机器。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 selfsigned.pem 文件复制到您的 Windows 机器，并将文件扩展名从 更改
</font></font><code>.pem</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>.crt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双击该</font></font><code>.crt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件并选择“安装证书...”。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择“当前用户”作为商店位置，然后按“下一步”。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择“将所有证书放入以下存储”，然后按“浏览...”按钮。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择“受信任的根证书颁发机构”并按“确定”。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按“下一步”完成证书导入向导。当提示信任证书时，按“确定”。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您可以通过 HTTPS 访问您本地的 Glimesh 开发实例</font></font><a href="https://localhost:4001" rel="nofollow"><code>localhost:4001</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker</font></font></h3><a id="user-content-docker" class="anchor" aria-label="永久链接：Docker" href="#docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Glimesh.tv 还可以使用</font><a href="https://docs.docker.com/compose/install/" rel="nofollow"><font style="vertical-align: inherit;">docker-compose</font></a><font style="vertical-align: inherit;">设置为</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅供开发使用</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="https://docs.docker.com/compose/install/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为此，请从 GitHub 存储库运行以下命令：</font></font></p>
<p dir="auto"><code>docker-compose up</code></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后您可以访问以下网站：</font></font><code>http://localhost:4000</code></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要运行测试，您可以启动 docker 实例并通过执行以下操作对其进行运行测试</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose run app bash
app<span class="pl-k">&gt;</span> mix <span class="pl-c1">test</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker-compose run app bash
app> mix test" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义本地环境</font></font></h3><a id="user-content-customizing-your-local-environment" class="anchor" aria-label="永久链接：自定义您的本地环境" href="#customizing-your-local-environment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以创建一个</font></font><code>config/local.exs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置文件来更改任何本地设置，从而简化开发。git 会忽略此文件，因此您不必担心提交任何机密。</font></font></p>
<div class="highlight highlight-source-elixir notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-v">Config</span>

<span class="pl-en">config</span> <span class="pl-pds">:glimesh</span><span class="pl-kos">,</span> <span class="pl-v">GlimeshWeb.Endpoint</span><span class="pl-kos">,</span>
  <span class="pl-pds">url: </span><span class="pl-kos">[</span><span class="pl-pds">host: </span><span class="pl-s">"glimesh.dev"</span><span class="pl-kos">,</span> <span class="pl-pds">port: </span><span class="pl-c1">443</span><span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import Config

config :glimesh, GlimeshWeb.Endpoint,
  url: [host: &quot;glimesh.dev&quot;, port: 443]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发展</font></font></h2><a id="user-content-developing" class="anchor" aria-label="永久链接：开发中" href="#developing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目背后的大部分核心代码都位于清晰的目录中，并与其他类似代码分组。以下是您经常使用的几个目录：</font></font></p>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前端</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后端</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资产/CSS</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有样式的 SCSS 目录，使用 Bootstrap 4.5</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资产/js</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的简单 JavaScript 钩子。通常根据操作直接从 LiveView 触发。我们努力保持 JavaScript 最少化</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">lib/glimesh_web/{live，模板}</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Phoenix LiveView 和基于常规控制器的视图（在 Phoenix 中称为模板）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库/glimesh</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">核心 Elixir 域逻辑和 DB 交互</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">lib/glimesh_web/{live，控制器}</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Phoenix LiveView 和常规控制器</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">priv/repo/迁移</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Postgres 数据库的 Ecto 迁移</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有测试（功能性和集成性）均使用 ExUnit 进行</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置</font></font></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地、测试和生产版本的配置</font></font></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">修改代码</font></font></h3><a id="user-content-modifying-code" class="anchor" aria-label="永久链接：修改代码" href="#modifying-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何已知目录中的所有代码都会自动监视更改并触发相应的构建。一些前端代码和实时视图会自动刷新浏览器，但对于更复杂的域逻辑，您可能需要刷新浏览器。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行静态代码分析</font></font></h3><a id="user-content-running-static-code-analysis" class="anchor" aria-label="永久链接：运行静态代码分析" href="#running-static-code-analysis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在提交拉取请求之前，请务必运行</font></font><a href="https://github.com/rrrene/credo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Credo</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，它将对整个项目运行静态代码分析。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mix code_quality</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mix code_quality" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h3><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><a href="http://github.com/Glimesh/glimesh.tv/fork"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分叉吧！</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建你的功能分支（</font></font><code>git checkout -b feature/my-new-feature</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提交更改 ( </font></font><code>git commit -am 'Add some feature'</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推送至分支 ( </font></font><code>git push origin feature/my-new-feature</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建新的 Pull 请求</font></font></li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试</font></font></h2><a id="user-content-testing" class="anchor" aria-label="固定链接：测试" href="#testing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Glimesh 包含一个全面且非常快速的测试套件，因此应该鼓励您尽可能频繁地运行测试。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mix <span class="pl-c1">test</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mix test" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何损坏的测试都将通过文件和行号标注出来。如果您正在处理单个测试或单个测试文件，则可以使用以下命令轻松指定较小的测试样本：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mix <span class="pl-c1">test</span> test/glimesh/your_test.exs
<span class="pl-c"><span class="pl-c">#</span> Or specifying a specific line</span>
mix <span class="pl-c1">test</span> test/glimesh/your_test.exs:15</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mix test test/glimesh/your_test.exs
# Or specifying a specific line
mix test test/glimesh/your_test.exs:15" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助</font></font></h2><a id="user-content-help" class="anchor" aria-label="永久链接：帮助" href="#help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要任何帮助，请随时打开</font></font><a href="https://github.com/Glimesh/glimesh.tv/issues/new"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Issue</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全策略</font></font></h2><a id="user-content-security-policy" class="anchor" aria-label="固定链接：安全政策" href="#security-policy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/Glimesh/glimesh.tv/blob/main/SECURITY.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的安全政策可以在SECURITY.md</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Glimesh.tv 已获得</font></font><a href="/Glimesh/glimesh.tv/blob/main/LICENSE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MIT 许可</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
