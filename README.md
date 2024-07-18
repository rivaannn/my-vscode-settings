<h1>🌟 My VSCode Settings 🌟</h1>

<p>This repository contains my custom Visual Studio Code (VSCode) settings, designed to optimize my development environment for productivity and aesthetics.</p>

<h2>🛠️ Settings</h2>

<p>Below are the key settings configured in the <code>settings.json</code> file:</p>

```json
{
  "workbench.startupEditor": "none",
  "workbench.iconTheme": "vscode-icons",
  "workbench.sideBar.location": "right",
  "workbench.colorTheme": "Tokyo Storm Gogh",
  "editor.fontSize": 19,
  "editor.fontFamily": "Cascadia Code",
  "editor.fontLigatures": true,
  "editor.codeActionsOnSave": {},
  "editor.lineHeight": 1.8,
  "editor.minimap.enabled": false,
  "terminal.integrated.lineHeight": 1.6,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 0.5,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "[*]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.wordWrap": "on",
  "security.workspace.trust.untrustedFiles": "open",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.fontFamily": "'MesloLGS NF'",
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.fontSize": 17
}
```
<h2>🔑 Key Configuration Highlights</h2>
<ul>
  <li><strong>Workbench Configuration</strong>
    <ul>
      <li>🔹 <code>"workbench.startupEditor": "none"</code>: Disable the startup editor.</li>
      <li>🔹 <code>"workbench.iconTheme": "vscode-icons"</code>: Use <code>vscode-icons</code> for a comprehensive set of icons.</li>
      <li>🔹 <code>"workbench.sideBar.location": "right"</code>: Place the sidebar on the right side.</li>
      <li>🔹 <code>"workbench.colorTheme": "Tokyo Storm Gogh"</code>: Set the color theme to <code>Tokyo Storm Gogh</code>.</li>
    </ul>
  </li>
  <li><strong>Editor Configuration</strong>
    <ul>
      <li>✨ <code>"editor.fontSize": 19</code>: Set the editor font size to 19.</li>
      <li>✨ <code>"editor.fontFamily": "Cascadia Code"</code>: Use <code>Cascadia Code</code> as the editor font.</li>
      <li>✨ <code>"editor.fontLigatures": true</code>: Enable font ligatures.</li>
      <li>✨ <code>"editor.lineHeight": 1.8</code>: Set the editor line height to 1.8.</li>
      <li>✨ <code>"editor.minimap.enabled": false</code>: Disable the minimap.</li>
      <li>✨ <code>"editor.defaultFormatter": "esbenp.prettier-vscode"</code>: Use Prettier as the default formatter.</li>
      <li>✨ <code>"editor.formatOnSave": true</code>: Enable format on save.</li>
      <li>✨ <code>"editor.wordWrap": "on"</code>: Enable word wrap.</li>
    </ul>
  </li>
  <li><strong>Terminal Configuration</strong>
    <ul>
      <li>💻 <code>"terminal.integrated.lineHeight": 1.6</code>: Set the terminal line height to 1.6.</li>
      <li>💻 <code>"terminal.integrated.cursorStyle": "line"</code>: Use a line cursor in the terminal.</li>
      <li>💻 <code>"terminal.integrated.cursorWidth": 0.5</code>: Set the cursor width to 0.5.</li>
      <li>💻 <code>"terminal.integrated.defaultProfile.windows": "Git Bash"</code>: Use <code>Git Bash</code> as the default terminal profile on Windows.</li>
      <li>💻 <code>"terminal.integrated.fontFamily": "'MesloLGS NF'"</code>: Set the terminal font to <code>MesloLGS NF</code>.</li>
      <li>💻 <code>"terminal.integrated.fontWeight": "normal"</code>: Use normal font weight in the terminal.</li>
      <li>💻 <code>"terminal.integrated.fontSize": 17</code>: Set the terminal font size to 17.</li>
    </ul>
  </li>
  <li><strong>Security Configuration</strong>
    <ul>
      <li>🔒 <code>"security.workspace.trust.untrustedFiles": "open"</code>: Automatically open untrusted files.</li>
    </ul>
  </li>
</ul>
<h2>📜 Usage</h2>
<ol>
  <li>Clone the repository to your local machine:
    <pre><code>git clone https://github.com/rivaannn/my-vscode-settings.git</code></pre>
  </li>
  <li>Copy the <code>settings.json</code> file to your VSCode user settings directory:
    <ul>
      <li><strong>Windows:</strong> <code>%APPDATA%\Code\User\settings.json</code></li>
      <li><strong>macOS:</strong> <code>$HOME/Library/Application Support/Code/User/settings.json</code></li>
      <li><strong>Linux:</strong> <code>$HOME/.config/Code/User/settings.json</code></li>
    </ul>
  </li>
  <li>Restart VSCode to apply the new settings.</li>
</ol>
<p>Feel free to customize these settings further to suit your personal preferences and workflow.</p>
<h2>🤝 Contributing</h2>
<p>If you have suggestions for improvements or additional settings, please feel free to submit a pull request or open an issue.</p>
<hr>
<p>By maintaining a well-configured <code>settings.json</code>, you can enhance your coding experience, making VSCode more responsive and tailored to your needs. Happy coding! 🚀</p>
