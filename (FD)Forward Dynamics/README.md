# Forward Dynamics

Forward Dynamics is usually used in simulation. It is relatively hard to compute, and roboticist do not use that quite often.

**Modern Robotics** has introduced a naive way of computing Mass matrix and bias force thus get the accelatation.

Roy Featherstone's **Rigid Body Dynamics Algorithm** has introduced some very good algorithms. They are **Inertia Matrix Method**, **Composite Rigid Body Algorithm** and **Articulated Body Algorithm**.

I wrote down the relationship and difference of algorithms in notes. And I implemented the three algorithm based on the framework of Modern Robotics Cpp.

## Code
[Modern Robotics naive Forward Dynamics](https://github.com/guzhaoyuan/ModernRoboticsCpp/blob/03d51d32dd6a7e97ef6616cc4c4bd7452a68bfcb/src/modern_robotics.cpp#L727)

[Inertia Matrix Method Forward Dynamics](https://github.com/guzhaoyuan/ModernRoboticsCpp/blob/83a398f2fd1793da45f9306e33f3a786646f0be7/src/modern_robotics.cpp#L975)

[Composite Rigid Body Algorithm Forward Dynamics](https://github.com/guzhaoyuan/ModernRoboticsCpp/blob/83a398f2fd1793da45f9306e33f3a786646f0be7/src/modern_robotics.cpp#L1006)

[Articulated Body Algorithm Forward Dynamics](https://github.com/guzhaoyuan/ModernRoboticsCpp/blob/83a398f2fd1793da45f9306e33f3a786646f0be7/src/modern_robotics.cpp#L1036)