# Hello World!
### How to make an egg

1. Heat up the pan[^1]
2. Put the oil on the pan
3. Crack an egg on the pan

![This is an egg, for reference](Brown-eggs.webp)

4. Wait for the edges to turn brown
5. Grab a spatula and lay it on a plate

### Here is an example of a 3D object

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

### Here is an example of the results of population growth

```mermaid
graph TD;
    A[Better health technology, education, and resources] --> B;
    A[Better health technology, education, and resources] --> C;
    B[Woman's rights] --> D[Stage 4- Slow population decline, birth rate slightly lower than death rate];
    C[Higher economic activity] --> D;
```

[^1]: There are many different pans, so I recommend a non-stick skillet. 

