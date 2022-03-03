# Habitat - Matterport 3D Research Dataset

Matterport and Facebook AI Research are collaborating to release the world's largest dataset of 3D spaces. This is available exclusively for academic, non-commercial uses. The Habitat-Matterport 3D Research Dataset (HM3D) is an unprecedented collection of high-resolution Matterport digital twins made up of residential, commercial, and civic spaces.

The dataset consists of 3D Meshes & Textures of 1,000 Matterport spaces and includes:
-   3D mesh file (OBJ & GLB)
-   JPG texture map image files
-   MTL file

🆕 **HM3D-Semantics:** We release semantic annotations for a subset of the scenes from HM3D. In the current version (v0.1), a subset of 100 annotated scenes (80 train | 20 val) is available for use with the Habitat simulator! We also release annotations for the example scene `00861-GLAQ4DNUx5U`. See `hm3d-(train|val|example)-semantic-annots-v0.1.tar.gz` in the table below. <br>
**Note:** Semantic annotations for these scenes are work-in-progress, check back later for additional updates.

Here’s a preview of selected spaces that are part of this library,

<p align="middle">
  <img src="./images/left.png" width="400" />
  <img src="./images/right.png" width="400" /> 
</p>

Access and use of the dataset are subject to the following [Terms & Conditions](https://matterport.com/matterport-end-user-license-agreement-academic-use-model-data)

|File Name|Data Set|Format|Link|Size|
|--|--|--|--|--|
|hm3d-minival-glb.tar|minival|glb|https://api.matterport.com/resources/habitat/hm3d-minival-glb.tar |465M|
|hm3d-minival-habitat.tar|minival|habitat| https://api.matterport.com/resources/habitat/hm3d-minival-habitat.tar |393M|
|hm3d-minival-obj+mtl.tar.gz|minival|obj+mtl| https://api.matterport.com/resources/habitat/hm3d-minival-obj+mtl.tar.gz|444M|
|hm3d-train-glb.tar|train|glb| https://api.matterport.com/resources/habitat/hm3d-train-glb.tar|32G|
|hm3d-train-habitat.tar|train|habitat|https://api.matterport.com/resources/habitat/hm3d-train-habitat.tar |26G|
|hm3d-train-obj+mtl.tar.gz|train|obj+mtl| https://api.matterport.com/resources/habitat/hm3d-train-obj+mtl.tar.gz|30G|
|hm3d-val-glb.tar|val|glb| https://api.matterport.com/resources/habitat/hm3d-val-glb.tar|4G|
|hm3d-val-habitat.tar|val|habitat| https://api.matterport.com/resources/habitat/hm3d-val-habitat.tar|3.3G|
|hm3d-val-obj+mtl.tar.gz|val|obj+mtl| https://api.matterport.com/resources/habitat/hm3d-val-obj+mtl.tar.gz|3.8G|
|hm3d-example-configs.tar|example|configs|[hm3d-example-configs.tar](example/hm3d-example-configs.tar)|10K|
|hm3d-example-glb.tar**|example|glb|[hm3d-example-glb.tar](example/hm3d-example-glb.tar)|186M|
|hm3d-example-habitat.tar**|example|habitat|[hm3d-example-habitat.tar](example/hm3d-example-habitat.tar)|155M|
|hm3d-example-obj+mtl.tar.gz|example|obj+mtl|[hm3d-example-obj+mtl.tar.gz](example/hm3d-example-obj+mtl.tar.gz)|179M|
|🆕 hm3d-train-semantic-annots-v0.1.tar.gz|train|habitat|https://api.matterport.com/resources/habitat/hm3d-train-semantic-annots-v0.1.tar.gz|1.9G|
|🆕 hm3d-val-semantic-annots-v0.1.tar.gz|val|habitat|https://api.matterport.com/resources/habitat/hm3d-val-semantic-annots-v0.1.tar.gz|433M|
|🆕 hm3d-example-semantic-annots-v0.1.tar.gz|example|habitat|https://api.matterport.com/resources/habitat/hm3d-example-semantic-annots-v0.1.tar.gz|26M|

