# Sign-lanuage-datasets
These datasets are used for machine-learning research

- Co: Country
- Class: Classes
- Subj: Subjects
- LL: Language level(W-Word,S-Sentence,H-Handshape)
- Type: Type(V-Video, VR-Video(RGB), VD-Video(depth))
- An: Annotations
- Av: Availability(CA-Contact Author, PA-Publicly Available, Un-Unknown, Non-Non available)
- T: There is in our hard drive?(Y-Yes, N-No)

|id| Dataset name         |Co |Class|Subj |Samples   |Data  | LL  |Type     |An     |Av    |T|
|--|----------------------|---|-----|-----|----------|------|-----|---------|-------|------|-|
|1 | DGS Kinect 40        |Ger|40   |15   |3000      |      |W    |V,[9]    |       |PA    |Y|
|2 | RWTH-PHOENIX-Weather |Ger|1200 |9    |45760     |52gb  |S    |V        |[18]   |PA    |Y|
|3 | SIGNUM               |Ger|450  |25   |33210     |920gb |S    |V        |       |PA,[5]|N|
|4 | GSL 20               |Gre|20   |6    |~840      |      |W    |         |       |CA    |Y|
|5 | Boston ASL LVD       |USA|3300+|6    | 9800     |      |W    |V,[9]    |[19,20]|PA    |N|
|6 | PSL Kinect 30        |Pol|30   |1    |30×10=300 |~1.2gb|W    |V,[10]   |       |PA    |Y|
|7 | PSL ToF 84           |Pol|84   |1    |84×20=1680|~33gb |W    |V,[11]   |       |PA    |N|
|8 | PSL 101              |Pol|?    |?    | ?        |?     |?    |?        |       |CA    |N|
|9 | LSA64                |Arg|64   |10   | 3200     |20gb  |W    |VR       |[21]   |PA    |Y|
|10| BosphorusSign        |Tur|     |     |          |      |     |         |       |Non   |N|
|11| MSR Gesture 3D       |USA|12   |10   | 336      |28mb  |W    |VD       |       |PA    |N|
|12| DEVISIGN-G           |Chi|36[1]|8    | 432      | ?    |W    |VR       |       |CA    |N|
|13| DEVISIGN-D           |Chi|500  |8    | 6000     | ?    |W    |VR       |       |CA    |N|
|14| DEVISIGN-L           |Chi|2000 |8    | 24000    | ?    |W    |VR       |       |CA    |N|
|15| IIITA -ROBITA        |Ind|23   |?    |          | 284mb|W    |VR,[15]  |       |CA    |N|
|16| Purdue ASL           |USA|?    |14[3]| ?        | ?    |W/S  |V,[14]   |       |[6]   |N|
|17| CUNY ASL             |USA|?    |8    |~33000[4] | ?    |S    |VR,[16]  |[7]    |U     |N|
|18| SignsWorld Atlas     |Ara|[2]  |10   | ?        | ?    |W,S,H|V,[17,14]|?      |U     |N|


[1] - letters/numbers;
[2] - multiple types;
[3] - only 5 available;
[4] - glosses;
[5] - 1TB, contact author to obtain hard drive;
[6] - Request DVDs/HD;
[7] - Signstream;
[8] - 
[9] - multiple angles;
[10]- depth from Kinect camera;
[11]- ToF camera;
[12]- 
[13]- ;
[14]- RGB;
[15]- 320x240;
[16]- mocap data;
[17]- Images;
[18]- Face, hand, end/start(unfinished);
[19]- Hand;
[20]- end/start;
[21]- Hands and Head position;
[22]- only ASL fingerspelling sequences

**Dataset information and related papers**

