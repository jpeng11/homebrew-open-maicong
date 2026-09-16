# homebrew-open-maicong

**简体中文** | [English](#english)

[Maicong Studio](https://github.com/jpeng11/open-maicong) 的 Homebrew tap。迈从 G75 V2 机械轴键盘的非官方 macOS 本地驱动。

## 安装（Apple Silicon）

```bash
brew install --cask --no-quarantine jpeng11/open-maicong/maicong-studio
```

当前包未签名。`--no-quarantine` 避免 Gatekeeper 隔离。若仍拦截：系统设置 → 隐私与安全性 → 仍要打开。

```bash
brew upgrade --cask --no-quarantine maicong-studio
brew uninstall --cask maicong-studio
brew uninstall --cask --zap maicong-studio
```

应用源码与发版说明见 [open-maicong](https://github.com/jpeng11/open-maicong)。发版时请同步更新本仓库的 `Casks/maicong-studio.rb` 与上游 `Casks/maicong-studio.rb`。

---

<a id="english"></a>

## English

Homebrew tap for [Maicong Studio](https://github.com/jpeng11/open-maicong), an unofficial offline macOS hub for the MCHOSE G75 V2 mechanical keyboard.

```bash
brew install --cask --no-quarantine jpeng11/open-maicong/maicong-studio
```

The current build is unsigned. Use `--no-quarantine`, or allow it in System Settings → Privacy & Security after the first open.

Keep `Casks/maicong-studio.rb` in sync with the copy in the [upstream repo](https://github.com/jpeng11/open-maicong/blob/main/Casks/maicong-studio.rb) when cutting a release.
