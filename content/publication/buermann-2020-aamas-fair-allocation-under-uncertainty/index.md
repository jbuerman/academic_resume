---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fair Allocation of Resources with Uncertain Availability"
authors: [admin, Enrico H. Gerding, Baharak Rastegar]
date: 2020-05-09T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-05-09T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proc. of the 19th International Conference on Autonomous Agents and Multiagent Systems
publication_short: AAMAS 2020

abstract: Multi-agent resource allocation is an important and well-studied problem within AI and economics. It is generally assumed that the quantity of each resource is known a priori. However, in many real-world problems, such as the production of renewable energy which is typically weather dependent, the exact amount of each resource may not be known at the time of decision making. In this paper we investigate fair division of a homogeneous divisible resource where the available amount is given by a probability distribution. Specifically, we study the notion of ex-ante envy-freeness, where, in expectation, agents weakly prefer their allocation over every other agent’s allocation. We analyse the trade-off between fairness and social welfare. We show that allocations satisfying ex-ante envy-freeness can result in higher social welfare compared to those satisfying ex-post envy-freeness. Nevertheless, the price of envy-freeness is at least Ω(n), where n is the number of agents, and this is tight under concave valuation functions. Principally, we show that the problem of optimising ex-ante social welfare subject to ex-ante envy-freeness is NP-hard in the strong sense. Finally, we devise an integer program to calculate the optimal ex-ante envy-free allocation for linear satiable valuation functions.

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ifaamas.org/Proceedings/aamas2020/pdfs/p204.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
