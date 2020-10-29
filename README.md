![GitHub](https://img.shields.io/github/license/ilyastuit/wysiwyg)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/ilyastuit/wysiwyg?label=version)
# JavaFX implementation of Lexi

**Lexi** is a WYSIWYG (What You See Is What You Get) editor. This project was for my Object Oriented Design Patterns Class. Thus, each of the different assignments required use of explicit design patterns to make the final product very modular and easy to add on to
**Motivation** - I've been reading the book(as most of you) and faced the questions like "How this pattern is implemented?" or "Is there an open-source implementation of Lexi?". After searching internet for the answers I decided to implement it all by myself.
**Note**: Even though I've tried to implement stuff as described in the book, there are differences that I'll try to describe in the future.

## Pattern referencing
- [IGlyph](https://github.com/) Abstract, base for all graphical units class. Described in Section 2.2 of GoF.
- [Composite](https://github.com/) Described in Section 2.2 of GoF.
- Strategy: basically any child glyph.
- [Decorator](https://github.com/) Note: currently, the scroller isn't a decorator as described in GoF due to implementation specific. Described in Section 2.4.
- [Abstract Factory](https://github.com/) Described in Section 2.5.
- Bridge: [Base Window](https://github.com/), interface [WindowImpl](https://github.com/) and its child [XWindowImpl](https://github.com/). Described in Section 2.6.
- [Command](https://github.com/) Described in Section 2.7. 