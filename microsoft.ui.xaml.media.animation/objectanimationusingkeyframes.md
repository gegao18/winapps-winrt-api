---
-api-id: T:Microsoft.UI.Xaml.Media.Animation.ObjectAnimationUsingKeyFrames
-api-type: winrt class
---

<!-- Class syntax.
public class ObjectAnimationUsingKeyFrames : Windows.UI.Xaml.Media.Animation.Timeline, Windows.UI.Xaml.Media.Animation.IObjectAnimationUsingKeyFrames
-->

# Microsoft.UI.Xaml.Media.Animation.ObjectAnimationUsingKeyFrames

## -description
Animates the value of an [Object](/dotnet/api/system.object?view=dotnet-uwp-10.0&preserve-view=true) property along a set of [KeyFrames](objectanimationusingkeyframes_keyframes.md) over a specified [Duration](../microsoft.ui.xaml/duration.md).

## -xaml-syntax
```xaml
<ObjectAnimationUsingKeyFrames>oneOrMoreDiscreteObjectKeyFrames</ObjectAnimationUsingKeyFrames>
```


## -remarks

## -examples
The following example uses the ObjectAnimationUsingKeyFrames class to animate the [Fill](../microsoft.ui.xaml.shapes/shape_fill.md) property of a [Rectangle](../microsoft.ui.xaml.shapes/rectangle.md). This animation uses two key frames in the following manner:


1. Using a [DiscreteObjectKeyFrame](discreteobjectkeyframe.md), the [Fill](../microsoft.ui.xaml.shapes/shape_fill.md) property of the [Rectangle](../microsoft.ui.xaml.shapes/rectangle.md) suddenly changes to a [LinearGradientBrush](../microsoft.ui.xaml.media/lineargradientbrush.md) after the first two seconds of the animation.
1. After the third second of the animation, the [Fill](../microsoft.ui.xaml.shapes/shape_fill.md) property is suddenly changed to a different [LinearGradientBrush](../microsoft.ui.xaml.media/lineargradientbrush.md), which remains until the end of the animation (four seconds total).

[!code-xaml[Objectanimationusingkeyframes](../microsoft.ui.xaml.media.animation/code/objectanimationusingkeyframes/csharp/Page.xaml#SnippetObjectanimationusingkeyframes)]

[!code-csharp[Objectanimationusingkeyframes_cs](../microsoft.ui.xaml.media.animation/code/objectanimationusingkeyframes/csharp/Page.xaml.cs#SnippetObjectanimationusingkeyframes_cs)]

[!code-vb[Objectanimationusingkeyframes_cs](../microsoft.ui.xaml.media.animation/code/objectanimationusingkeyframes/vbnet/Page.xaml.vb#SnippetObjectanimationusingkeyframes_cs)]

## -see-also
[Storyboarded animations](/windows/apps/design/motion/storyboarded-animations), [Timeline](timeline.md), [ObjectKeyFrame](objectkeyframe.md), [Timeline](timeline.md), [ObjectKeyFrame](objectkeyframe.md)
