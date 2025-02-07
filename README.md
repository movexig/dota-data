# dota-data

Auto-generated Dota 2 resource dumps.

Data from this package is available on [ModDota API](http://moddota.com/api) page (previously [dota.tools](https://dota.tools/)).

## To update from a new dump

### For contributors:

1. Check out this repository
2. Create a new DOTA addon through the addon tool, call it `dumper` for example
3. Copy `.lua` scripts from `dumper` directory of this repository to
   `dota 2 beta\game\dota_addons\dumper\scripts\vscripts`
4. Launch `dumper` addon
5. In `vsconsole` do `dota_launch_custom_game dumper test_basic`
6. Proceed through the game setup screen
7. Copy-paste the console output (starting with `$> dump_panorama_css_properties`) into `dumper/dump` in this repository
8. Run `yarn install` then `yarn build` in the root of the repository
9. Commit changes
10. Create a pull request

### For maintainers:

11. Run `npm version minor`
12. Push with tags
