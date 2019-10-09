+++
title = "Unified Convolutional Neural Network Approach of Gesture Recognition and Fingertip Detection"

# Date first published.
date = "2019-09-30"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mohammad Mahmudul Alam", "Mohammad Tariqul Islam", "S. M. Mahbubur Rahman"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In Pattern Recognition, Elsevier, Science Publishers [In Progress]"
publication_short = "In Elsevier"

# Abstract and optional shortened version.
abstract = "In human-computer interaction or in sign language interpretation, recognizing hand gestures and detecting fingertips become ubiquitous in computer vision research. In this paper, a unified convolutional neural network (CNN) approach for both hand gesture recognition and fingertip detection are introduced. The proposed algorithm uses a single network to predict finger class probabilities and fingertips positional output in one evaluation. Instead of directly regressing fingertips position from the fully connected layer of the CNN, we regress ensemble of fingertips position from the fully convolutional network (FCN) and subsequently take ensemble average to regress the final fingertips positional output. Since the whole recognition and detection pipeline use a single network, it is extremely fast, runs at 76 frames per second. Compared to state-of-the-art methods, the proposed method makes less localization error and less likely to predict false positive and false negative. It outperforms other fingertip detection approach including Heatmap-based and End2End frameworks."

abstract_short = "A Unified Convolutional Neural Network Approach of Gesture Recognition and Fingertip Detection."

# Featured image thumbnail (optional)
image_preview = "featured.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/MahmudulAlam/Unified-Gesture-and-Fingertip-Detection"
url_dataset = "http://www.hcii-lab.net/data/SCUTEgoGesture/index.htm"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "ac", url = "http://example.org"}]
      


# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""
+++