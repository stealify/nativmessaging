# nativmessaging
Is a Core Component used often @stealif/sharedArrayBuffer to do Cross Platform Cross Application Interop eg: Browser Extension using nodejs. 
It implements utils to use when you do Component Integration on a lower level. It uses the C Std IO implementation so it works with command lines and fileHandels. 

## Todo
- create contentScript to backgroundScript Generators. 
  - in content scripts no data url imports and only extension:// url schema are allowed.
- create HostScript to contentScript
- offer both with @stealify/sharedArrayBuffer helpers as it is faster to work on sharedMemory.
- minimal effort to create also firefox compatible extensions? https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Chrome_incompatibilities#data_cloning_algorithm
