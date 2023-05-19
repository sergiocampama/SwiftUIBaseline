This repo showcases an issue when importing SwiftUI, where UILabel's rendering is messed up for attributed strings, at least with the baselineOffset attribute.

If you run the SwiftUIBaselineExpected scheme on a simulator, you'll see that the text content is offset towards the top. And if you run the SwiftUIBaseline scheme, you'll see that the label is now centered.

The code for both apps is exactly the same, the only difference is SwiftUIBaseline has a Swift condition that makes SwiftUI to get imported.