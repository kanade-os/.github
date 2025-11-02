<picture>
  <source media="(prefers-color-scheme: dark)" srcset="logo-dark.png 2x">
  <source media="(prefers-color-scheme: light)" srcset="logo.png 2x">
  <img alt="kanade - an experimental operating system" src="logo.png">
</picture>

---

At its core, kanade is a UNIX-like operating system, a personal learning project on which I can _experiment_. Come back later -- there might be some really cool stuff!

All the same, kanade is also an experiment in designing an OS dev ecosystem of reusable modules, to foster custom operating system development.

## Design goals
- [otonashi](https://github.com/kanade-os/otonashi) will let you bootstrap a multi-threaded, multi-core OS kernel in no time. Think _Arduino for modern machines_, you get memory paging, context switching and SMP entry points for your platform, and you decide how to wire everything up.
- [the driver project](https://github.com/kanade-os/drivers) will provide clearly defined API layers to help you integrate composable drivers into your kernel. Hardware drivers are a significant portion of modern operating systems, which is why I want to encourage reuse.
- [the kanade kernel](https://github.com/kanade-os/kernel) will serve as a reference implementation of what an OS built on these resource looks like, as well as a platform to experiment with.
- [the kanade operating system](https://github.com/kanade-os/kanade) will be a full-fledged, UNIX-like distribution showcasing how software ports can expedite the creation of an ecosystem around an OS.

