# dx9_to_dx11

used flip model to display video (Dx11) on an hWnd. Now I want to use BitBlt model of Direct3D9 to display video on the same hWnd. How can I turn off flip model of Dx11?
For special reasons, I need to turn off Dx11 after using Dx11 display, and then use DX9 to display video.
The actual test result is: even after I release both swapchain and d3ddevice, I still can't use the BitBlt model of Direct3D9 to display video. Is there something wrong with the release code.
