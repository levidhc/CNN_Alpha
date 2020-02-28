# CNN_Alpha

This is derivative work from literature review of a paper, intending to serve as potential benchmark alphas for the research project developed under ETC Investment Group, Academy Division. The code developed is supported by QIML. The underlying logic and technique follows through with the abstract:

"Computational intelligence techniques for ﬁnancial trading systems have always been quite popular. In the last decade, deep learning models start getting more attention, especially within the image processing community. In this study, we propose a novel algorithmic trading model CNN-TA using a 2-D Convolutional Neural Network based on image processing properties. In order to convert ﬁnancial time series into 2-D images, 15 diﬀerent technical indicators each with diﬀerent parameter selections are utilized. Each indicator instance generates data for a 15 day period. As a result, 15x15 sized 2-D images are constructed. Each image is then labelled as Buy, Sell or Hold depending on the hills and valleys of the original time series. The results indicate that when compared with the Buy & Hold Strategy and other common trading systems over a long out-of-sample period, the trained model provides better results for stocks and ETFs. "

Although differ in underlying methodology, the time horizon of this trading approach is in line with ETC's main alpha intented rebalancing period. This benchmark alpha and its associated data can be used to incrementally train our models to its optimized form. 
