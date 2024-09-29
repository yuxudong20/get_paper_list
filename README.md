get_paper.ipynb: 搜集icra, iros论文的title, authors, year, keywords, abstract, url, 需要提前准备好txt文件，可以从IEEE官网导出.

get_corl.ipynb: 搜集corl 2022和corl 2023论文的title, authors, abstract, url等信息，需要从corl2022.org或者corl2023.org导出yaml文件.

get_openreview.ipynb: 搜集corl 2024和其他顶会的论文信息（更推荐papers.cool）,用的是openreview官方提供的api.

导出结果：可以导出html，也可以导出csv（见get_paper.ipynb）。个人偏好html, 这样abstract能显示全。