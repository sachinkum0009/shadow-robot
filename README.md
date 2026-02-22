# shadow-robot
VLA implementation for Humanoid Robots

![Shadow Robot](docs/media/shadow_robot.png)


```bash
uv run src/main.py
```

## Architecture

```mermaid
graph TD
    A[VLA Inference Server] <--> B[Inference Client]
    C[Env: G1] --> B
    D[ROS Interface] --> C
    B -- Actions --> D
```
