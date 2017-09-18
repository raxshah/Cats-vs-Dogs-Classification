# Cats vs Dogs (Kaggle -Deep Learning)



## Problem Statement

[Asirra](http://research.microsoft.com/en-us/um/redmond/projects/asirra/) (Animal Species Image Recognition for Restricting Access) requires identifying Dogs and Cats from given images. The current literature suggests machine classifiers can score above 80% accuracy on this task. They need more advance techniques improve accuracy

## Techniques

Fine-tune Vgg16 model to solve Cats vs Dogs classification problem.

## Tools and Libraries

- Vgg16 model
- Keras
- Scikit learn

## Results

Result file is available inside /submission/ directory

- 0.10 score on Public leader board on Kaggle
- top 50% score in Kaggle competition.

## Difficulties

- Setup GPU on AWS (as this is my first deep learning project)
- Keep data in proper structure so vgg16 and keras model can read it.

## Future Scope

Apply similar techniques to other object detection application/competition like [Right Whale Recognition](https://www.kaggle.com/c/noaa-right-whale-recognition), [Galaxy Zoo - The Galaxy Challenge](https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/) etc.

## Reference

- [http://course.fast.ai/](http://course.fast.ai/)
- [https://www.kaggle.com/c/dogs-vs-cats](https://www.kaggle.com/c/dogs-vs-cats)