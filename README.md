# Hi, I'm Noah (27卒 / CS Student)👋

<div align="center">

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=3F51B5&center=true&vCenter=true&width=435&lines=Information+Science+Student;Home+Lab+Enthusiast+(Proxmox);Backend+%26+Infra+Developer" alt="Typing SVG" />

  <p>
    <b>Network / Infrastructure / Backend</b><br>
    自宅サーバー（Home Lab）とネットワークインフラ、開発環境の自動化やコード化(IaC)に関心があります。<br>
    低レイヤーの理解を武器に、堅牢なバックエンドシステムを構築することが目標。<br>
    単に動くコードではなく、技術的な制約やシステムアーキテクチャ、保守性を考慮した「設計されたコード」の実装を心がけています。
  </p>

  <p>
    <a href="https://qiita.com/noah-devtech" target="_blank">
      <img src="https://img.shields.io/badge/Qiita-55C500?style=for-the-badge&logo=qiita&logoColor=white" alt="Qiita" />
    </a>
  </p>

</div>

---

## 🛠️ Tech Stack

<div align="center">
  
  **Main Languages**<br>
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <br><br>

  **Infrastructure & OS (Home Lab)**<br>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
  <br>
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" alt="Proxmox" />
  <img src="https://img.shields.io/badge/TrueNAS-0095D5?style=for-the-badge&logo=truenas&logoColor=white" alt="TrueNAS" />
  <br><br>

  **Tools & Automation**<br>
  <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white" alt="Gradle" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <br>
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white" alt="IntelliJ" />
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode" />
  <br>
</div>

---

## 🚀 Featured Projects

### 1. Ethernet-river
> **Visualizing network traffic flow using OSC protocol.**

ネットワークパケットの流れを「光の川」としてリアルタイムに可視化するインタラクティブ・インスタレーションです。

* **Purpose:** 目に見えないネットワーク通信の量と流れを、直感的に理解可能な形で物理空間に投影すること。
* **Architecture:** * **Capture:** Raspberry Pi上で `Pyshark` を用い、パケットをリアルタイム解析。
    * **Communication:** 解析データをOpenSound Control (OSC) プロトコルで描画用PCへ低遅延転送。
    * **Visualization:** Java (Processing) 側で受信データに基づきパーティクルを生成・描画。
* **Tech:** Python, Java (Processing), OSC, Raspberry Pi

### 2. [Processing 4 Build Automation System](https://github.com/noah-devtech/Processing4-Gradle-Template)
> **Solving native library dependency hell & Java 17 module restrictions.**

Processing 4をIntelliJ等のモダンIDEで開発するためのGradleテンプレートです。

* **Problem:** OSごとのネイティブライブラリ（JOGL/OpenGL）の手動管理が困難であり、Java 17のモジュールシステムによる制約で起動しない問題がありました。
* **Solution:** `build.gradle.kts`によるプラットフォームの動的判定と、JVM引数（`--add-opens`）の自動注入を実装し、 **「誰でも・どのOSでも一発で動く」** 環境を実現しました。
* **Tech:** Java 17, Gradle (Kotlin DSL), GitHub Actions

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=noah-devtech&show_icons=true&theme=gotham&count_private=true" alt="GitHub Stats" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=noah-devtech&layout=compact&theme=gotham&langs_count=8" alt="Top Langs" />
</div>

---

## 📫 How to reach me

2027年卒のソフトウェアエンジニア志望です。低レイヤーやネットワーク、インフラ技術に強い関心があります。

* ✉️ [Email Me](mailto:noah.dev.tech+github@gmail.com)