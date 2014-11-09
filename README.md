# Layout.swift

## Dynamic Layouts for Swift

To Install, just include the file Layout.swift in your project.

## Available Layouts

#### VerticalLayout
Subviews layed out vertically. Eack subview layed out relative to the baseline of the previous subview.

    init(width: CGFloat)

#### VerticalFitLayout
One of the subviews is expanded to the rest of the parents height. This subview must be initialised with height zero.

    init(width: CGFloat)

#### VerticalScreenLayout
Works like VerticalLayout but takes the Screen Width.

    init()

#### HorizontalLayout
Subviews layed out horizontally. Eack subview layed out relative to the top right of the previous subview.

    init(height: CGFloat)

#### HorizontalFitLayout
One of the subviews is expanded to the rest of the parents width. This subview must be initialised with width zero.

    init(height: CGFloat)

For Usage and more Info refer this article. [Dynamic Layout in Swift](https://medium.com/swift-programming/dynamic-layouts-in-swift-b56cf8049b08)