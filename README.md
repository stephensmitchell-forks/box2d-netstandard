![Box2D Logo](https://box2d.org/images/logo.svg)

# Box2D .NET Standard 

Box2D is a C# port of C++ Box2D by Ihar Kalasouski and supported by Ben Ukhanov.

- The purpose of this repository is to create Box2D .NET Standard library
- The .NET Standard supports .NET Framework, .NET Core, and [.NET 5+ later](https://medium.com/capgemini-dynamics-365-team/future-of-net-net-5-microsoft-build-2019-from-a-net-developer-point-of-view-7a1158fb0691)
- The nuget package is available on nuget.org

## Source

- [C++ Box2D Original - Erin Catto](https://github.com/erincatto/box2d)
- [Ported C# Box2DX - Ihar Kalasouski](https://code.google.com/archive/p/box2dx/)

## Contributing

Anyone who wants to contribute to this repository:
- The changes will be in the new branch (feature/new or feature/bug-fix)
- The new pull request will be started
- The new version will be published on nuget.org

## Features

### Collision
- Continuous collision detection
- Contact callbacks: add, persist, remove
- Convex polygons and circles
- Multiple shapes per body
- One-shot contact manifolds
- Incremental sweep-and-prune broadphase
- Efficient pair management
- Fast broadphase AABB queries
- Collision groups and categories

### Physics
- Continuous physics with time of impact solver
- Persistent body-joint-contact graph
- Island solution and sleep management
- Contact, friction, and restitution
- Stable stacking with a linear-time solver
- Revolute, prismatic, distance, pulley, gear, and mouse joints
- Joint limits, motors, and friction
- Momentum decoupled position correction
- Fairly accurate reaction forces/impulses

### System
- Centralized tuning parameters
- Pure .NET Standard 2.0+ library
- Please [See .NET Implementation Support](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)

## Documentation
- [Manual](https://box2d.org/documentation/)
- [Reddit](https://www.reddit.com/r/box2d/)
- [Discord](https://discord.gg/NKYgCBP)

## License
Original C++ Box2D is developed by Erin Catto, and uses the [MIT license](https://en.wikipedia.org/wiki/MIT_License).