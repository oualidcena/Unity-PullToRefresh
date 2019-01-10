# Unity-PullToRefresh
Pull to refresh for Unity UI.
http://baba-s.hatenablog.com/entry/2019/01/10/160000
![screenshot1](https://github.com/kiepng/Unity-PullToRefresh/blob/master/Documents/screenshot01.gif)

## Usage
1. Download PullToRefresh-vx.x.x.unitypackage from [Releases](https://github.com/kiepng/Unity-PullToRefresh/releases).
2. Import the package into your Unity project.
3. Create your `ScrollRect` implements `IScrollable`.
4. Prepare `Image` of Loading icon.
4. Add `UIRefreshControl` component to your ScrollView from `Add Component` in inspector.
5. Attach `IScrollable` and `LoadingIcon` to `UIRefreshControl`.
![screenshot2](https://github.com/kiepng/Unity-PullToRefresh/blob/master/Documents/screenshot02.png)  
See `ExampleScene` for details.

## Environment
Unity2018.2.7f1

## License
MIT

## Author
[kiepng](https://github.com/kiepng)

