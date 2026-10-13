# os.ivan.gg

**Your PIN decides what opens.** An Android OS based on [GrapheneOS](https://grapheneos.org)
where one lock screen takes several PINs, each with its own outcome: the everyday profile, a
protected space with its own keys, an instant reboot that clears every key from memory, or a
wipe.

> Personal research and test project, alpha quality. Provided as is, with no warranty and no
> liability of any kind. Not affiliated with or endorsed by the GrapheneOS project; please
> don't ask GrapheneOS for support with it.

**Supported:** Pixel 8 Pro (`husky`). Based on GrapheneOS 17.

## Repositories

| Repo | What |
|---|---|
| [os-ivan-gg](https://github.com/os-ivan-gg/os-ivan-gg) | design docs, tests, build tooling, patches per feature; start here |
| [manifest](https://github.com/os-ivan-gg/manifest) | `repo` manifest: GrapheneOS plus the forks below |
| [platform_frameworks_base](https://github.com/os-ivan-gg/platform_frameworks_base) | lock settings, credential dispatch, protected space, boot logo |
| [platform_packages_apps_Settings](https://github.com/os-ivan-gg/platform_packages_apps_Settings) | protected space setup, reboot PIN, PIN screens |
| [platform_packages_apps_SetupWizard2](https://github.com/os-ivan-gg/platform_packages_apps_SetupWizard2) | first-run screens |
| [platform_system_sepolicy](https://github.com/os-ivan-gg/platform_system_sepolicy) | one boot animation rule |
| [platform_packages_apps_Updater](https://github.com/os-ivan-gg/platform_packages_apps_Updater) | updates from our server (planned) |
| [releases](https://github.com/os-ivan-gg/releases) | factory images and over-the-air updates (none yet) |

Our changes live on the `envs-17` branch of each fork.
