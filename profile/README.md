# XNA to MonoGame Samples
This organization is a collection of the XNA samples from the XNA Creators Club.  Each repository contains a branch with the original XNA code as well as branch(s) with the code ported to the current version of MonoGame.

## Special Thanks
Special thanks to @simondarksidej for his [XnaGameStudio](https://github.com/simondarksidej/XNAGameStudio) repository which archived all of this amazing content for us.  Without his preservation of this content, we might not have it now to learn from.  

## MonoGame Port Progress
The following sections breakdown the progress of porting the XNA Creators Club samples to MonoGame

## Completed Ports
The following samples have been successfully converted to MonoGame.

| Sample                                                                        | Description                                                                                                            | Status      |
|-------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|-------------|
| [AccelerometerSample](https://github.com/xna-to-monogame/AccelerometerSample) | This sample shows how to read the accelerometer sensor on an Android device                                            | ✅ Completed |
| [AimingSample](https://github.com/xna-to-monogame/AimingSample)               | This sample shows how to turn one object to face another. This can be useful for aiming, for example.                  | ✅ Completed |
| [Audio3DSample](https://github.com/xna-to-monogame/Audio3DSample)             | This sample shows how to position sounds in 3D space, implementing panning, Doppler, and distance attenuation effects. | ✅ Completed |

## Partial Ports

The following samples have been partially converted to MonoGame, but may have one or more issues preventing them from being marked as completed.  Please check notes in description for issues if you would like to help.

| Sample                                                                | Description                                                                                                                                                       | Status                                                                                                                                                                                          |
|-----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [BillboardSample](https://github.com/xna-to-monogame/BillboardSample) | This sample shows how to efficiently render large numbers of billboard sprites by using a vertex shader to perform the billboard computations entirely on the GPU | ⚠ This sample is currently not working in MonoGame 3.8.1 See [Issue #1](https://github.com/xna-to-monogame/BillboardSample/issues/1) for more information on why and if you would like solve it |

## Can't Port

The following samples are ones that cannot be ported to MonoGame.  Reasons for why they can't be ported are listed in the description.  Each sample also has an open active issue for discussion on how we can make a MonoGame port sample that is equivalent.

| Sample                                                                                            | Description                                                                                                                    | Status                                                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [AvatarAnimationBlendingSample](https://github.com/xna-to-monogame/AvatarAnimationBlendingSample) | This sample shows how to blend two avatar animations together so that they smoothly transition from one animation to the next. | ⚠️ This sample cannot be converted to MonoGame because it focuses specifically on the Xbox 360 avatar integration provided through Microsoft.Framework.Xna.GameServices which is not part of MonoGame. If you have an idea for how to take this sample and make it relevant for something in MonoGame, please submit discussion on the [Port Issue](https://github.com/xna-to-monogame/AvatarAnimationBlendingSample/issues/1) |
| [AvatarMultipleAnimationsSample](https://github.com/xna-to-monogame/AvatarMultipleAnimationsSample) | This sample demonstrates how to play two animations simultaneously on different parts of a single avatar. | ⚠️ This sample cannot be converted to MonoGame because it focuses specifically on the Xbox 360 avatar integration provided through Microsoft.Framework.Xna.GameServices which is not part of MonoGame. If you have an idea for how to take this sample and make it relevant for something in MonoGame, please submit discussion on the [Port Issue](https://github.com/xna-to-monogame/AvatarMultipleAnimationsSample/issues/1) |


## License
All content and source code found in the sample repositories are bound to the Microsoft Permissive License (Ms-PL).
See their respective LICENSE file for more information.
