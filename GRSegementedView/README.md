# GRSegementedView

Nice animated custom segment control which can be used insted of UISegmentedControl

## Example

To run the example project, clone the repo, and run the code.

## Installation
### Manually:

* Download GRSegementedView or Clone Download.
* Drag and drop GRSegementedView directory to your project

## Usage

Create a UIView in the StoryBoard and subclass it as GRSegmentedView and create outlet for it.
Then use the code:
```swift segmentView.segmentTitles = ["One", "Two", "Three"]
segmentView.selectionTitleColor = .white
segmentView.deselectionTitleColor = .white
segmentView.selectorColor = .brown
segmentView.delegate = self
```
   ### Delegate
```swift
func didSelected(_ segmentControl: GRSegmentedView, at index: Int) {
    print("Selecetd Index: ", index)
}
   ```

## Author

Gregory Wilson, gregorywlsn0111@gmail.com

## License

GRSegementedView is available under the MIT license. See the LICENSE file for more info.
