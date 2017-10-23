#ECT image reconstruction and detection of hidden materials

## Simulation Setup

### 100 pixels and 12 electrodes

![image](https://user-images.githubusercontent.com/5483365/31868410-7a73085c-b76c-11e7-91d1-8485b4cd71d6.png)
![image](https://user-images.githubusercontent.com/5483365/31868414-885bf028-b76c-11e7-908f-6eec18c85fbe.png)

### Human and Metal Box using COMSOL 4.2 (Simulation)

![image](https://user-images.githubusercontent.com/5483365/31868393-48f0f4ce-b76c-11e7-9da8-45dd632f0b83.png)

Reconstructed image of human and box at 20kHz using Landweber algorithm (alpha = 0.05, 1000 iterations)
![image](https://user-images.githubusercontent.com/5483365/31868502-ab631e56-b76d-11e7-96f3-4aaddfbc1059.png)

Reconstructed image of human and box but this time at 100kHz using Landweber algorithm (alpha = 0.05, 1000 iterations)
![image](https://user-images.githubusercontent.com/5483365/31868611-eb37d20a-b76e-11e7-8f59-0d5163542d7d.png)

Subracting the 100kHz image and the 20kHz image, gives the image of the box.
![image](https://user-images.githubusercontent.com/5483365/31868617-fa00e3d0-b76e-11e7-8d9c-400a3695e56c.png)

### Human with Metal 'Gun' (in red) in pocket using COMSOL 4.2 (Simulation)

Original Image
![image](https://user-images.githubusercontent.com/5483365/31868682-e510518a-b76f-11e7-897b-32412824031f.png)

Reconstructed image of human and box at 20kHz using Landweber algorithm (alpha = 0.05, 1000 iterations)
![image](https://user-images.githubusercontent.com/5483365/31868694-f6c18a52-b76f-11e7-8444-4fc8e225f03b.png)

Reconstructed image of human and box at 20kHz using Landweber algorithm (alpha = 0.05, 1000 iterations)
![image](https://user-images.githubusercontent.com/5483365/31868696-ff95b824-b76f-11e7-80d3-e84d3cda150d.png)

Subtracted
![image](https://user-images.githubusercontent.com/5483365/31868704-10e660ce-b770-11e7-8fb3-a27f2b6ff611.png)
