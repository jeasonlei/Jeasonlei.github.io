

# Shaohai Lei（雷绍海）

Welcome to my personal website!

# About me

I am a final-year PhD candidate from the College of Economics and Management at Nanjing Agricultural University in China. Now, I am also a visiting researcher work at Institute of Food and Reseource Economics (ILR) at The University of Bonn in Germany. 

My research field incldues International Trade, International Finance, Empirical Microeconomics, Development Economics, Chinese Economy. My research interests focus on the Agri-product trade and policy analysis, frim international activity and market power and climate risk and corporate finance.

I will be on the job market in 2025-2026 and available for interviews. You can find my CV and bio in Chinese here. Feel free to contact me if you are interested in my research!


# =========================
# Author Settings
# =========================
author:
  name: "Shaohai Lei"
  avatar: "profile.jpg"
  bio: >
    Visiting PhD Student at the University of Bonn.
    PhD candidate in International Trade at Nanjing Agricultural University.
    Research interests include agricultural trade, import shocks,
    local labor markets, and welfare analysis.
  location: "Bonn, Germany"
  employer: "University of Bonn"
  email: "lsha1@uni-bonn.de"

# =========================
# Academic Profile
# =========================
academic:
  position: "Visiting PhD Student"
  institution: "University of Bonn"
  department: "Agricultural Economics"
  phd_institution: "Nanjing Agricultural University"
  field: "International Trade & Agricultural Economics"

# =========================
# Social Links
# =========================
social:
  github: jeasonlei
  google_scholar: "https://scholar.google.com/citations?user=mmrlrmEAAAAJ&hl=en"
  linkedin: "https://www.linkedin.com/in/jeason-phone-cale-usb-cable-dc-cable-lei-41a739208/?locale=en_US"
  ORCID: "https://orcid.org/0000-0002-0926-6206"

# =========================
# Navigation Bar
# =========================
navigation:
  - title: "About"
    url: /
  - title: "Research"
    url: /research/
  - title: "Publications"
    url: /publications/
  - title: "Working Papers"
    url: /working-papers/
  - title: "CV"
    url: /cv/
  - title: "Contact"
    url: /contact/

# =========================
# Build Settings
# =========================
markdown: kramdown
highlighter: rouge
permalink: /:categories/:title/

plugins:
  - jekyll-feed
  - jekyll-sitemap
  - jekyll-seo-tag

# =========================
# Defaults
# =========================
defaults:
  - scope:
      path: ""
      type: "posts"
    values:
      layout: "single"
      author_profile: true
