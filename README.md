
# GEO3D

```
let engine: GEO3DEngine = GEO3DScnEngine()
let root: GEO3DRoot = engine.createRoot(frame: view.bounds)
view.addSubview(root.view)

var sphere = engine.create(.sphere)
root.add(sphere)
```
