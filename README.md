## Hi there 👋

# <span data-lang="en">👨🏻‍🎓 Biography</span><span data-lang="zh" hidden>👨🏻‍🎓 个人简介</span>

<p data-lang="en">
  I am a Postdoctoral Fellow in
  <a href="https://www.polyu.edu.hk/rclae/">Research Centre for Low Altitude Economy</a>,
  <a href="https://www.polyu.edu.hk/aae/">Department of Aeronautical and Aviation Engineering</a>,
  <a href="https://www.polyu.edu.hk/">The Hong Kong Polytechnic University</a>, working with Prof.
  <a href="https://scholar.google.com/citations?user=UfIb9GkAAAAJ">Wen-Hua Chen</a>.
  My research focuses on <span style="color: red;">autonomous safe landing of rotorcraft UAVs</span> and <span style="color: red;">underactuated mechatronic/robotic systems</span>, with equal emphasis on theory and application. 
  Previously, I received the Ph.D. degree in Artificial Intelligence (with honors) from 
  <a href="https://www.nankai.edu.cn/main.htm">Nankai University</a>, 
  Tianjin, China, in June 2026, under the supervision of Prof. 
  <a href="https://ai.nankai.edu.cn/info/1033/5214.htm">Ning Sun</a> 
  at the <a href="https://url.nankai.edu.cn/">Underactuated Robots Lab</a>. 
  I received the B.Eng. in Automation (with honors) from 
  <a href="https://www.jlu.edu.cn/">Jilin University</a>, 
  Changchun, China, in June 2021.
</p>
<p data-lang="zh" hidden>
  目前，我在<a href="https://www.polyu.edu.hk/rclae/">香港理工大学低空经济研究中心</a>、<a href="https://www.polyu.edu.hk/aae/">航空及民航工程学系</a>担任博士后研究员，合作导师为<a href="https://scholar.google.com/citations?user=UfIb9GkAAAAJ">陈文华教授</a>。我的研究聚焦于<span style="color: red;">旋翼无人机自主安全降落</span>和<span style="color: red;">欠驱动机电/机器人系统</span>，理论与应用并重。此前，我于2026年6月在<a href="https://www.nankai.edu.cn/main.htm">南开大学</a>获得人工智能专业工学博士学位，师从<a href="https://ai.nankai.edu.cn/info/1033/5214.htm">孙宁教授</a>，并在国内领先的<a href="https://url.nankai.edu.cn/">欠驱动机器人实验室</a>开展研究工作。此外，我于2021年6月在<a href="https://www.jlu.edu.cn/">吉林大学</a>获得自动化专业工学学士学位。
</p>

<p data-lang="en">
  I have been awarded the <strong><span style="color: red;">National Natural Science Foundation of China (NSFC)</span> Youth Student Basic Research Project <span style="color: red;">(for Ph.D. students)</span></strong> as <strong>principal investigator</strong>. My research contributions have resulted in <strong>10+ peer-reviewed publications</strong>
  <a href='https://scholar.google.com/citations?user=g91ocA8AAAAJ'>
    <img src="https://img.shields.io/endpoint?logo=Google%20Scholar&amp;url=https://raw.githubusercontent.com/meng-zhai/meng-zhai.github.io/google-scholar-stats/gs_data_shieldsio.json&amp;labelColor=f6f6f6&amp;color=9cf&amp;style=flat&amp;label=citations" alt="Google Scholar citations">
  </a>
  in top journals, including <strong>IEEE Transactions</strong>. These achievements have been recognized with <strong>5 Best Paper/Best Poster awards</strong> at conferences, the Autonomous Robotic Technology Seminar (ARTS) Scholarship Nomination Award (8 candidates worldwide each year), the National Scholarship for Doctoral Students, the BYD Scholarship, and other academic awards/honors. I have also contributed to the research community as a reviewer for IEEE TIE, IEEE  TSMCS, IEEE TCyber, IEEE RAL, IEEE Internet of Things Journal, Nonlinear Dynamics, ISA Transactions, ICRA, ACC, CDC, etc.
</p>
<p data-lang="zh" hidden>
  我作为<strong>项目负责人</strong>主持获批了<strong><span style="color: red;">国家自然科学基金</span>青年学生基础研究项目<span style="color: red;">（博士研究生）</span></strong>。目前，我已在包括 <strong>IEEE Transactions</strong> 在内的高水平期刊发表<strong>同行评审论文10余篇
  <a href='https://scholar.google.com/citations?user=g91ocA8AAAAJ'>
    <img src="https://img.shields.io/endpoint?logo=Google%20Scholar&amp;url=https://raw.githubusercontent.com/meng-zhai/meng-zhai.github.io/google-scholar-stats/gs_data_shieldsio.json&amp;labelColor=f6f6f6&amp;color=9cf&amp;style=flat&amp;label=citations" alt="Google Scholar citations">
  </a>
  </strong>。相关研究成果获得会议<strong>最佳论文奖/最佳张贴论文奖共5项</strong>，并先后获自主机器人技术研讨会奖学金提名奖（全球每年8名候选人）、博士研究生国家奖学金、比亚迪奖学金及其他学术奖励与荣誉。此外，我还担任 IEEE TIE、IEEE TSMCS、IEEE TCyber、IEEE RAL、IEEE Internet of Things Journal、Nonlinear Dynamics、ISA Transactions、ICRA、ACC、CDC 等期刊和会议的审稿人。
