#  2026 Korea University Methods Workshop: Text-as-Data/NLP

## Time and location

- Time: 1--3:00pm (Lecture 1) & 3:30--5:30pm (Lecture 2), January 22
- Location: 145, Anam-ro, Seongbuk-gu, Seoul, Korea (고려대학교 상남정경관 113호)


## Instructor
- **Name:** Taegyoon Kim, Ph.D. in Political Science and Social Data Analytics
- **Email:** [taegyoon@kaist.ac.kr](mailto:taegyoon@kaist.ac.kr)
- **Webpage:** [https://taegyoon-kim.github.io](https://taegyoon-kim.github.io)


## Overview

This workshop introduces political science students to a key subset of essential concepts and techniques in text-as-data and NLP.  
- The workshop will blend theoretical understanding with practical, hands-on experience.
- The workshop consists of two lectures (2 hours each). 
- The first lecture will focus on pre-processing and representing texts, covering text normalization, vector semantics models, static and contextual word embeddings, and similarity measures.
- The second lecture will focus on supervised machine learning an generative models (LLM) for text classification.

**Note that the workshop is intended as a broad introduction to text-as-data and NLP for social science research. For a more comprehensive, semester-length course, please refer to [NLP for Humanities and Social Sciences](https://github.com/taegyoon-kim/nlp_25spring).**


## Tutorials

The workshop will invovle guided coding (or tutorials) using Python and Google Colab. Little prior experience in the language is assumed. Note that students are expected to **bring their own computing device**.


## Referenced books and articles

### Textbooks
- **[GRS]** Grimmer, J., Roberts, M.E., & Stewart, B.M. (2022). *Text as Data: A New Framework for Machine Learning and the Social Sciences*. [Link](https://product.kyobobook.co.kr/detail/S000002751294)

- **[JM]** Jurafsky, D. & Martin, J.H. *Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition*. [Link](https://web.stanford.edu/~jurafsky/slp3/)

- **[AG]** Alammar, J. & Grootendorst, M. (2024). *Hands-On Large Language Models: Language Understanding and Generation*. [Link](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961)


### Lecutre 1
- Selecting texts for research
  - [GRS] Sections 3.1 and 3.2 in Chp. 3 "Principles of Selection and Representation."
  - [GRS] Chp. 4 "Selecting Documents."
- Clening and representing texts
  - [GRS] Chp. 5 "Bag of Words."
  - [GRS] Chp. 7 "The Vector Space Model and Similarity Metrics."
  - [JM] Sections 2.1 and 2.2 in Chp. 2 "Regular Expressions, Text Normalization, Edit Distance"
  - [JM] Chp. 6 ``Vector Semantics and Embeddings" 
  - Denny, M.J. and Spirling, A., 2018. Text preprocessing for unsupervised learning: Why it matters, when it misleads, and what to do about it. Political Analysis, 26(2), pp.168-189.
- Static word embeddings 
  - [GRS] Chp. 8 "Distributed Representations of Words"
  - Osnabrügge, M., Hobolt, S.B. and Rodon, T., 2021. Playing to the gallery: Emotive rhetoric in parliaments. American Political Science Review, 115(3), pp.885-899.
  - Kozlowski, A.C., Taddy, M. and Evans, J.A., 2019. The geometry of culture: Analyzing the meanings of class through word embeddings. American Sociological Review, 84(5), pp.905-949.
  - Garten, J., Hoover, J., Johnson, K.M., Boghrati, R., Iskiwitch, C. and Dehghani, M., 2018. Dictionaries and distributions: Combining expert knowledge and large scale textual data content analysis: Distributed dictionary representation. Behavior research methods, 50, pp.344-361.
- Contextual word embeddings 
  - Smith, N.A., 2019. Contextual word representations: A contextual introduction. arXiv preprint arXiv:1902.06006.
  - [JM] Sections 7.1-7.4 and 7.6 in Chp. 7 "Neural Networks and Neural Language Models"
  - [JM] Chp. 10 ``Transformers and Pretrained Language Models"
  - [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
  - [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
  - [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning](https://jalammar.github.io/illustrated-bert/)
  
### Lecutre 2
- Classic supervised classification
  - [GRS] Chp. 17 "An Overview of Supervised Classification"
  - [GRS] Chp. 18 "Coding a Training Set"
  - [GRS] Chp. 19 "Classifying Documents with Supervised Learning"
  - [GRS] Chp. 20 "Checking Performance"
  - Siegel, A.A., Nikitin, E., Barberá, P., Sterling, J., Pullen, B., Bonneau, R., Nagler, J. and Tucker, J.A., 2021. Trumping hate on Twitter? Online hate speech in the 2016 US election campaign and its aftermath. Quarterly Journal of Political Science, 16(1), pp.71-104.
  - Barberá, P., Boydstun, A.E., Linn, S., McMahon, R. and Nagler, J., 2021. Automated text classification of news articles: A practical guide. Political Analysis, 29(1), pp.19-42.
  - Bestvater, S.E. and Monroe, B.L., 2023. Sentiment is not stance: Target-aware opinion classification for political text analysis. Political Analysis, 31(2), pp.235-256.
- Fine-tuning representation models for classification
  - [JM] Chp. 11 "Masked Language Models"
  - [AG] Chp. 11 "Fine-tuning Representation Models for Classification" 
  - Card, D., Chang, S., Becker, C., Mendelsohn, J., Voigt, R., Boustan, L., Abramitzky, R. and Jurafsky, D., 2022. Computational analysis of 140 years of US political speeches reveals more positive but increasingly polarized framing of immigration. Proceedings of the National Academy of Sciences, 119(31), p.e2120510119.
  - Laurer, M., Van Atteveldt, W., Casas, A. and Welbers, K., 2024. Widmann, T. and Wich, M., 2023. Creating and comparing dictionary, word embedding, and transformer-based models to measure discrete emotions in German political text. Political Analysis, 31(4), pp.626-641.
- Using generative models for classification
  - [AG] Chp. 1 "An Introduction to Large Language Models"
  - [AG] Chp. 3 "Looking Inside Large Language Models"
  - [AG] Chp. 6 "Prompt Engineering"
  - [AG] Chp. 12 "Fine-tuning Generation Models"
  - Törnberg, P. (2024). Best practices for text annotation with large language models. arXiv preprint arXiv:2402.05129.
  - Wei, J., Wang, X., Schuurmans, D., Bosma, M., Xia, F., Chi, E., ... & Zhou, D. (2022). Chain-of-thought prompting elicits reasoning in large language models. Advances in neural information processing systems, 35, 24824-24837.

