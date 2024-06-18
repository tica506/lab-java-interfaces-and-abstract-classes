# iNTERFACES AND ABSTRACT CLASSES

This project demonstrates various Java concepts including BigDecimal operations, car inventory system, video streaming service, and custom implementations of an integer list.

## BigDecimal Operations

1. **roundToNearestHundredth**: Rounds a `BigDecimal` to the nearest hundredth.
2. **reverseSignAndRoundToNearestTenth**: Reverses the sign of a `BigDecimal` and rounds to the nearest tenth.

## Car Inventory System

- **Car**: Abstract class with properties and methods common to all cars.
    - **Sedan**: Subclass of `Car`.
    - **UtilityVehicle**: Subclass of `Car` with an additional `fourWheelDrive` property.
    - **Truck**: Subclass of `Car` with an additional `towingCapacity` property.

## Video Streaming Service

- **Video**: Abstract class with properties and methods common to all videos.
    - **TvSeries**: Subclass of `Video` with an additional `episodes` property.
    - **Movie**: Subclass of `Video` with an additional `rating` property.

## IntList Interface and Implementations
~~~~~
- **IntList**: Interface defining methods for adding and retrieving integers.
    - **IntArrayList**: Implementation of `IntList` using a resizable array that increases by 50% when full.
    - **IntVector**: Implementation of `IntList` using a resizable array that doubles in size when full.

## Efficiency Examples

- **IntArrayList**: More efficient for smaller lists or when memory usage is a concern due to smaller incremental resizing.
- **IntVector**: More efficient for larger lists or when frequent resizing is needed due to doubling the size of the array.

