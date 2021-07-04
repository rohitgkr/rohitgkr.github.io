---
layout: post
title: Harnessing wind energy to keep roads clear of snow!
---

This post is inspired by a [VLOG (in Hindi)](https://www.youtube.com/watch?v=tBk9Ts6yxVY) from Sonam Wangchuk in which he was looking into an environmentaly friendly solution for clearing snow off roads in the Himalayan region of Ladakh in India. That got me thinking about the problem and the following is my high level solution to the problem that exploits wind energy as a potential environment friendly mechanism. For those who may not be aware, Sonam Wangchuk is an Indian mechanical engineer & winner of a long list of awards including Rolex, Magsaysay, UNESCO to name a few. He is well known founder of various institutions such as [LiveSimply](https://www.ilivesimply.org/), [Himalayan Institute of Alternatives](https://milaap.org/fundraisers/hial) and innovative products in the areas of environment & sustainable living.

# Problem statement
To come up with an environment friendly solution to keep roads clear of snow during winter. The objective is to avoid or minimise the carbon footprint that is currently incurred when using snow ploughing trucks through winter and periods of heavy snow fall. 

# The idea
My idea is to alter the trajectory of falling snow flakes at a sufficiently high altitude so that the resulting parabola would NOT intersect with the road surface. Consider a spec of snow that falling given a wind velocity 'w' whose natural parabolic trajectory lands it on the left edge of the road at a distance 'd'. This could potentially be deflected in such a manner that the altered trajectory takes it to the right edge of the road. Doing so would require a minimum amount of force that's sufficient to keep the road clear from snow accumulation.  
![Snow trajectory]({{ site.baseurl }}/images/DAWTSnowBlowerPhysics.png)
Figure 1

My original thought was to use an array of HAWTs laid out along the road. I turned to DAWTs instead which produce a significantly lower air pressure behind the rotor disk and thereby higher incoming wind velocity. This should increase suction power to a certain extent in front of the turbine and alter the domain flow in surrounding air significantly so as to pass via the DAWT. I have portrayed the following three options that I think are viable for DAWT layout along the road. Of the three option A is my preferred layout. I urge experts in the field to provide feedback on air flow patterns and turbine-turbine interactions so as to arrive on the most optimum layout. 
![Snow trajectory]({{ site.baseurl }}/images/LayoutOnRoad.png)
Figure 2

# Solution
The array of turbines is connected to a power back up battery system to store energy and to charge a fleet of electric vehicles in a charging station. The battery backup will power street lights at night. Any excess power may be plugged into the power grid.   

# Operation
A diffuser augmented wind turbine (DAWT) is particularly more suitable in this application as it produces a pressure differential that increases suction power. While not as powerful as a motor driven propeller it fits into the objective of reducing carbon foot print in two ways. 
1. During steady winds or light snow the DAWT array is likely to be able to deflect snow flakes sufficiently well to extremeties beyond the road boundary and keep the road clear of snow
2. During heavy snow fall or when there's snow at wind speeds close to zero, electric vehicles from the charging station can be deplyed with snow ploughs to clear light debris or accumulated snow    

# The physics
Assuming steady wind that's sufficiently horizontal in direction, a faling snow flake has a horizontal velocity component equal to that of the wind velocity by the time it is close to the height of the turbine. In Figure 1 above the dotted parabola depicts the trajectory of a snow flake falling under steady wind in the absence of a wind turbine. The horizontal distance 'd' is the displacement from the point that's vertically at the same height as the rotor disk along this dotted line trajectory. In other words 'd' is the horizontal displacement from the point in the natural trajectory when the snow flake is at the height of the wind turbine.

The blue line depicts the induced alteration in trajectory of the snow flake in the presence of the DAWT. When the snow flake arrives in the vicinity of the DAWT it is likely to be sucked in. While particles that pass through the wind turbine will end up outside the road boundary to the right, a particle that does not pass through is likely to be impacted by a momentary suction force that alters its trajectory. As wind velocity is primarily horizontal this momentary force produces a horizontal acceleration. When the snow flake moves out of the sphere of significant influence of this momentary pressure force it continues in an altered parabolic trajectory. This is equivalent to a projectile that's launched horizontally from an initial height at the new velocity post momentary acceleration.

# Nomenclature
1. w: wind velocity @ 5m/s
2. g: acceleration due to gravity @ 9.8 m/s<sup>2</sup>
3. d: horizontal displacement from the point in the natural trajectory when the snow flake is at the height of the wind turbine
4. &rho; : Density of snow mixed with air @ 350-400 kg/m<sup>3</sup>

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
