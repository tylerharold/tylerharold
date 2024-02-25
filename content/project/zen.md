# Zen: A minimal text editor inspired by Vim

My journey into learning Rust had its fair share of initial challenges. 
Rust, known for its steep learning curve, demands patience and dedication, but the investment in mastering it is undoubtedly rewarding.

To aid my learning process, I engaged with [Philip Flenker's series](https://www.flenker.blog/hecto/) on building a text editor in Rust.
This series not only provided a practical approach to understanding Rust but also aligned perfectly with my interests. 
As a daily user of NeoVim, the idea of crafting a minimal text editor inspired by Vim resonated with me.

While my editor drew heavy inspiration from the series, I infused it with personal touches to enhance its functionality and tailor it to my needs:

- **Configurable Keymaps:** I introduced the ability to customize keymaps through a configuration file, adding a layer of personalization and flexibility.
- **Integration with Syntect:** By replacing the built-in highlighting system with Syntect, I ensured more reliable and consistent syntax highlighting across various file types.
- **Command System for Multi-Keypress Actions:** This feature was implemented to streamline complex commands, making the editor more efficient and user-friendly.
- **Enhanced Movement Capabilities:** Expanding upon Hecto's basic movement mechanics, I incorporated more Vim-like motions, offering a familiar and intuitive navigation experience.
