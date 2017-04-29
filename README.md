# Vulkan Cookbook
This is the code repository for [Vulkan Cookbook](https://www.packtpub.com/game-development/vulkan-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781786468154), published by [Packt](https://www.packtpub.com/). All the example workflows that are mentioned in the book are present in the package.

## About the Book
Vulkan is the next generation graphics API released by the Khronos group. It is expected to be the successor to OpenGL and OpenGL ES, which it shares some similarities with such as its cross-platform capabilities, programmable pipeline stages, or nomenclature. Vulkan is a low-level API that gives developers much more control over the hardware, but also adds new responsibilities such as explicit memory and resources management. With it, though, Vulkan is expected to be much faster.

### Related Books

* [Vulkan Programming [Video]](https://www.packtpub.com/application-development/vulkan-programming-video?utm_source=github&utm_medium=repository&utm_campaign=9781786460714)

* [Learning Vulkan](https://www.packtpub.com/application-development/learning-vulkan?utm_source=github&utm_medium=repository&utm_campaign=9781786469809)

* [Building an Unreal RTS Game: The Basics [Video]](https://www.packtpub.com/application-development/building-unreal-rts-game-basics-video?utm_source=github&utm_medium=repository&utm_campaign=9781787285279)

### Suggestions and Feedback
 [Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.

<hr>

# Please note!
## Currently only Windows operating system is supported. Linux version is being prepared and should be ready soon.

<hr>

# [Samples](./Samples/Source%20Files/)

## [Chapter 11 - Lighting](./Samples/Source%20Files/11%20Lighting/)

<img src="./Samples/Source%20Files/11%20Lighting/01-Rendering_a_geometry_with_vertex_diffuse_lighting/screenshot.png" width="150px" align="right">

* ### [01 - Rendering a geometry with vertex diffuse lighting](./Samples/Source%20Files/11%20Lighting/01-Rendering_a_geometry_with_vertex_diffuse_lighting/main.cpp)

Sample showing how to implement a diffuse lighting algorithm calculated only at geometry's verices using vertex shaders.<br>
<b>Left mouse button:</b> rotate the scene

<img src="./Samples/Source%20Files/11%20Lighting/02-Rendering_a_geometry_with_fragment_specular_lighting/screenshot.png" width="150px" align="right">

* ### [02 - Rendering a geometry with fragment specular lighting](./Samples/Source%20Files/11%20Lighting/02-Rendering_a_geometry_with_fragment_specular_lighting/main.cpp)

This sample present the Phong specular lighting algorithm implemented on vertex and fragment shaders.<br>
<b>Left mouse button:</b> rotate the scene

<img src="./Samples/Source%20Files/11%20Lighting/03-Rendering_a_normal_mapped_geometry/screenshot.png" width="150px" align="right">

* ### [03 - Rendering a normal mapped geometry](./Samples/Source%20Files/11%20Lighting/03-Rendering_a_normal_mapped_geometry/main.cpp)

Here a normal mapping technique is presented and the model is lit using the specular lighting algorithm.<br>
<b>Left mouse button:</b> rotate the scene

<img src="./Samples/Source%20Files/11%20Lighting/04-Rendering_a_reflective_and_refractive_geometry_using_cubemaps/screenshot.png" width="150px" align="right">

* ### [04 - Rendering a reflective and refractive geometry using cubemaps](./Samples/Source%20Files/11%20Lighting/04-Rendering_a_reflective_and_refractive_geometry_using_cubemaps/main.cpp)

Sample presenting how to use cubemaps to render a transparent geometry that both reflects and refracts environment.<br>
<b>Left mouse button:</b> rotate the scene

<img src="./Samples/Source%20Files/11%20Lighting/05-Adding_shadows_to_the_scene/screenshot.png" width="150px" align="right">

* ### [05 - Adding shadows to the scene](./Samples/Source%20Files/11%20Lighting/05-Adding_shadows_to_the_scene/main.cpp)

In this sample a basic shadow mapping algorithm is shown. In the first render pass a shadow map is generated. In the second render pass a scene is rendered and the data from the shadow map is used to check, whether the geometry is lit or covered in shadow.<br>
<b>Left mouse button:</b> rotate the scene<br>
<b>Right mouse button:</b> move the light

## [Chapter 12 - Advanced Rendering Techniques](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/)

<img src="./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/01-Drawing_a_skybox/screenshot.png" width="150px" align="right">

* ### [01 - Drawing a skybox](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/01-Drawing_a_skybox/main.cpp)

Here it is shown how to draw a skybox, which simulates background - objects seen in a distance and/or a sky.<br>
<b>Left mouse button:</b> look around

<img src="./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/02-Drawing_bilboards_using_geometry_shaders/screenshot.png" width="150px" align="right">

* ### [02 - Drawing bilboards using geometry shaders](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/02-Drawing_bilboards_using_geometry_shaders/main.cpp)

This sample presents a way of drawing sprites or bilboards - flat, textured quads that are always facing the camera.<br>
<b>Left mouse button:</b> rotate the scene

<img src="./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/03-Drawing_particles_using_compute_and_graphics_pipelines/screenshot.png" width="150px" align="right">

* ### [03 - Drawing particles using compute and graphics pipelines](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/03-Drawing_particles_using_compute_and_graphics_pipelines/main.cpp)

Here an example of rendering particles is shown. Compute shaders are used to calculate positions of all particles in the system. Particles are rendered as flat bilboards (sprites).<br>
<b>Left mouse button:</b> rotate the scene

<img src="./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/04-Rendering_a_tesselated_terrain/screenshot.png" width="150px" align="right">

* ### [04 - Rendering a tesselated terrain](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/04-Rendering_a_tesselated_terrain/main.cpp)

This code sample shows one of the ways to draw a terrain. A complete graphics pipeline with all five programmable stages is used that tessellates the terrain near the camera to improve its complexity, with level of details faiding away with increasing distance from the camera, and with a flat shading lighting algorithm.<br>
<b>Left mouse button:</b> rotate the scene<br>
<b>Mouse wheel:</b> zoom in / zoom out

<img src="./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/05-Rendering_a_fullscreen_quad_for_postprocessing/screenshot.png" width="150px" align="right">

* ### [05 - Rendering a fullscreen quad for postprocessing](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/05-Rendering_a_fullscreen_quad_for_postprocessing/main.cpp)

Sample presenting a fast and easy way to prepare an image postprocessing phase in a graphics pipeline - by using a fullscreen quad drawn already in a clip space. An edge detection algorithm is shown as on of the examples of postprocessing techniques.

<img src="./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/06-Using_input_attachment_for_color_correction_postprocess_effect/screenshot.png" width="150px" align="right">

* ### [06 - Using an input attachment for color correction postprocess effect](./Samples/Source%20Files/12%20Advanced%20Rendering%20Techniques/06-Using_input_attachment_for_color_correction_postprocess_effect/main.cpp)

In this code another postprocessing technique is shown that uses one of the Vulkan's specific features - input attachments, which allow reading data from render targets (attachments) in the same render pass.<br>
<b>Left mouse button:</b> rotate the scene

## [Other](./Samples/Source%20Files/Other/)

<img src="./Samples/Source%20Files/Other/01-Creating_Logical_Device/screenshot.png" width="150px" align="right">

* ### [01 - Creating a logical device](./Samples/Source%20Files/Other/01-Creating_Logical_Device/main.cpp)

Code sample that shows basic Vulkan setup - instance creation, physical device enumeration and logical device creation.

<img src="./Samples/Source%20Files/Other/02-Creating_Swapchain/screenshot.png" width="150px" align="right">

* ### [02 - Creating a swapchain](./Samples/Source%20Files/Other/02-Creating_Swapchain/main.cpp)

Here a swapchain object is created, which allows us to render a scene directly to an application's window.

<img src="./Samples/Source%20Files/Other/03-Using_Render_Passes/screenshot.png" width="150px" align="right">

* ### [03 - Using render passes](./Samples/Source%20Files/Other/03-Using_Render_Passes/main.cpp)

This example shows how to preapre a basic render pass - a description of attachments (render targets) needed to render a geometry.

<img src="./Samples/Source%20Files/Other/04-Using_Graphics_Pipeline/screenshot.png" width="150px" align="right">

* ### [04 - Using a graphics pipeline](./Samples/Source%20Files/Other/04-Using_Graphics_Pipeline/main.cpp)

Sample showing how to create a graphics pipeline, setup its multiple parameters and use it to draw a scene.

<img src="./Samples/Source%20Files/Other/05-Using_Combined_Image_Samplers/screenshot.png" width="150px" align="right">

* ### [05 - Using combined image samplers](./Samples/Source%20Files/Other/05-Using_Combined_Image_Samplers/main.cpp)

Here descriptor sets are introduced. They are required to setup an interface between application and a pipeline and to provide images (textures) to shaders.

<img src="./Samples/Source%20Files/Other/06-Using_Uniform_Buffers/screenshot.png" width="150px" align="right">

* ### [06 - Using uniform buffers](./Samples/Source%20Files/Other/06-Using_Uniform_Buffers/main.cpp)

Another example of using descriptor sets, but this time it presented how to prepare transformation matrices and provide them to shaders.

<img src="./Samples/Source%20Files/Other/07-Using_Push_Constants/screenshot.png" width="150px" align="right">

* ### [07 - Using push constants](./Samples/Source%20Files/Other/07-Using_Push_Constants/main.cpp)

This code sample presents a very fast and easy way to provide data to shaders - push constants. Though the provided data may not be too big, they are ideal for performing frequent updates.

<img src="./Samples/Source%20Files/Other/08-Using_Tessellation_Shaders/screenshot.png" width="150px" align="right">

* ### [08 - Using tessellation shaders](./Samples/Source%20Files/Other/08-Using_Tessellation_Shaders/main.cpp)

Here we can see how to create a graphics pipeline with tessellation control and evaluation shaders enabled responsible for increasing the complexity of a rendered geometry.

<img src="./Samples/Source%20Files/Other/09-Using_Geometry_Shaders/screenshot.png" width="150px" align="right">

* ### [09 - Using geometry shaders](./Samples/Source%20Files/Other/09-Using_Geometry_Shaders/main.cpp)

Sample presenting how to use geometry shaders and generate new primitives instead of those drawn in an application.

<img src="./Samples/Source%20Files/Other/10-Using_Compute_Shaders/screenshot.png" width="150px" align="right">

* ### [10 - Using compute shaders](./Samples/Source%20Files/Other/10-Using_Compute_Shaders/main.cpp)

This code sample shows how to create a compute pipeline - the second type of pipelines supported in the Vulkan API. It allows us to perform mathematical computations.

<img src="./Samples/Source%20Files/Other/11-Drawing_Vertex_Normals/screenshot.png" width="150px" align="right">

* ### [11 - Drawing vertex normals](./Samples/Source%20Files/Other/11-Drawing_Vertex_Normals/main.cpp)

Here a commonly used debugging technique is presented that uses geometry shaders to display normal vectors provided by the application.

<img src="./Samples/Source%20Files/Other/12-Using_Depth_Attachments/screenshot.png" width="150px" align="right">

* ### [12 - Using depth attachments](./Samples/Source%20Files/Other/12-Using_Depth_Attachments/main.cpp)

In this example we can see how to setup a render pass, framebufer and a graphics pipeline to use depth attachment and enable depth test during drawing.

<hr>

# [Recipes Library](./Library/Source%20Files/)

## [Chapter 01 - Instance and Devices](./Library/Source%20Files/01%20Instance%20and%20Devices/)

* [03 - Connecting with a Vulkan Loader library](./Library/Source%20Files/01%20Instance%20and%20Devices/03%20Connecting%20with%20a%20Vulkan%20Loader%20library.cpp)

* [05 - Loading function exported from a Vulkan Loader library](./Library/Source%20Files/01%20Instance%20and%20Devices/05%20Loading%20function%20exported%20from%20a%20Vulkan%20Loader%20library.cpp)

* [06 - Loading global-level functions](./Library/Source%20Files/01%20Instance%20and%20Devices/06%20Loading%20global-level%20functions.cpp)

* [07 - Checking available Instance extensions](./Library/Source%20Files/01%20Instance%20and%20Devices/07%20Checking%20available%20Instance%20extensions.cpp)

* [08 - Creating a Vulkan Instance](./Library/Source%20Files/01%20Instance%20and%20Devices/08%20Creating%20a%20Vulkan%20Instance.cpp)

* [09 - Loading instance-level functions](./Library/Source%20Files/01%20Instance%20and%20Devices/09%20Loading%20instance-level%20functions.cpp)

* [10 - Enumerating available physical devices](./Library/Source%20Files/01%20Instance%20and%20Devices/10%20Enumerating%20available%20physical%20devices.cpp)

* [11 - Checking available device extensions](./Library/Source%20Files/01%20Instance%20and%20Devices/11%20Checking%20available%20device%20extensions.cpp)

* [12 - Getting features and properties of a physical device](./Library/Source%20Files/01%20Instance%20and%20Devices/12%20Getting%20features%20and%20properties%20of%20a%20physical%20device.cpp)

* [13 - Checking available queue families and their properties](./Library/Source%20Files/01%20Instance%20and%20Devices/13%20Checking%20available%20queue%20families%20and%20their%20properties.cpp)

* [14 - Selecting index of a queue family with desired capabilities](./Library/Source%20Files/01%20Instance%20and%20Devices/14%20Selecting%20index%20of%20a%20queue%20family%20with%20desired%20capabilities.cpp)

* [15 - Creating a logical device](./Library/Source%20Files/01%20Instance%20and%20Devices/15%20Creating%20a%20logical%20device.cpp)

* [16 - Loading device-level functions](./Library/Source%20Files/01%20Instance%20and%20Devices/16%20Loading%20device-level%20functions.cpp)

* [17 - Getting a device queue](./Library/Source%20Files/01%20Instance%20and%20Devices/17%20Getting%20a%20device%20queue.cpp)

* [18 - Creating a logical device with geometry shaders and graphics queue](./Library/Source%20Files/01%20Instance%20and%20Devices/18%20Creating%20a%20logical%20device%20with%20geometry%20shaders%20and%20graphics%20queue.cpp)

* [19 - Destroying a logical device](./Library/Source%20Files/01%20Instance%20and%20Devices/19%20Destroying%20a%20logical%20device.cpp)

* [20 - Destroying a Vulkan Instance](./Library/Source%20Files/01%20Instance%20and%20Devices/20%20Destroying%20a%20Vulkan%20Instance.cpp)

* [21 - Releasing a Vulkan Loader library](./Library/Source%20Files/01%20Instance%20and%20Devices/21%20Releasing%20a%20Vulkan%20Loader%20library.cpp)

## [Chapter 02 - Image Presentation](./Library/Source%20Files/02%20Image%20Presentation/)

* [01 - Creating a Vulkan Instance with WSI extensions enabled](./Library/Source%20Files/02%20Image%20Presentation/01%20Creating%20a%20Vulkan%20Instance%20with%20WSI%20extensions%20enabled.cpp)

* [02 - Creating a presentation surface](./Library/Source%20Files/02%20Image%20Presentation/02%20Creating%20a%20presentation%20surface.cpp)

* [03 - Selecting a queue family that supports presentation to a given surface](./Library/Source%20Files/02%20Image%20Presentation/03%20Selecting%20a%20queue%20family%20that%20supports%20presentation%20to%20a%20given%20surface.cpp)

* [04 - Creating a logical device with WSI extensions enabled](./Library/Source%20Files/02%20Image%20Presentation/04%20Creating%20a%20logical%20device%20with%20WSI%20extensions%20enabled.cpp)

* [05 - Selecting a desired presentation mode](./Library/Source%20Files/02%20Image%20Presentation/05%20Selecting%20a%20desired%20presentation%20mode.cpp)

* [06 - Getting capabilities of a presentation surface](./Library/Source%20Files/02%20Image%20Presentation/06%20Getting%20capabilities%20of%20a%20presentation%20surface.cpp)

* [07 - Selecting a number of swapchain images](./Library/Source%20Files/02%20Image%20Presentation/07%20Selecting%20a%20number%20of%20swapchain%20images.cpp)

* [08 - Choosing a size of swapchain images](./Library/Source%20Files/02%20Image%20Presentation/08%20Choosing%20a%20size%20of%20swapchain%20images.cpp)

* [09 - Selecting desired usage scenarios of swapchain images](./Library/Source%20Files/02%20Image%20Presentation/09%20Selecting%20desired%20usage%20scenarios%20of%20swapchain%20images.cpp)

* [10 - Selecting a transformation of swapchain images](./Library/Source%20Files/02%20Image%20Presentation/10%20Selecting%20a%20transformation%20of%20swapchain%20images.cpp)

* [11 - Selecting a format of swapchain images](./Library/Source%20Files/02%20Image%20Presentation/11%20Selecting%20a%20format%20of%20swapchain%20images.cpp)

* [12 - Creating a swapchain](./Library/Source%20Files/02%20Image%20Presentation/12%20Creating%20a%20swapchain.cpp)

* [13 - Getting handles of swapchain images](./Library/Source%20Files/02%20Image%20Presentation/13%20Getting%20handles%20of%20swapchain%20images.cpp)

* [14 - Creating a swapchain with R8G8B8A8 format and a MAILBOX present mode](./Library/Source%20Files/02%20Image%20Presentation/14%20Creating%20a%20swapchain%20with%20R8G8B8A8%20format%20and%20a%20MAILBOX%20present%20mode.cpp)

* [15 - Acquiring a swapchain image](./Library/Source%20Files/02%20Image%20Presentation/15%20Acquiring%20a%20swapchain%20image.cpp)

* [16 - Presenting an image](./Library/Source%20Files/02%20Image%20Presentation/16%20Presenting%20an%20image.cpp)

* [17 - Destroying a swapchain](./Library/Source%20Files/02%20Image%20Presentation/17%20Destroying%20a%20swapchain.cpp)

* [18 - Destroying a presentation surface](./Library/Source%20Files/02%20Image%20Presentation/18%20Destroying%20a%20presentation%20surface.cpp)

## [Chapter 03 - Command Buffers and Synchronization](./Library/Source%20Files/03%20Command%20Buffers%20and%20Synchronization/)

## [Chapter 04 - Resources and Memory](./Library/Source%20Files/04%20Resources%20and%20Memory/)

## [Chapter 05 - Descriptor Sets](./Library/Source%20Files/05%20Descriptor%20Sets/)

## [Chapter 06 - Render Passes and Framebuffers](./Library/Source%20Files/06%20Render%20Passes%20and%20Framebuffers/)

## [Chapter 08 - Graphics and Compute Pipelines](./Library/Source%20Files/08%20Graphics%20and%20Compute%20Pipelines/)

## [Chapter 09 - Command Recording and Drawing](./Library/Source%20Files/09%20Command%20Recording%20and%20Drawing/)

## [Chapter 10 - Helper Recipes](./Library/Source%20Files/10%20Helper%20Recipes/)
