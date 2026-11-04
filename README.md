<div align="center">

# Hi, I'm Pratik 👋

### Backend Software Engineer · C# / .NET Core / SQL Server

I build REST APIs and data-driven applications in C# and .NET, from loan-platform backends to real-time hardware monitoring clients.

<a href="https://www.linkedin.com/in/pratikgholam/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
<a href="https://portfolio.pratikgholam.workers.dev/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge" alt="Portfolio"></a>
<a href="mailto:gholampratik2@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge" alt="Email"></a>

</div>

---

### ⚡ What I'm Up To

- 🔭 **Currently building:** [Grounded QA](https://github.com/pratikgholam/groundedqa), a document Q&A API that answers from your documents (FastAPI, PostgreSQL/pgvector)
- 🌱 **Next:** LLD/HLD design-pattern projects in Python
- 💬 **Ask me about:** C#, .NET Core, REST API design, SQL Server / PostgreSQL optimization

---

### 📦 Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pratikgholam/loan-application-api">Loan Application API</a></h4>
      <p>ASP.NET Core REST API for submitting and reviewing loan applications, with JWT roles, EF Core + Dapper, and fake data</p>
      <p>✅ Complete</p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pratikgholam/groundedqa">Grounded QA</a></h4>
      <p>Document Q&A API (FastAPI, PostgreSQL/pgvector) that answers only from your documents</p>
      <p>🚧 In progress</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pratikgholam/parking-lot-lld">Parking Lot (LLD)</a></h4>
      <p>Framework-free Python library modeling a parking lot, demonstrating Strategy, Factory, and State patterns in about 200 lines</p>
      <p>✅ Complete</p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pratikgholam/leaderboard-hld">Leaderboard (HLD)</a></h4>
      <p>Real-time leaderboard service in Python with FastAPI, Redis sorted sets, and PostgreSQL, supporting score updates, top-N queries, rank lookups, and rebuilds from the database</p>
      <p>🚧 In progress</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/pratikgholam/portfolio">Portfolio</a></h4>
      <p>Personal portfolio site built with React + Vite</p>
      <p>✅ Complete</p>
    </td>
    <td width="50%"></td>
  </tr>
</table>

---

### 🏗️ Leaderboard Architecture

```mermaid
flowchart LR
    C[Client] -->|score updates, top-N, rank lookups| A[FastAPI]
    A --> R[(Redis sorted set)]
    A --> P[(PostgreSQL)]
    P -.->|rebuild| R
```

---

<details open>
<summary><b>🛠️ Tech Stack & Tools</b></summary>

<br>

[![My Skills](https://skillicons.dev/icons?i=cs,dotnet,py,postgres,sqlite,docker,postman,visualstudio,gitlab,bitbucket)](https://skillicons.dev)

</details>
