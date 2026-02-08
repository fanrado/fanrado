## Hi there 👋

## 📊 Real-Time GitHub Activity

### GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=fanrado&show_icons=true&theme=radical&count_private=true&include_all_commits=true)

### GitHub Streak
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=fanrado&theme=radical)

### Top Languages
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=fanrado&layout=compact&theme=radical&langs_count=8)

### Activity Graph
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=fanrado&theme=redical&hide_border=true)

### Recent Activity
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

> **Note:** To enable the Recent Activity section, you need to set up a GitHub Action workflow. Create `.github/workflows/update-activity.yml`:
> 
> ```yaml
> name: Update README with recent activity
> 
> on:
>   schedule:
>     - cron: '*/30 * * * *'  # Runs every 30 minutes
>   workflow_dispatch:
> 
> jobs:
>   build:
>     runs-on: ubuntu-latest
>     name: Update Profile README
> 
>     steps:
>       - uses: actions/checkout@v3
>       - uses: jamesgeorge007/github-activity-readme@master
>         env:
>           GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
> ```

### Profile Views
![Profile Views](https://komarev.com/ghpvc/?username=fanrado&color=blueviolet&style=flat-square&label=Profile+Views)

<!--
**fanrado/fanrado** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
