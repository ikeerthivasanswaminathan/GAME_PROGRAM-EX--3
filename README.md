# GAME PROGRAMMING - EX - 3

## EXP - 3 Change the third person character mesh and add animations

## Name : KEERTHIVASAN S
## Reg no : 212223220046

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure

1. **Import New Character Mesh and Animations:**
   - In the **Content Browser**, import a new **Skeletal Mesh** along with its **Animations** (FBX files).
   - Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

2. **Replace Character Mesh:**
   - Open the **ThirdPersonCharacter Blueprint** (usually found in `ThirdPersonBP/Blueprints`).
   - Select the **Mesh** component.
   - In the **Details Panel**, change the **Skeletal Mesh** to the newly imported mesh.

3. **Set Animation Blueprint:**
   - If available, assign a matching **Animation Blueprint** in the **Details Panel** under the **Animation** section.
   - If not available, create one:
     - Right-click in the Content Browser → **Animation → Animation Blueprint**.
     - Choose the correct skeleton.
     - In the AnimGraph, set up state machines or direct animation nodes.
     - Compile and save.

4. **Preview and Test:**
   - Place the character in the level.
   - Press **Play** to test idle, walk, and run animations based on character movement.
  
## Output

<img width="843" height="577" alt="op1" src="https://github.com/user-attachments/assets/78869110-8ca6-49e8-b207-e878b14b6cd6" />

<img width="476" height="420" alt="op2" src="https://github.com/user-attachments/assets/fe59c2dd-c878-4185-9c4b-92a209bbc932" />

<img width="1541" height="912" alt="op3" src="https://github.com/user-attachments/assets/145c7063-724c-47a9-9101-2c54a75a4246" />

## Result
Therefore, the default Third Person is C.
