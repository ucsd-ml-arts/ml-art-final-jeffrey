# Final Project

Jeffrey Yeung, c1yeung@ucsd.edu

## Abstract Proposal

For this project, I want to revisit and combine the techniques used in project 1: text generation, and project 4: style transfer. I want to generate a description of an object using character-based RNN then turn that description into an image, and finally applying style transfer onto it to make it look more artistic and unique. I think this will be an interesting process because every step of the process will be generated, and the only input I am providing is the training corpus text file.

## Project Report

Uploaded as Final_Report.pdf

## Model/Data

sciencetext.csv - Contains texts of video descriptions for science and nature related videos

people.jpg, colors.jpg, glass.jpg - Style images for applying style transfer

data, miscc folder - Contains data required for AttnGAN

model.py, GlobalAttention.py - Used to run AttnGAN to generate images from caption

## Code

- Jupyter notebooks: Final.ipynb

## Results

Generated text from video captions of science videos:

'a blue bird flying in the sky'

Generated bird image from caption:

![bird1](https://github.com/ucsd-ml-arts/ml-art-final-jeffrey/blob/master/bird1.png)

Bird image after style transfer:

![bird1ST](https://github.com/ucsd-ml-arts/ml-art-final-jeffrey/blob/master/bird1ST.png)

Second generated bird image from caption:

![bird2](https://github.com/ucsd-ml-arts/ml-art-final-jeffrey/blob/master/bird2.png)

After style transfer:

![bird2ST](https://github.com/ucsd-ml-arts/ml-art-final-jeffrey/blob/master/bird2ST.png)

Third example:

![bird3](https://github.com/ucsd-ml-arts/ml-art-final-jeffrey/blob/master/bird3.png)

After style transfer:

![bird3ST](https://github.com/ucsd-ml-arts/ml-art-final-jeffrey/blob/master/bird3ST.png)

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts
