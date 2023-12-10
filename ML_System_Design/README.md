# Machine Learning System Design Interview Reading List
Welcome to the [Machine Learning System Design Interview](https://www.amazon.com/Machine-Learning-System-Design-Interview/dp/1736049127/ref=sr_1_1?crid=1N7OYRAM2K046&keywords=machine+learning+system+design+interview&qid=1698602213&sprefix=%2Caps%2C173&sr=8-1) Reading List! This curated list is from the Reference Materials at each chapter of the above listed book.

Another good MLSD resources can be found in this [repo](https://github.com/alirezadir/Machine-Learning-Interviews). Be sure to check it out.

## Chapter 1: Introduction and Overview
TODO
- [x] [Data warehouse](https://cloud.google.com/learn/what-is-a-data-warehouse)
- [] []()
- [] []()
- [] []()

## Chapter 2: Visual Search System
- [x] [Visual search at pinterest](https://arxiv.org/pdf/1505.07647.pdf)
- [x] [Unifying visual embeddings for search at Pinterest](https://medium.com/pinterest-engineering/unifying-visual-embeddings-for-visual-search-at-pinterest-74ea7ea103f0)
- [x] [Representation learning](https://en.wikipedia.org/wiki/Feature_learning)
- [x] [ResNet paper](https://arxiv.org/abs/1512.03385)
- [x] [Transformer paper - Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [x] [Vision transformer paper](https://arxiv.org/abs/2010.11929)
- [x] [SimCLR - A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709)
- [ ] [MoCo paper](https://arxiv.org/pdf/1911.05722.pdf) 
- [x] [Constractive Representation Learning Methods](https://lilianweng.github.io/posts/2019-11-10-self-supervised/)
- [x] [Dot product](https://en.wikipedia.org/wiki/Dot_product)
- [x] [Cosine similarity](https://en.wikipedia.org/wiki/Cosine_similarity)
- [x] [Euclidean distance](https://en.wikipedia.org/wiki/Euclidean_distance)
- [x] [Curse of dimensionality](https://en.wikipedia.org/wiki/Curse_of_dimensionality)
- [x] [Curse of dimensionality issue in ML](https://www.mygreatlearning.com/blog/understanding-curse-of-dimensionality/)
- [x] [Cross-entropy loss](https://en.wikipedia.org/wiki/Cross-entropy)
- [ ] [Vector quantization](http://www.ws.binghamton.edu/fowler/fowler%20personal%20page/EE523_files/Ch_10_1%20VQ%20Description%20(PPT).pdf)
- [ ] [Product quantization](https://towardsdatascience.com/product-quantization-for-similarity-search-2f1f67c5fddd)
- [ ] [R-Trees](https://en.wikipedia.org/wiki/R-tree)
- [x] [KD-Trees](https://kanoki.org/2020/08/05/find-nearest-neighbor-using-kd-tree/)
- [ ] [Annoy](https://towardsdatascience.com/comprehensive-guide-to-approximate-nearest-neighbors-algorithms-8b94f057d6b6)
- [ ] [Locality-sensitive hashing](http://web.stanford.edu/class/cs246/slides/03-lsh.pdf)
- [ ] [Fais library](https://github.com/facebookresearch/faiss)
- [ ] [ScaNN library](https://github.com/google-research/google-research/tree/master/scann)
- [x] [Cotent moderation with ML](https://appen.com/blog/content-moderation/)
- [x] [Bias in AI and recommendation systems](https://www.searchenginejournal.com/biases-search-recommender-systems/339319/#close)
- [x] [Positional bias](https://eugeneyan.com/writing/position-bias/)
- [x] [Smart crop](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2018/Smart-Auto-Cropping-of-Images)
- [ ] [Better search with gnns](https://arxiv.org/pdf/2010.01666.pdf)
- [x] [Active learning](https://en.wikipedia.org/wiki/Active_learning_(machine_learning))
- [ ] [Human-in-the-loop ML](https://arxiv.org/pdf/2108.00941.pdf)

## Chapter 3: Google Stree View Blurring System
- [x] [Google Street View](https://www.google.com/streetview/)
- [x] [DETR](https://github.com/facebookresearch/detr)
- [x] [RCNN family](https://lilianweng.github.io/posts/2017-12-31-object-recognition-part-3/)
- [x] [Fast RCNN](https://arxiv.org/abs/1504.08083)
- [x] [Faster RCNN](https://arxiv.org/abs/1506.01497)
- [ ] [YOLO family](https://pyimagesearch.com/2022/04/04/introduction-to-the-yolo-family/)
- [ ] [SSD](https://jonathan-hui.medium.com/ssd-object-detection-single-shot-multibox-detector-for-real-time-processing-9bd8deac0e06)
- [x] [Data augmentation techiniques](https://www.kaggle.com/discussions/getting-started/190280)
- [x] [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network)
- [ ] [Object detection details](https://dudeperf3ct.github.io/object/detection/2019/01/07/Mystery-of-Object-Detection/)
- [ ] [Forward pass and backward pass - Andrew Ng Youtube Video](https://www.youtube.com/watch?v=qzPQ8cEsVK8)
- [x] [MSE](https://en.wikipedia.org/wiki/Mean_squared_error)
- [x] [Log loss/cross entropy loss](https://en.wikipedia.org/wiki/Cross-entropy)
- [x] [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/voc2008/index.html)
- [x] [Coco dataset evaluation](https://cocodataset.org/#detection-eval)
- [ ] [Object detection evaluation](https://github.com/rafaelpadilla/Object-Detection-Metrics)
- [ ] [Non-maximum suppression (NMS)](https://en.wikipedia.org/wiki/NMS)
- [x] [Python implementation of NMS](https://learnopencv.com/non-maximum-suppression-theory-and-implementation-in-pytorch/)
- [x] [Recent object detection models](https://viso.ai/deep-learning/object-detection/)
- [x] [Distributed training in TensorFlow](https://www.tensorflow.org/guide/distributed_training)
- [x] [Distributed training in Pytorch](https://pytorch.org/tutorials/beginner/dist_overview.html)
- [x] [GDPR and ML](https://www.oreilly.com/radar/how-will-the-gdpr-impact-machine-learning/)
- [ ] [Bias and fairness in face detectin](http://sibgrapi.sid.inpe.br/col/sid.inpe.br/sibgrapi/2021/09.04.19.00/doc/103.pdf)
- [x] [AI fairness](https://www.kaggle.com/code/alexisbcook/ai-fairness)
- [x] [Continue learing](https://towardsdatascience.com/how-to-apply-continual-learning-to-your-machine-learning-models-4754adcd7f7f)
- [x] [Active learning](https://en.wikipedia.org/wiki/Active_learning_(machine_learning))
- [x] [Human-in-the-loop ML](https://arxiv.org/pdf/2108.00941.pdf)

## Chapter 4: Youtube Video Search
- [ ] [Elasticsearch](https://www.tutorialspoint.com/elasticsearch/elasticsearch_query_dsl.htm)
- [x] [Preprocessing text data](https://huggingface.co/docs/transformers/preprocessing)
- [x] [NFKD normalization](http://unicode.org/reports/tr15/)
- [x] [What is Tokenization summary](https://huggingface.co/docs/transformers/tokenizer_summary)
- [x] [Hash collision](https://en.wikipedia.org/wiki/Hash_collision)
- [ ] [Deep Learning for NLP](http://cs224d.stanford.edu/lecture_notes/notes1.pdf)
- [x] [TI-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)
- [x] [Word2Vec models](https://www.tensorflow.org/text/tutorials/word2vec)
- [ ] [Continuous bag of words](https://www.kdnuggets.com/2018/04/implementing-deep-learning-methods-feature-engineering-text-data-cbow.html)
- [ ] [Skip-gram model](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)
- [x] [BERT model](https://arxiv.org/abs/1810.04805)
- [ ] [GPT3 model](https://arxiv.org/abs/2005.14165)
- [x] [BLOOM model](https://bigscience.huggingface.co/blog/bloom)
- [x] [Transformer implementation from scratch](https://peterbloem.nl/blog/transformers)
- [x] [3D convolutions](https://www.kaggle.com/code/shivamb/3d-convolutions-understanding-use-case/notebook)
- [ ] [Vision Transformer](https://arxiv.org/abs/2010.11929)
- [x] [Query understanding for search engines](https://www.linkedin.com/pulse/ai-query-understanding-daniel-tunkelang/)
- [ ] [Multimodel video representation learning](https://arxiv.org/abs/2012.04124)
- [ ] [Multimodel language models](https://arxiv.org/abs/2107.00676)
- [ ] [Near-duplicate video detection](https://arxiv.org/abs/2005.07356)
- [ ] [Generalizable search relevence](https://livebook.manning.com/book/ai-powered-search/chapter-10/v-10/1)
- [x] [Freshness in search and recommendation systems](https://developers.google.com/machine-learning/recommendation/dnn/re-ranking)
- [ ] [Semantic product search by Amazon](https://arxiv.org/pdf/1907.00937.pdf)
- [ ] [Ranking relevance in Yahoo search](https://www.kdd.org/kdd2016/papers/files/adf0361-yinA.pdf)
- [ ] [Semantic product search in E-Commerce](https://arxiv.org/abs/2008.08180)

## Chapter 5: Harmful Content Detection
- [x] [Facebook's inauthentic behavior](https://transparency.fb.com/policies/community-standards/inauthentic-behavior/)
- [x] [LinkedIn's professional community policies](https://www.linkedin.com/legal/professional-community-policies)
- [x] [Twitter's civic integrity policy](https://help.twitter.com/en/rules-and-policies/election-integrity-policy)
- [x] [Facebooks integrity survey](https://arxiv.org/abs/2009.10311)
- [x] [Pinterest's violation detection system](https://medium.com/pinterest-engineering/how-pinterest-fights-misinformation-hate-speech-and-self-harm-content-with-machine-learning-1806b73b40ef)
- [x] [Abusive deteciton at LinkedIn-isolation forests](https://engineering.linkedin.com/blog/2019/isolation-forest)
- [x] [WPIE method](https://ai.meta.com/blog/community-standards-report/)
- [x] [BERT paper](https://arxiv.org/abs/1810.04805)
- [x] [Multilingual DistilBert](https://huggingface.co/distilbert-base-multilingual-cased)
- [ ] [Multilingual language models](https://arxiv.org/abs/2107.00676)
- [ ] [CLIP model](https://openai.com/research/clip)
- [x] [SimCLR paper](https://arxiv.org/abs/2002.05709)
- [ ] [VideoMoCo paper](https://arxiv.org/abs/2103.05905)
- [x] [Hyperparameter tunning](https://cloud.google.com/ai-platform/training/docs/hyperparameter-tuning-overview)
- [x] [Overfitting](https://en.wikipedia.org/wiki/Overfitting)
- [x] [Focal loss](https://amaarora.github.io/posts/2020-06-29-FocalLoss.html)
- [ ] [Graidient blending in multimodel systems](https://arxiv.org/abs/1905.12681)
- [x] [ROC curves vs precision-recall curve](https://machinelearningmastery.com/roc-curves-and-precision-recall-curves-for-classification-in-python/)
- [x] [Introduced bias by human labeling](https://labelyourdata.com/articles/bias-in-machine-learning)
- [ ] [Facebook's approach to quickly tackling trending harmful content](https://ai.meta.com/blog/harmful-content-can-evolve-quickly-our-new-ai-system-adapts-to-tackle-it/)
- [ ] [Facebook's TIES approach](https://arxiv.org/abs/2002.07917)
- [ ] [Temporal interaction embedding](https://www.facebook.com/atscaleevents/videos/730968530723238)
- [ ] [Building and scaling human review system](https://www.facebook.com/atscaleevents/videos/1201751883328695)
- [ ] Abusive account detection framework
- [x] [Borderline contents](https://transparency.fb.com/features/approach-to-ranking/content-distribution-guidelines/content-likely-violating-our-community-standards)
- [ ] [Efficient harmful content detection](https://about.fb.com/news/2021/12/metas-new-ai-system-tackles-harmful-content/)
- [ ] [Linear Transformer paper](https://arxiv.org/abs/2006.16236)
- [ ] [Efficient AI models to detect hate speech](https://ai.meta.com/blog/how-facebook-uses-super-efficient-ai-models-to-detect-hate-speech/)

## Chapter 6: Video Recommendation System
- [x] [Youtube recommendation system](https://blog.youtube/inside-youtube/on-youtubes-recommendation-system/)
- [x] [DNN for Youtube recommendation](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf)
- [ ] [CBOW](https://arxiv.org/pdf/1301.3781.pdf)
- [x] [BERT paper](https://arxiv.org/abs/1810.04805)
- [x] [Matrix factorization](https://developers.google.com/machine-learning/recommendation/collaborative/matrix)
- [x] [Stochastic gradient descent](https://en.wikipedia.org/wiki/Stochastic_gradient_descent)
- [x] [WALS optimization](https://fairyonice.github.io/Learn-about-collaborative-filtering-and-weighted-alternating-least-square-with-tensorflow.html)
- [ ] [Instagram multi-stage recommendation system](https://instagram-engineering.com/powered-by-ai-instagrams-explore-recommender-system-7ca901d2a882)
- [x] [Exploration and exploitation trade-off](https://en.wikipedia.org/wiki/Multi-armed_bandit)
- [x] [Bias in AI and recommendation systems](https://www.searchenginejournal.com/biases-search-recommender-systems/339319/)
- [ ] [Ethical concerns in recommendation systems](https://link.springer.com/article/10.1007/s00146-020-00950-y)
- [ ] [Seasonality in recommendation systems](https://www.computer.org/csdl/proceedings-article/big-data/2019/09005954/1hJsfgT0qL6)
- [ ] [A multitask ranking system](https://daiwk.github.io/assets/youtube-multitask.pdf)
- [ ] [Benefit from a negative feedback](https://arxiv.org/pdf/1607.04228.pdf)

## Chapter 7: Event Recommendation System
- [ ] []()
## Chapter 8: Ad Click Prediction on Social Platforms
## Chapter 9: Similar Listings on Vacation Rental Platforms
## Chapter 10: Personalized News Feed

## Chapter 11: People You May Know
- [x] [Clustering in ML](https://developers.google.com/machine-learning/clustering/overview)
- [] [PYMK on Facebook]()
- [] [Graph convolutional neural netwoeks]()
- [] [GraphSage paper]()
- [] [Graph attention networks]()
- [] [Graph isomorphism network]()
- [] [Graph neural networks]()
- [] [Personalized random walk]()
- [] [LinkedIn's PYMK system]()
- [] [Addressing delayed feedback]()