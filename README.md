
# as_gwc_public_theme

An ArchivesSpace plugin that customizes the public interface by adding a banner
image and some styling and locale strings.

Compatible with ArchivesSpace v4.2.1.

---

Developed by Hudson Molonglo for The Green-Wood Cemetery.

&copy; 2026 Hudson Molonglo Pty Ltd


## Installation

Install this plugin by placing it in the `archivesspace/plugins` directory and
adding it to your list of configured plugins in `archivesspace/config/config.rb`,
like this:
```
AppConfig[:plugins] << 'as_gwc_public_theme'
```

## Configuration

In addition to the plugins entry noted above, add the following line to
`archivesspace/config/config.rb`:
```
AppConfig[:pui_branding_img] = 'assets/images/gwc_logo.png'
```
