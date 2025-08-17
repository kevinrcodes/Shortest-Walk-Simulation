Google Maps Shortest Walk Simulation

A campus navigation system built in Java and JavaFX that calculates optimal walking routes between buildings at UW–Madison. The project models the campus as a weighted graph and applies efficient algorithms to compute shortest paths, travel times, and routes.

Features

Graph Management: Stores campus buildings as nodes and walking times as weighted edges.

Data Loading: Parses .dot graph files to dynamically build the campus map.

Location Retrieval: Lists all buildings/locations in the dataset.

Shortest Path Calculation:

Direct shortest path between two locations.

Shortest path that must pass through a specific intermediate location.

Travel Time Calculation: Returns exact walking times along computed paths.

JavaFX Frontend: Displays step-by-step routes and timing in an interactive UI.

Tech Stack

Java, JavaFX for backend + UI

Graph Algorithms: Dijkstra’s algorithm, Red-Black Trees, Hashtables

Data Input: DOT file parsing with regex

How It Works

Load the campus graph data from a DOT file.

Query available locations.

Run shortest path search between chosen locations.

Get route details and travel times via the JavaFX interface.

Example Use Case

Find the quickest walking route from one building to another.

Enforce a stop at a third building on the way.

Display results with travel time breakdown and nutrition-style step list.
