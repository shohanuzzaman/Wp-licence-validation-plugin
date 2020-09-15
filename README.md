# Wp-license-validation WordPress Plugin
This is an example of a WordPress plugin that utilizes Keygen for licensing.
For this example, each license key will be locked to a specific domain (also
referred to as "node-locked" licensing).


## Running the example

You will need to set up a local WordPress installation on `localhost` in
order for the license to be valid. Simply move the `example-plugin.php`
script into the `wp-content/plugins` folder and activate the plugin.

## Validating a license key

Navigate to the plugin's settings menu. You can use the license key "`wp-localhost-key`"
while on `localhost` to test a valid license. If you're not on `localhost`, an
error will be shown.


https://github.com/shohanuzzaman



```javascript
{
  requireFingerprintScope: true,
  maxMachines: 1,
  concurrent: false,
  floating: false,
  protected: true,
  strict: true
}
```

You can leave all other attributes to their defaults, but feel free to
modify them if needed for your particular licensing model, e.g. change
the `maxMachines` limit, set it to `floating = true`, etc.

## Questions?

Reach out at arnob77s@gmail.com) if you have any
questions or concerns!
# Wp-licence-validation-plugin
# Wp-licence-validation-plugin
