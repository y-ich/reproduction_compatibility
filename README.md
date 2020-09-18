# Reproduction code of incompatibility of MLModel on iOS 14/iPadOS 14

The MLModel ./MLModels/ModelUnderTest.mlmodel works fine on iOS 13/iPadOS 13, but does not work on iOS 14/iPadOS 14.

When you call predictionFromFeatures:options:error method, Xcode debugger outputs

    reproduction_compatibility[1816:411275] [coreml] Failure in -completeOutputBackings:error:.

This mlmodel is been used on my commercial app.
Please fix it soon or Please let me know any workarounds to avoid this error on app side.

Thank you for your efforts!