Implements original Quake light flickering in Unity.

Inspired by this blog post
https://80.lv/articles/valve-reused-the-code-for-flickering-lights-in-alyx-22-years-later/

Can be used as component on a Light, or you can call the static methods to animate anything you want.
Implements original integer based light flickers, which are great for harsh flickers, but blends still animate at 10fps, as originally designed.
Also implemented an interpolated version which linear blends the values.
Additional extra parameters for manual time step and speed.

Quake source code license is GPL, but I only used the 'lightstyles' array, so it's a matter of debate if it applies.
My code can be considered free public domain, so use your own judgement on what rights apply. ¯\_(ツ)_/¯