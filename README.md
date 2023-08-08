# Unity_Shader
Unity Shader: A Unity Shader implemented based on HLSL, which achieves effects such as vegetation swaying with the wind, color gradient, water surface fluctuation, and reflection.
1. Calculate the wind force based on time, position, and noise in the vertex function, and modify the vertex position according to the wind force to achieve vegetation swaying with the wind.
2. Use a mixture of the main color and main texture sampling to generate the base color, and overlay the second color based on vertex positions or UV coordinates to control the second color level and fade in/out degree to achieve vegetation color gradient.
3. Add water surface disturbance through wave normal mapping and use voronoi noise to achieve a white foam effect. Calculate the Fresnel value based on the direction of the line of sight, and combine it with a reflection map to achieve a refractive effect. Wave, foam and reflection parameters can be adjusted to control the details of water surface.
