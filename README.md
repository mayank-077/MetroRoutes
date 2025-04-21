# MetroRoutes
This Java-based application enables users to input the names of their source and destination stations within the Delhi Metro network. Based on this input, it calculates and displays the fare and the shortest metro route to reach the destination. For better commuter navigation, the program also includes a visual representation of the metro map.

The core logic of the application relies on Graph and Heap data structures. In this graph, each node represents a metro station and holds details such as the station's name, the metro corridor it belongs to, and the lines it connects. The edges between nodes denote direct connections between stations, where the weight of each edge corresponds to the physical distance between the two stations.

To determine the optimal path from the source to the destination, the program employs well-known algorithms such as Dijkstra’s Algorithm, Breadth-First Search (BFS), and Depth-First Search (DFS). Based on the calculated total distance, the fare is estimated and then displayed along with the recommended metro route.

The main application logic is implemented in Main.java, while Heap.java contains the heap data structure implementation.

You can run this project in any standard IDE, whether online or offline, including Eclipse, NetBeans, or ideone.com. Basic familiarity with Java programming is recommended. Although knowledge of data structures like Graph and Heap, as well as algorithms like Dijkstra, BFS, and DFS, will enhance your understanding, it is not mandatory. Some exposure to Java's Collection framework can be helpful but isn't essential. For reference, you can explore the Collections framework here: GeeksforGeeks - Collections in Java.
