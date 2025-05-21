# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date:05-03-2025
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
# 1. Open Unreal Engine:
Launch Unreal Engine and create a new project or open an existing project.
# 2. Create a New Material:
In the Content Browser, right-click and select ‘Material’ to create a new material.
Name it appropriately (e.g., ‘M_EffectMaterial’).
# 3. Adjust the Emissive Property:
Open the material by double-clicking on it.
In the Material Editor, use a Constant3Vector node to define a color for the emissive effect.
Connect the node to the Emissive Color input of the Material node.
Adjust the color's brightness by multiplying it with a constant to simulate glowing material.
# 4. Modify the Roughness:
Use a Scalar Parameter node to control the roughness (0 for smooth, 1 for rough).
Connect this node to the Roughness input of the material node.
# 5. Control Metallic Property:
Use another Scalar Parameter node to define metallicity (0 for non�metallic, 1 for metallic).
Connect the scalar to the Metallic input of the material node.
# 6. Apply the Material to a 3D Model:
Drag and drop the material onto a 3D model in the scene to see the effects in real-time.
# 7. Tweak the Values:
Experiment with different values for emissive color, roughness, and metallic properties to see how they affect the appearance of the material.
# 8. Take Screenshots:
Capture the visual results using the Screenshot tool within Unreal Engine


## Output:
# 1.Base Color
![image](https://github.com/user-attachments/assets/5019ba56-16e6-4dbc-8c74-8134c2e4f843)
# 2.Emissive property
![image](https://github.com/user-attachments/assets/585c9a1f-4d34-4572-abd7-9b5a295734e0)
# 3.Roughness property 
![image](https://github.com/user-attachments/assets/f868cff1-1f77-4ec1-9c94-7dfeacded00d)
# 4.Mettalic property
![image](https://github.com/user-attachments/assets/588deb08-1308-4a26-b6f2-51c238f747a0)
# 5.Final output
![image](https://github.com/user-attachments/assets/fd06f051-04b6-49b8-aa7e-9df34ee795aa)

## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
