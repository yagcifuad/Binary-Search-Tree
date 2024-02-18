# Binary-Search-Tree
=======
# Binary Search Tree Implementation

This project contains the implementation of a Binary Search Tree (BST) in Java. The BinarySearchTree class provides functionalities for creating, searching, inserting, and deleting elements in a binary search tree. The BinarySearchTreePane class visualizes the BST using JavaFX, allowing users to interactively insert and delete nodes.

## Author:
Fuad Yagci

## BinarySearchTree Class

The `BinarySearchTree` class implements the `Tree` interface and provides the following functionalities:

- **Constructor**: Creates an empty binary search tree or initializes it with an array of elements.
- **Search**: Searches for an element in the tree.
- **Insert**: Inserts an element into the tree.
- **Delete**: Deletes an element from the tree.
- **Traversal**: Supports in-order, pre-order, and post-order traversal of the tree.
- **Path**: Finds the path from the root to a specific element.
- **Utility Methods**: getSize() returns the size of the tree, isEmpty() checks if the tree is empty, and getRoot() returns the root node.

## BinarySearchTreePane Class

The `BinarySearchTreePane` class extends JavaFX's Pane class and provides a graphical representation of the binary search tree. It visualizes the tree with nodes and edges, allowing users to view the structure of the tree.

## Main Class

The `Main` class contains the main method to launch the application. It creates an instance of the binary search tree, sets up the JavaFX stage, and handles user interactions for inserting and deleting nodes.

## Usage

To use this implementation:

1. Compile the Java files.
2. Run the Main class.
3. Use the GUI to insert or delete nodes from the binary search tree.
4. Visualize the changes in the tree structure on the graphical pane.

## Dependencies

- JavaFX: The graphical user interface is built using JavaFX for visualization.
- Java Development Kit (JDK): Ensure you have JDK installed to compile and run the code.

## Contributing

Contributions to improve the efficiency, add new features, or fix bugs are welcome. Feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

