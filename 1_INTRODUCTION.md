# Learn WebGPU with Rust
Welcome. 

### What is WebGPU?
WebGPU is a low-level graphics API that provides direct access to the graphics hardware on a user's device. It is designed to be used with the latest generation of graphics hardware, and is intended to provide a more efficient, low-level alternative to other web graphics APIs such as WebGL. WebGPU is still in development and is not currently widely supported in web browsers.

The full (draft) specification can be found here: https://gpuweb.github.io/gpuweb/ It is worth while to read this page and use it as a reference, but it's not an easy read, whereas this website is.

### What is WebGPU Shading Language (WGSL)?
WebGPU Shading Language is a low-level shading language that is designed to be used with the WebGPU API. It is based on the existing Metal Shading Language and is intended to provide developers with a way to write shaders that can run on the web using the WebGPU API. Shaders written in this language can be used to program the graphical processing units (GPUs) found in many modern computers and devices, allowing developers to create complex and visually impressive graphics for web applications.

The full (draft) specification can be found here: https://www.w3.org/TR/WGSL/

### What is WGPU?
WGPU is a Rust library that provides safe and convenient access to the WebGPU API. It allows developers to write graphics and compute programs in Rust that can run on the web using WebAssembly. WGPU is designed to be low-level and close to the metal, giving developers maximum control over the performance and behavior of their programs. It also provides high-level abstractions for common graphics and compute tasks, making it easier to write fast and efficient code.

### What are the fundametnals of WebGPU?
WebGPU is a low-level API for accessing the graphical hardware of a computer directly from a web browser. It is designed to provide high-performance graphics and make it easier for developers to build 3D graphics applications for the web.

Some of the fundamental concepts of WebGPU include:

* Buffers: A buffer is a chunk of memory that is used to store data that will be processed by the GPU. Buffers can be used to store vertex data, index data, and other types of data that are required for rendering 3D graphics.
* Textures: A texture is a 2D image that is used to add detail and texture to 3D objects. Textures can be applied to the surfaces of 3D objects in a variety of ways, and can be used to create a wide range of visual effects.
* Shaders: Shaders are small programs that run on the GPU and are used to manipulate the data in buffers and textures in order to produce the final image that is displayed on the screen. Shaders are written in a special programming language called WGSL (WebGPU Shading Language).
* Pipelines: A pipeline is a sequence of steps that are performed by the GPU in order to render a 3D scene. This typically includes steps such as vertex shading, primitive assembly, rasterization, and fragment shading.

Overall, WebGPU is designed to provide developers with a low-level, flexible, and efficient way to access the graphical capabilities of a computer from a web browser.


```rs
let x = 1;

fn foo_bar(x: u64)
{
  ley y = 2.0;
}
```
