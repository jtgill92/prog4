# prog4

Proposed EC: 1% Render opaque triangles with one draw call per model while still allowing for transparent triangles to be ordered back to front per triangle.

This approach is often used by game engines to reduce draw call overhead. Each opaque model requires only one draw call. Transparent models are ordered per triangle and require one draw call per triangle.
