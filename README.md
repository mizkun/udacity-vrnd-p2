#1. Name
Kyohei Mizutani

#2. How long it took to complete
2 hours

#3. One thing I liked
Good backgound city noise.

#4. One thing that was challenging about this project
Got `No GvrViewer instance found.` error at `TriggerAnimation:Awake()` since `TriggerAnimation` tried to call `GvrViewer.Instance` in `Awake()`.
I fixed this by moving `GvrViewer.Instance` to `Update()` method.
