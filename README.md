# Software Engineer | Systems & C++ Specialist

High-performance backend services, network packet analyzers, and computer vision pipelines built in modern C++. Focused on low-level systems engineering, network protocols, and bridging classical algorithms with modern AI integration.

---

### Technical Competencies

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Linux/WSL-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" alt="OpenCV" />
</p>

- **Languages:** C++11/17, C, Python, SQL
- **Systems & Networking:** POSIX Sockets, TCP/IP, libpcap, Berkeley Packet Filters (BPF), HTTP/1.1 Protocol Design, Multithreading
- **Computer Vision & AI:** OpenCV, Canny Edge Detection, Hough Transforms, Local LLM Integration (Ollama via libcurl)
- **Toolchain & Build Systems:** CMake, Git, Linux/WSL, Bash

---

### Featured Projects

#### [NetLens](https://github.com/localopensource/netlens)
*High-performance network packet analyzer.*
- Hooks directly into network interfaces via **libpcap** to capture live data-link layer traffic in real time.
- Implements custom **Berkeley Packet Filter (BPF)** expressions for targeted packet selection by protocol, host, or port.
- Decodes IPv4 headers, parses TCP/UDP transport layers, extracts raw HTTP plaintext payloads, and exports incremental records to a structured JSON stream.

#### [LaneVision-LLM](https://github.com/localopensource/LaneVision-LLM)
*Hybrid computer vision and AI driving assistance pipeline.*
- Combines classical computer vision techniques (**OpenCV**, **Canny Edge Detection**, **Hough Line Transforms**) with region-of-interest filtering for real-time lane line extraction.
- Integrates with a local **Ollama** instance via `libcurl` to periodically translate visual road conditions into natural language insights.

#### [WebSearchEngine](https://github.com/localopensource/web-search-engine)
*Zero-dependency HTTP search engine server.*
- Built entirely on C++11 and POSIX sockets without external web frameworks.
- Implements an in-memory **inverted index** using whitespace tokenization for constant-time lookups, coupled with a raw socket HTTP handler and clean web query interface.

#### [DataPlatform Server](https://github.com/alfred7070/dataplatform)
*Lightweight file upload and analysis server.*
- Handles HTTP file uploads with binary signature (magic number) verification for robust type detection.
- Features a built-in CSV parser with DataFrame-style label and one-hot encoding capabilities.

---

### Profile Statistics

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=localopensource&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</p>

---

### Connect
- GitHub: [@localopensource](https://github.com/localopensource)