</p>

<p data-lang="en">
  I look forward to potential academic discussions and collaborations. Please feel free to contact me at
  <a href="mailto:tangshi2026@gmail.com">tangshi2026@gmail.com</a>.
</p>
<p data-lang="zh" hidden>
  我期待未来的学术交流与合作。随时欢迎通过 <a href="mailto:tangshi2026@gmail.com">tangshi2026@gmail.com</a> 与我联系。
</p>

### 📎 Homepages
- Personal Pages: https://meng-zhai.github.io (updated recently🔥)
- Google Scholar: https://scholar.google.com/citations?user=g91ocA8AAAAJ&hl

### <span data-lang="en">💬 Recent News</span><span data-lang="zh" hidden>💬 最新动态</span>

{% assign news_items = site.data.news | default: [] %}
{% assign news_count = news_items | size %}
{% assign limit = include.limit %}
{% if limit %}
  {% assign limit = limit | plus: 0 %}
  {% if limit > news_count %}
    {% assign limit = news_count %}
  {% elsif limit < 0 %}
    {% assign limit = 0 %}
  {% endif %}
{% else %}
  {% assign limit = news_count %}
{% endif %}

{% if limit > 0 %}
{% for item in news_items limit: limit %}
{% assign item_en = item.en | default: nil %}
{% assign item_zh = item.zh | default: nil %}
{% if item_en or item_zh %}
- {% if item_en %}<span data-lang="en">{{ item_en }}</span>{% endif %}{% if item_zh %}<span data-lang="zh"{% if item_en %} hidden{% endif %}>{{ item_zh }}</span>{% endif %}
{% else %}
- {{ item }}
{% endif %}
{% endfor %}
{: .news-list}
{% else %}
<p data-lang="en">No news items are available right now. Please check back later.</p>
<p data-lang="zh" hidden>暂无消息更新，欢迎稍后再来查看。</p>
{% endif %}

{% if include.show_button and limit < news_count %}
<!-- <p class="news-actions">
  <a class="btn" href="{{ '/news/' | relative_url }}">
    <span data-lang="en">-- Read More News --</span>
    <span data-lang="zh" hidden>-- 查看更多消息 --</span>
  </a>
</p> -->
{% endif %}

### <span data-lang="en">📚 Publications</span><span data-lang="zh" hidden>📚 论文列表</span>


<div class="publication-controls">
  <input
    type="search"
    id="publication-search"
    class="publication-search"
    placeholder="Search publications..."
    aria-label="Search publications"
    data-placeholder-en="Search publications..."
    data-placeholder-zh="搜索成果..."
    data-aria-label-en="Search publications"
    data-aria-label-zh="搜索成果"
  >
  <select id="publication-type-filter" data-label-en="Type" data-label-zh="类型">
    <option value="all">Type</option>
  </select>
  <select id="publication-year-filter" data-label-en="Date" data-label-zh="日期">
    <option value="all">Date</option>
  </select>
  <button
    type="button"
    id="publication-year-sort"
    class="publication-sort"
    aria-label="Sort by newest"
    data-aria-label-en="Sort by newest"
    data-aria-label-zh="按最新排序"
  >
    <svg
      class="publication-sort-icon"
      viewBox="0 0 1025 1024"
      xmlns="http://www.w3.org/2000/svg"
      width="20"
      height="20"
      aria-hidden="true"
      focusable="false"
    >
      <path
        d="M754.012 538a59.832 59.832 0 0 1 40.055 15.402c24.663 22.223 26.722 60.323 4.6 85.097L557.154 908.976a60.125 60.125 0 0 1-4.6 4.621c-24.661 22.223-62.587 20.154-84.709-4.62L226.332 638.498A60.418 60.418 0 0 1 211 598.261C211 564.98 237.857 538 270.987 538h483.025zM557.155 117.024L798.668 387.5A60.418 60.418 0 0 1 814 427.739C814 461.02 787.143 488 754.013 488H270.988a59.832 59.832 0 0 1-40.055-15.402c-24.663-22.223-26.722-60.323-4.6-85.097l241.513-270.477a60.125 60.125 0 0 1 4.6-4.621c24.661-22.223 62.587-20.154 84.709 4.62z"
        fill="currentColor"
      />
    </svg>
  </button>
</div>

<ol id="publication-list" class="publication-list"></ol>

{% assign publications = site.data.publications %}
<ul id="publication-source" class="publication-source" hidden>
  {% for pub in publications %}
  <li
    data-type="{{ pub.type }}"
    data-year="{{ pub.year }}"
    {% if pub.date %}data-date="{{ pub.date }}"{% endif %}
    {% if pub.citation_plain %}data-citation-plain="{{ pub.citation_plain | escape_once }}"{% endif %}
    {% if pub.citation_bibtex %}data-citation-bibtex="{{ pub.citation_bibtex | replace: '\n', '&#10;' | escape_once }}"{% endif %}
  >
    {{ pub.body_html | strip }}
    {% if pub.scholar_id %}
    <strong><span class="show_paper_citations" data="{{ pub.scholar_id }}"></span></strong>
    {% endif %}
  </li>
  {% endfor %}
</ul>




{% comment %}
{% include citation-modal.html %}
{% endcomment %}