1.  [DGS Kinect 40 - German Sign Language](https://www.cvssp.org/data/KinectSign/webpages/downloads.html)

    1.  [Sign Language Recognition using Sub-Units](http://jmlr.csail.mit.edu/papers/volume13/cooper12a/cooper12a.pdf), 2012, Cooper et al.

    2.  [Sign Language Recognition using Sequential Pattern Trees](https://pdfs.semanticscholar.org/e8a1/84e76d6476ecc27857b1c1b280af5628d0ae.pdf) 2012, Ong et al.

    3.  [Sign Spotting using Hierarchical Sequential Patterns with Temporal Intervals](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Ong_Sign_Spotting_using_2014_CVPR_paper.pdf) 2014, Ong et al.

2.  [RWTH-PHOENIX v1 - German Sign Language](http://www-i6.informatik.rwth-aachen.de/~forster/database-rwth-phoenix.php) [RWTH-PHOENIX v2](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX/)

    1.  [Dataset paper](http://www-i6.informatik.rwth-aachen.de/publications/download/773/forster-lrec-2012.pdf) 2012, Forster et al.

    2.  [Dataset extensions paper](http://www.lrec-conf.org/proceedings/lrec2014/pdf/585_Paper.pdf) 2014, Forster et al

    3.  [Continuous sign language recognition: Towards large vocabulary statistical recognition systems handling multiple signers](http://www.sciencedirect.com/science/article/pii/S1077314215002088) 2015, Koller et al. 4.[May the force be with you: Force-aligned signwriting for automatic subunit annotation of corpora](http://www-i6.informatik.rwth-aachen.de/publications/download/852/Koller-FG-2013.pdf) 2013, Koller et al.

    4.  [Deep Sign: Hybrid CNN-HMM for Continuous Sign Language Recognition](http://epubs.surrey.ac.uk/812319/)

3.  [SIGNUM - German Sign Language](http://www.phonetik.uni-muenchen.de/forschung/Bas/SIGNUM/)

    1.  [Continuous sign language recognition: Towards large vocabulary statistical recognition systems handling multiple signers](http://www.sciencedirect.com/science/article/pii/S1077314215002088) 2015, Koller et al.

4.  Greek Sign Language (no website)

    1.  [Sign Language Recognition using Sub-Units](http://jmlr.csail.mit.edu/papers/volume13/cooper12a/cooper12a.pdf), 2012, Cooper et al.

    2.  [Sign Language Recognition using Sequential Pattern Trees](https://pdfs.semanticscholar.org/e8a1/84e76d6476ecc27857b1c1b280af5628d0ae.pdf) 2012, Ong et al.

    3.  [Sign Spotting using Hierarchical Sequential Patterns with Temporal Intervals](http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Ong_Sign_Spotting_using_2014_CVPR_paper.pdf) 2014, Ong et al.

5.  [Boston ASLLVD - American Sign Language](http://www.bu.edu/av/asllrp/dai-asllvd.html)

    1.  [Exploiting Phonological Constraints for Handshape Inference in ASL Video](http://www.bu.edu/asllrp/1826-CVPR_2011.pdf) 2011, Thangali et al.

    2.  [A New Framework for Sign Language Recognition based on 3D Handshape Identification and Linguistic Modeling](http://www.lrec-conf.org/proceedings/lrec2014/pdf/1138_Paper.pdf) 2014 - Dilsizian - 84% accuracy

6.  [PSL Kinect 30 - Polish Sign Language](http://vision.kia.prz.edu.pl/dynamickinect.php)

    1.  [Polish sign language words recognition with Kinect ](http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=6577826&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D6577826)2013, Oszust et al.

    2.  [Some Approaches to Recognition of Sign Language Dynamic Expressions with Kinect ](http://link.springer.com/chapter/10.1007%2F978-3-319-08491-6_7)2014, Oszust et al.

    3.  [Recognition of Hand Gestures Observed by Depth Cameras](http://cdn.intechopen.com/pdfs-wm/48352.pdf) 2015, Kapuscinski
        et al.

7.  [PSL ToF 84 - Polish Sign Language](http://vision.kia.prz.edu.pl/dynamictof.php)

    1.  [Polish sign language words recognition with Kinect](http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=6577826&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D6577826) 2013,
        Oszust et al.

    2.  [Recognition of Hand Gestures Observed by Depth Cameras](http://cdn.intechopen.com/pdfs-wm/48352.pdf) 2015, Kapuscinski
        et al.

8.  PSL 101 - Polish Sign Language (no website)

    1.  [Modelling and Recognition of Signed Expressions Using Subunits Obtained by Data–Driven Approach](http://link.springer.com/chapter/10.1007%2F978-3-642-33185-5_35#page-2) 2012, Oszust et al.

9.  [LSA64 Argentinian Sign
    Language](http://facundoq.github.io/unlp/lsa64/index.html)

    1.  [LSA64: an Argentinian Sign Language Dataset](http://sedici.unlp.edu.ar/handle/10915/56764)

    2.  [Sign Languague Recognition Without Frame-Sequencing Constraints: A Proof of Concept on the Argentinian Sign Language](https://link.springer.com/chapter/10.1007/978-3-319-47955-2_28)

    3.  [Dynamic Gesture Recognition and its Application to Sign Language](http://sedici.unlp.edu.ar/handle/10915/62945) 2017, Ronchetti

    4.  [SIGN LANGUAGE RECOGNITION BASED ON HAND AND BODY SKELETAL DATA](https://www.researchgate.net/profile/Kosmas_Dimitropoulos/publication/325011717_Sign_Language_Recognition_based_on_Hand_and_Body_Skeletal_Data/links/5af160e3a6fdcc24364b1024/Sign-Language-Recognition-based-on-Hand-and-Body-Skeletal-Data.pdf) 2017,Konstantinidis et al.

    5.  [Real-Time Sign Language Gesture (Word) Recognition from Video Sequences Using CNN and RNN](https://link.springer.com/chapter/10.1007/978-981-10-7566-7_63) 2018, Masood et al.

10. [Turkish sign language dataset](https://www.cmpe.boun.edu.tr/pilab/BosphorusSign/home_en.html)

11. [MSR Gesture 3D - ASL](https://www.microsoft.com/en-us/research/people/zliu/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fum%2Fpeople%2Fzliu%2Factionrecorsrc%2F)[Download site](https://www.uow.edu.au/~wanqing/#Datasets)

    1.  [Action Recognition from Depth Sequences Using Weighted Fusion of 2D and 3D Auto-Correlation of Gradients Features](https://link.springer.com/article/10.1007/s11042-016-3284-7) 2016, Chen et al

12. [DEVISIGN G](http://vipl.ict.ac.cn/homepage/ksl/data.html#page3)

13. [DEVISIGN D](http://vipl.ict.ac.cn/homepage/ksl/data.html#page3)

14. [DEVISIGN L](http://vipl.ict.ac.cn/homepage/ksl/data.html#page3)

15. [IIITA -ROBITA Indian Sign Language Gesture Database ](<https://robita.iiita.ac.in/dataset.php>)

    1.  [Recognizing & Interpreting Indian Sign Language Gesture for Human Robot Interaction](https://ieeexplore.ieee.org/document/5640434/) 2010, Nandy et al.

    2.  [Recognition of Isolated Indian Sign Language gesture in Real Time ](https://pdfs.semanticscholar.org/fa4d/a909eeebc9a923e29502e3eb2dd6c40ca083.pdf)2010, Nandy et al.

16. [Purdue ASL Dataset](http://www2.ece.ohio-state.edu/~aleix/ASLdatabase.htm)

17. [CUNY ASL Dataset for Animation](https://facundoq.github.io/unlp/sign_language_datasets/latlab.cs.qc.cuny.edu/corpus)

    1.  [Collecting and evaluating the CUNY ASL corpus for research on American Sign Language animation](https://www.sciencedirect.com/science/article/pii/S0885230813000879)

18. [SignsWorld Atlas; a benchmark Arabic Sign Language database](https://www.sciencedirect.com/science/article/pii/S1319157814000548)

**Datasets Handshape features (Handshape/hand posture datasets) but not all are for sign language**

|id|Name                           |Co |Clas|Sub|Samples| Data | Type              | Availability |
|--|-------------------------------|---|----|---|-------|------|-------------------|--------------|
| 1|ASL Fingerspelling A           |USA| 24 | 5 | 131000| 2.1gb|images (depth+rgb) | Free download|
| 2|ASL Fingerspelling B           |USA| 24 | 9 |       | 317mb|images (depth)     | Free download|
| 3|LSA16 handshapes               |Arg| 16 |10 | 800   |   7mb|images (rgb)       | Free download|
| 4|PSL Fingerspelling ToF         |Pol| 16 | 3 | 960   |~290mb|3D point cloud     | Free download|
| 5|ISL                            |Iri|[23]| 6 | [24]  | 170mb|segmented images   | Free download|
| 6|RWTH-PHOENIX-Weather Handshapes|Ger| 60 |   | [25]  |+ 17gb|Hand Images (rgb)  | Free download|
| 7|Japanese Fingerspelling Dataset|Jap| 41 |10 | 8055  | 4.5mb|[26]               | Free download|
| 8|NUS hand posture dataset I     |Sin| 10 | ? | 240   |   3mb|images(rgb),160x120| Free download|
| 9|NUS hand posture dataset II    |Sin| 10 |40 | 2000  |  73mb|images(rgb)160x120 | Free download|
|10|CIARP                          |\- | 10 | ? | 6000  |  11mb|images(rgb)38x38   | Free download|
|11|RTWH Fingerspelling dataset    |Ger|    |   |       |      |                   |              |
|12|Indian Kinect                  |Ind| 40 |18 | 5041  |   2gb|[27]               | Free download|
|13|[ArASL]                        |Ara| 32 | ? | 54,049|  64mb|images(rgb)        | Free download|
|14|ChicagoFSWild                  |USA|[2] |160| ?     |      | images(rgb)       | Free download|     
|15|ChicagoFSWild+                 |USA|    |   |       |      |                   |              |

[ArASL] - Arabic Alphabets Sign Language Dataset;
[2] - multiple types;
[23]- 23 static + 3 dynamic;
[24]- 58114 frames/468 videos; 
[25]- 3359 labelled + 17gb unlabeled
[26]- segmented images (rgb), 32x32
[27]- images (rgb+depth) 640x480

**Dataset information and related papers**

1.  [ASL Fingerspelling](http://empslocal.ex.ac.uk/people/staff/np331/index.php?section=FingerSpellingDataset)

    1.  [Spelling It Out: Real-Time ASL Fingerspelling Recognition](http://personal.ee.surrey.ac.uk/Personal/N.Pugeault/publications/PugeaultBowden2011b.pdf). 2011, Pugeault et al.

    2.  [Recognition of Hand Gestures Observed by Depth Cameras](http://cdn.intechopen.com/pdfs-wm/48352.pdf). 2015, Kapuscinski et al.

2.  [PSL Fingerspelling ToF](http://vision.kia.prz.edu.pl/statictof.php)

    1.  [Recognition of Hand Gestures Observed by Depth Cameras](http://cdn.intechopen.com/pdfs-wm/48352.pdf). 2015, Kapuscinski et al.

3.  [LSA16 handshapes](http://facundoq.github.io/unlp/lsa16/index.html)

    1.  [Handshape recognition for Argentinian Sign Language using ProbSom](http://journal.info.unlp.edu.ar/wp-content/uploads/2015/10/JCST-42-Paper-1.pdf). 2016, Ronchetti et al.

    2.  [A Study of Convolutional Architectures for Handshape Recognition applied to Sign Language](http://sedici.unlp.edu.ar/handle/10915/63481) 2017, Quiroga et al.

4.  [ISL Irish Sign Language Letters](https://github.com/marlondcu/ISL).

    1.  [A Dataset for Irish Sign Language Recognition](http://doras.dcu.ie/21882/1/IMVIP_short_cr.pdf) 2017, Oliveira et al.

    2.  [A comparison between end-to-end approaches and feature extraction based approaches for Sign Language recognition](http://doras.dcu.ie/22132/1/Houssem_-_IVCNZ_2017.pdf) 2017, Oliveira et al.

5.  [RWTH-PHOENIX-Weather 2014 MS Handshapes](https://www-i6.informatik.rwth-aachen.de/~koller/1miohands-data/)

    1.  [Deep Hand: How to Train a CNN on 1 Million Hand Images When Your Data Is Continuous and Weakly Labelled ](https://www-i6.informatik.rwth-aachen.de/publications/download/1000/Koller-CVPR-2016.pdf) 2017, Koller et al.

6.  [Japanese Sign Language Dataset](http://home.agh.edu.pl/~bkw/research/data/mva/jsl.zip)

    1.  [Recognition of JSL Finger Spelling Using Convolutional Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7986796) 2017, Hosoe, Sako and Kwolek

    2.  [Learning Siamese Features for Finger Spelling Recognition](https://link.springer.com/chapter/10.1007/978-3-319-70353-4_20) 2017, Sako and Kwolek

7.  [NUS hand posture dataset I](https://www.ece.nus.edu.sg/stfpage/elepv/NUS-HandSet/)

    1.  [Hand posture and face recognition using a Fuzzy-Rough Approach](http://vadakkepat.com/web/images/stories/pubs/ijhr-2010.pdf) 2010, Pramod Kumar P, Prahlad Vadakkepat, and Loh Ai Poh

    2.  [Hand Posture Recognition Using Convolutional Neural Network](https://www.researchgate.net/publication/322915265_Hand_Posture_Recognition_Using_Convolutional_Neural_Network)

8.  [NUS hand posture dataset II](https://www.ece.nus.edu.sg/stfpage/elepv/NUS-HandSet/)
    1.  [Attention Based Detection and Recognition of Hand Postures Against Complex Backgrounds](http://link.springer.com/article/10.1007%2Fs11263-012-0560-5?LI=true) 2013, Pisharady et al

9.  [CIARP 2017](http://home.agh.edu.pl/~bkw/code/ciarp2017/)

    1.  [Hand Posture Recognition Using Convolutional Neural Network](https://link.springer.com/chapter/10.1007/978-3-319-75193-1_53)

10. [RTWH Fingerspelling dataset](http://www-i6.informatik.rwth-aachen.de/aslr/fingerspelling.php)

11. [Modeling Image Variability in Appearance-Based Gesture Recognition. In ECCV Workshop on Statistical Methods in Multi-Image and Video Processing](https://www-i6.informatik.rwth-aachen.de/publications/download/29/Dreuw-ECCV-SMVP-2006.pdf)

12. [Indian Kinect](https://www.ias.ac.in/article/fulltext/sadh/041/02/0161-0182) [github](https://github.com/zafar142007/Gesture-Recognition-for-Indian-Sign-Language-using-Kinect)

13. [Nearest neighbour classification of Indian sign language gestures using kinect camera](https://www.ias.ac.in/article/fulltext/sadh/041/02/0161-0182) 2016, Ansari and Harit

14. [Arabic Alphabets Sign Language Dataset (ArASL)](https://data.mendeley.com/datasets/y7pckrw6z2/1)

15. [Arabic Alphabet and Numbers Sign Language Recognition](https://www.researchgate.net/publication/285755274_Arabic_Alphabet_and_Numbers_Sign_Language_Recognition)

16. [ChicagoFSWild](https://ttic.uchicago.edu/~klivescu/ChicagoFSWild.htm#download)
    1.  [American Sign Language fingerspelling recognition in the wild](https://arxiv.org/pdf/1810.11438.pdf)
    2.  [Fingerspelling recognition in the wild with iterative visual attention](https://arxiv.org/pdf/1908.10546.pdf)
17. [ChicagoFSWild+](https://ttic.uchicago.edu/~klivescu/ChicagoFSWild.htm#download)
    1.  [Fingerspelling recognition in the wild with iterative visual attention](https://arxiv.org/pdf/1908.10546.pdf)

**Continuous hand pose**

1.  [NYU Hand pose dataset](https://cims.nyu.edu/~tompson/NYU_Hand_Pose_Dataset.htm)

    1.  [Real-Time Continuous Pose Recovery of Human Hands Using Convolutional Networks](https://cims.nyu.edu/~tompson/others/TOG_2014_paper_PREPRINT.pdf)


**Datasets of facial features **

1.  QLIBRAS

    1.  [QLIBRAS: A novel database for grammatical facial expressions in Brazilian Sign Language](https://pdfs.semanticscholar.org/919a/1e2bea81a7dc52dfa20fe530cf75a8f307da.pdf)

**Datasets of lip reading features**

1.   [GRID corpus - Lip](http://spandh.dcs.shef.ac.uk/gridcorpus/)
     1.   [LipNet: End-to-End Sentence-level Lipreading](https://arxiv.org/pdf/1611.01599.pdf)
     2.   [Dynamic Stream Weighting for Turbo-Decoding-Based Audiovisual ASR](https://pdfs.semanticscholar.org/3087/e40e076b2a7bbb1e7a6efb7779a941283853.pdf)
2.   [AVICAR - Lip](http://www.isle.illinois.edu/sst/AVICAR/)
     1. [Classification and Feature Extraction by Simplexization](https://ieeexplore.ieee.org/document/4451093)
3.   [AVLetter](http://www.ee.surrey.ac.uk/Projects/LILiR/datasets/avletters1/index.html)
     1. [Temporal Multimodal Learning in Audiovisual Speech Recognition](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Hu_Temporal_Multimodal_Learning_CVPR_2016_paper.pdf)
4.   [CUAVE](http://people.csail.mit.edu/siracusa/avdata/)
     1. [CUAVE: A new audio-visual database for multimodal human-computer interface research](https://www.researchgate.net/publication/228722705_CUAVE_A_new_audio-visual_database_for_multimodal_human-computer_interface_research)
5.   OuluVS1 (no website)
     1. [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf)
6.   [OuluVS2](http://www.ee.oulu.fi/research/imag/OuluVS2/)
     1. [Out of time: automated lip sync in the wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16a/chung16a.pdf)
7.   [BBC TV](http://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)
     1. [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf)

The table from the paper - [LipNet: End-to-End Sentence-level Lipreading](https://arxiv.org/pdf/1611.01599.pdf)

| **Method** | **Dataset** | **Size** | **Output** | **Accuracy** |
|----------------|-----------------|------------|--------------- |------------------ |
| Fu et al. (2008)      | AVICAR | 851 | Digits | 37.9% |
| Hu et al. (2016) | AVLetter | 78 | Alphabet | 64.6%|
| Papandreou et al. (2009) | CUAVE | 1800 | Digits | 83.0%|
| Chung & Zisserman (2016a) |OuluVS1 | 200 | Phrases | 91.4% |
| Chung & Zisserman (2016b) | OuluVS2 | 520 | Phrases | 94.1% |
| Chung & Zisserman (2016a) | BBC TV | > 400000 | Words | 65.4% |
| Gergen et al. (2016) | GRID | 29700 | Words | 86.4% |
| LipNet | GRID | 28775 | Sentences | 95.2% |
**Other info**

Kevin Murphy mantains a similar list for [Action Recognition Datasets](http://www.cs.ubc.ca/~murphyk/videodata.html).

Other similar websites with sign language dataset compilations are:

-   [Chalearn dataset list](http://ww1.chalearn.org/resou/databases)

-   [RWTH datasets list](https://www-i6.informatik.rwth-aachen.de/web/Software/Databases/Signlanguage/?db=rwth-boston-104)

Papers that cite datasets that are unavailable:

-   480 signs, Indian Sign Language

    -   [Segment, Track, Extract, Recognize and Convert Sign Language Videos to Voice/Text](https://pdfs.semanticscholar.org/37f8/0b0bf92dae99fc66fea90973e3b3e1b42e86.pdf) 2012, Kishore and Kumar

    -   [Selfie video based continuous Indian sign language recognition system](https://www.sciencedirect.com/science/article/pii/S2090447917300217) 2017, Rao and Kishore

-   10 signs, indian sign language

    -   [Recognizing & interpreting Indian Sign Language gesture for Human Robot Interaction](https://ieeexplore.ieee.org/document/5640434/?part=1) 2010, Nandy et al.

-   24 static handshapes, Indian Sign Language

    -   [Recognition of Indian Sign Language in Live Video](https://arxiv.org/pdf/1306.1301.pdf) 2013, Singha and Das Hand movement datasets (movement only):

1.  [LIBRAS hand movement](https://archive.ics.uci.edu/ml/datasets/Libras+Movement)

    1.  [Hand Movement Recognition for Brazilian Sign Language: A Study Using Distance-Based Neural Networks.](https://ieeexplore.ieee.org/document/5178917/)

**References**
https://facundoq.github.io/unlp/sign_language_datasets/index.html
