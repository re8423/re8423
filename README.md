# Hi 👋, I'm Rei, an aspiring Data Scientist and Engineer!

### I am current completing my MSc in Scientific Computing and Data Analysis (Financial Technology) at Durham University
> Bsc: Computer Science (Durham - 1st Class hons)

## Contents:
This page contains information on my skills, background as well as work experience:
1. [Technical skills 💻](#my-technology-stack-hover-over-for-names)
2. [University Projects 👩‍💻](#my-university-degree-)
3. [Career 👷‍♀️](#my-career-)

Additionally, here is my LinkedIn!:

<a href="https://www.linkedin.com/in/rei-ishii-5778a6221/"><img src="https://img.icons8.com/color/96/000000/linkedin.png"/></a>

# My Technology Stack (hover over for names):
### Professional:
<center><div>
    <img src="https://img.icons8.com/color/96/000000/python.png" title="Python"/>
    <img src="https://pytorch.org/assets/images/pytorch-logo.png" width="96" title="PyTorch"/>
    <img src="https://numfocus.org/wp-content/uploads/2016/07/pandas-logo-300.png" width="96" title="Pandas"/>
    <img src="https://cdn-images-1.medium.com/max/1200/1*iDQvKoz7gGHc6YXqvqWWZQ.png" width="96" title="Tensorflow"/>
    <img src="https://user-images.githubusercontent.com/67586773/105040771-43887300-5a88-11eb-9f01-bee100b9ef22.png" width="96" title="Numpy"/>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" width="96" title="scikit-learn"/>
    <img src="https://img.icons8.com/color/48/000000/git.png" title="Git"/>
    <img src="https://img.icons8.com/color/48/000000/latex.png" title="LaTeX"/>
    <img src="https://user-images.githubusercontent.com/50221806/86498227-c985dc00-bd39-11ea-9135-3e82bab6d664.png" width="48" title="NumPy"/>
    <img src="https://img.icons8.com/color/48/000000/c-plus-plus-logo.png" title="C++"/>
    <img src="https://img.icons8.com/color/48/000000/javascript--v1.png" title="JavaScript"/>
    <img src="https://img.icons8.com/fluency/48/000000/c.png" title="C"/>
    <img src="https://img.icons8.com/color/48/000000/nodejs.png" title="Node.js"/>
    <img src="https://icons8.com/icon/ZMFmFsekpKfY/ruby-on-rails" title="Ruby on Rails"/>
    <img src="https://img.icons8.com/color/48/000000/css3.png" title="CSS"/>
    <img src="https://img.icons8.com/color/48/000000/react-native.png" title="React.js"/>
    <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" title="HTML-5"/>
    <img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo--v1.png" title="Java"/>
    <img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/external-c-sharp-computer-programming-flaticons-lineal-color-flat-icons.png" title="C#"/>
</div></center>


### Intermediate:
<center><div>
    <img src="https://img.icons8.com/color/48/000000/mongodb.png" title="MongoDB & Mongoose"/>
    <img src="https://img.icons8.com/color/48/000000/sql.png" title="SQL"/>
    <img src="https://img.icons8.com/color/48/000000/amazon-web-services.png" title="AWS"/>
    <img src="https://img.icons8.com/color/48/docker.png" title="Docker"/>
    <img src="https://img.icons8.com/color/48/kubernetes.png" title="Kubernetes"/>
</div></center>

## Notable University projects:

* Dissertation - [Improved Density-Estimation and Restoration based Vector-Quantized Anomaly Detection](https://github.com/re8423/VQ_Anomaly_Improved): 83/100. [Pytorch]
    >![demo](https://github.com/re8423/VQ_Anomaly_Improved/blob/7f2a9b92a0ccf0d49124d1951eaca029cf132d84/Images/light_wise_vae_trans_anom(1).gif)
    >
    > Vector-Quantized anomaly detection remains a new and relatively unexplored area of research, thus it is necessary to
determine the optimal architectures for existing methods, and hence compare their performances. This paper explores how different
designs of the Vector-Quantized model and Auto-Regressive model impact the performance of Density-Estimation and Restoration
based anomaly detection. This was done by introducing perceptual quality to the learned vector codebook, as well as comparing
PixelSnail and the GPT-2 Transformer as Auto-Regressive models to determine the need for learning local spatial dependencies.
Extensive experimentation found that Vector-Quantized models utilizing a perceptually rich codebook allowed it to perform better than
existing state of the art methods. Furthermore, learning local spatial dependencies was found to be of importance for Restoration
methods, which encourages the use of Auto-Regressive models that include convolutional layers. It was also found that unlikely latent
variables do not necessarily correspond to anomalous regions, thus revealing an inherent weakness of Restoration-based methods.
Lastly, this paper also outlined the high computational cost of the current Vector-Quantized Restoration method, and proposes
Light-Pixel-wise detection, a much faster, light-weight variant with improved performance

* Deep Learning - [Image Generative Models](https://github.com/re8423/Generative_Images_with_VQ-VAE): 90/100. [Pytorch]
    > ![samples](https://github.com/re8423/Generative_Images_with_VQ-VAE/blob/df4b25f68352cf9ed1eff284f5a2df46978fc6cc/Gen_samples/samples.png)
    >
    > I used a vector-quantised variational autoencoder (VQ-VAE) to learn the codebooks of the FFHQ dataset, and use that together with a transformer utilizing masked training to sample new images. The VQ-VAE is a model which uses discrete latent embeddings for its autoencoder component. In a typical variational autoencoder, the prior and posterior are assumed to be normally distributed with a diagonal variance, and the encoder is used to predict the posterior mean and variance. In the VQ-VAE however, instead of a continuous normal distribution, discrete latent variables are used, and hence the prior and posterior distributions are a uniform categorical distribution.
  
* Reinforcement Learning - [Bipedal Walker with Truncated Quantile Critics](https://github.com/re8423/Bipedal_walker_TQC): 85/100. [Pytorch]
    > ![hardcore](https://github.com/re8423/Bipedal_walker_TQC/blob/30581c2d05a6db44b526479b8e7fa05e2d5db971/Results/agent-hardcore-video%2C%20episode%3D1000%2C%20score%3D312.gif)
    >
    > I used the Truncated Quantile Critics (TQC) to overcome overestimation bias in off policy learning for the bipedal walker environment. In deep reinforcement learning, for each state-action pair the Q-function calculates Qθ(s, a) to predict the expected reward. Overestimation bias occurs when the estimated Qθ(s, a) are greater than the true values Q(s, a) (overestimation of future rewards). If the policy exploits the overestimations it can lead to poor performance. TQC is a predecessor of the Soft actor critic (SAC) algorithm and attempts to alleviate this by incorporating the distributional representation of a critic, truncation of critic predictions, and the ensembling of multiple critics.

