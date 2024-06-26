# Components

在Makepad中，我们认为组件(component)是一个高级的小部件(widget)，建立在小部件的基本结构之上。组件可以是具有预定义属性的单个小部件，也可以是多个小部件协同工作的组合。这种方法允许在设计用户界面时具有更大的灵活性和模块性。在以下部分中，我将深入解释Makepad的`theme_desktop_dark`中的所有组件，展示它们的独特特性和功能。

In Makepad, we believe that a component is an advanced widget, built upon the foundational structures of widgets. A component can either be a single widget with predefined properties or a combination of multiple widgets working together. This approach allows for greater flexibility and modularity in designing user interfaces. In the following sections, I will provide an in-depth explanation of all the components within Makepad's `theme_desktop_dark`, showcasing their unique properties and functionalities.

## Attention

<strong style="color: #FF0000">
当你看到划线的组件，请不要使用<br><br>
If you see the component marked with line, please do not use
</strong>

## All Components

### Root

- `Root`

### Designer

- `Designer`
- ~`DesignerView`~

### Window

- `Window`

### View

- `View`
- `SolidView`
- `SlidesView`
- `Slide`
#### ScrollView
- `ScrollXView`
- `ScrollYView`
- `ScrollXYView`
- ~`KeyboardView`~
#### ShapeView
- `RectView`
- `RoundedView`
- ~`RoundedXView`~   
- ~`RoundedYView`~
- `RoundedAllView`
- ~`CircleView`~
- ~`HexagonView`~
#### GradientView
- `GradientXView`
- `GradientYView`
#### ~CachedView~
- `CachedView`
- `CachedScrollXY`
- `CachedScrollX`
- `CachedScrollY`
- `CachedRoundedView`

### Label

- `Label`
- `LinkLabel`
- `SlideBody`

### Icon

- `icon`

### Image

- `Image`
- `ImageBlend`
- `RotatedImage`

### CheckBox

- `CheckBox`

### RadioButton

- `RadioButton`

### TextInput

- `TextInput`

### Slider

- `Slider`

### ScrollBar(s)

- `ScrollBar`
- `ScrollBars`

### Splitter

- `Splitter`

### ~Stack~
- `StackViewHeader`
- `StackNavigationView`
  