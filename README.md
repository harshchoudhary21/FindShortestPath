
# Shortest-Path-Finder

### Project Overview

The Shortest-Path-Finder is a web application designed to calculate and display the shortest path between two nodes in a graph. It is particularly useful for students and professionals who need to quickly determine the most efficient route between two points. The project is primarily intended for students at IIIT Guwahati, but it can be adapted for broader applications.

### Key Features

- **Shortest Distance Calculation**: Provides the minimum distance between a specified source and destination.
- **Path Visualization**: Displays the exact path to be followed to achieve the shortest distance.

### API Reference

#### Get Shortest Distance Between Node A and Node B

```http
  GET /shortd/<int:A>/<int:B>
```

| Parameter      | Type      | Description            |
| :------------- | :-------- | :--------------------- |
| `A` (source)   | `integer` | **Required**           |
| `B` (destination) | `integer` | **Required**       |

### Tech Stack

- **Client**: React
- **Server**: Flask, Python

### Used By

This project is used by the following:

- Students of IIIT Guwahati

### FAQ

#### How can I obtain the shortest path from the source to the destination?

Every possible source and destination is mapped with a number ranging from 1 to 64. The application will display the nodes in the order required to reach the destination with the minimum distance.
