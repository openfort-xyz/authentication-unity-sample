# Authentication in Unity

...

## Features

- 🏰 Openfort Authentication.
- 🏰 [Openfort CSharp SDK](https://github.com/openfort-xyz/openfort-unreal-engine).

## How to run locally

**1. Clone and configure the sample**

```
git clone https://github.com/openfort-xyz/samples
cd authentication-unity-sample
```


You will need an Openfort account in order to run the demo. Once you set up your account, go to the Openfort [developer dashboard](https://dashboard.openfort.xyz/apikeys) to find your API keys.

Then, navigate to `Assets/Scripts/LoginSceneManager.cs` and replace the following values with your own:

```csharp
OpenfortAuth authClient = new OpenfortAuth("YOUR_PUBLISHABLE_KEY");
```


**2. Configure Authentication Providers**

Coming soon.


## Get support
If you found a bug or want to suggest a new [feature/use case/sample], please [file an issue](../../../issues).

If you have questions, comments, or need help with code, we're here to help:
- on [Discord](https://discord.com/invite/t7x7hwkJF4)
- on Twitter at [@openfortxyz](https://twitter.com/openfortxyz)
- by [email](mailto:support+github@openfort.xyz)
