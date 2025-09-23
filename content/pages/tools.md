---
content_type: page
description: This section provides Excel calculator files and Matlab files used for
  the course.
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: ce8135a8-a730-53fa-fcae-d3ff8910dd3e
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Excel Calculator Files
----------------------

Heat Exchanger Network ({{% resource_link 6ba4821c-57ec-a3a4-8b13-e49b4e82ebf5 "XLS" %}})  
Shower Controllability Analysis ({{% resource_link 66defec1-15a1-1a24-a1b5-9d25e19e82e9 "XLS" %}})

MATLAB® Files
-------------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
MATLAB® FILES
{{< thclose >}}
{{< thopen >}}
DESCRIPTIONS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
calc\_f.m ({{% resource_link 5cacd7ee-6420-7933-5ede-b9c653551b7d "M" %}})
{{< tdclose >}}
{{< tdopen >}}
Contains a system of equations that describes the steady-state operation of a heat exchanger network.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
calc\_Jac.m ({{% resource_link f0d59177-77a5-f1ae-c9cd-454cc28c6973 "M" %}})
{{< tdclose >}}
{{< tdopen >}}
Function to calculate the Jacobian matrix for a set of nonlinear algebraic equations. A simple central differencing scheme is used.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
ice\_root.m ({{% resource_link 11438f91-6c39-009b-76c3-1df2056a4eb2 "M" %}})
{{< tdclose >}}
{{< tdopen >}}
Calculates the RGA (relative gain array) and DC (disturbance cost) for the 10.492 heat exchanger network.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
reduced\_Newton.m ({{% resource_link 3fe1ffed-07cc-2d74-c6c6-120be76f22b6 "M" %}})
{{< tdclose >}}
{{< tdopen >}}
Uses a reduced-Newton algorithm with a weak line search to solve a set of non-linear algebraic equations.
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}