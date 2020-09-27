# AndroidXSlidingUpPanelXamarin

Xamarin Bindings library for [hannesa2's][hannesa2] [AndroidSlidingUpPanel][AndroidSlidingUpPanel]

Plugin is available on [Nuget][Nuget].

# Support

* Feel free to open an issue. Make sure to use one of the templates!

How do I use it?
================

    <com.sothree.slidinguppanel.SlidingUpPanelLayout xmlns:sothree="http://schemas.android.com/apk/res-auto"
      android:id="@+id/sliding_layout"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      android:gravity="bottom"
      sothree:umanoPanelHeight="68dp"
      sothree:umanoShadowHeight="4dp"
      sothree:umanoParallaxOffset="100dp"
      sothree:umanoDragView="@+id/dragView"
      sothree:umanoOverlay="true">
    <!-- MAIN CONTENT -->
    </com.sothree.slidinguppanel.SlidingUpPanelLayout>
    
Look at the sample project and the original project for more information.

### Licensing

This project is licensed under the [MS-PL License](http://opensource.org/licenses/ms-pl.html)

[hannesa2]: https://github.com/hannesa2
[AndroidSlidingUpPanel]: https://github.com/hannesa2/AndroidSlidingUpPanel/
[Nuget]: https://www.nuget.org/packages/Xam.Plugins.AndroidX.SlidingUpPanel/
