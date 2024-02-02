# Epic GPULightmass Landscape Patch for UE 5.3.2

The problem with Landscape has been fixed there is a commit for UE 5.4 which has been converted to UE 5.3.2

[Initial Landscape error post](https://forums.unrealengine.com/t/gpu-lightmass-not-working-on-landscape/1371174)

The reported fix is below

[GPULM: Fix Landscape vertex factory incorrect position component format](https://issues.unrealengine.com/issue/UE-199910)

The binary for this fix has been compiled into UnrealEditor-GPULightmass.dll

Click on the green "Code" button to get a zip which you unload

into root DRIVE:\Program Files\Epic Games\UE_5.3

This patch is currently UNTESTED, one user says it works! please test it!. Report your findings in the thread

The test file is available in the post 

[Landscape test project](https://forums.unrealengine.com/t/gpu-lightmass-not-working-on-landscape/1371174/8)

Remember to check DXRI is set to DX12 and SM6 in your Project setting 

which are needed for all projects using EPIC GPU Lightmass (EGPU) 

The SM5 shaders may need to be temporarily disabled for the projects shaders to be compiled in SM6

[posting thread to report testing Landscape patch](https://forums.unrealengine.com/t/gpu-lightmass-not-working-on-landscape/1371174)

So commit has been converted to 5.3.2 source in the file

in the path Engine\Plugins\Experimental\GPULightmass\Source\GPULightmass\Private\Scene\Scene.cpp

LEGAL

NO WARRANTY and no responsibilty on behalf of any party is given for the patch. This makes you 5.3.2 binary no longer production version

If there is a problem and you want to remove the patch.

The best way is to go into the Epic Games Launcher where you installed 5.3.2

Right click on the yellow down arrow and select "Verify".

This will remove all the patches forr
Epic GPULightmass and Luoshuang’s GPULightmass patches
