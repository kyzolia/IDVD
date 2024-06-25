
# IDVD

The Interactive Data Visualization Dashboard is a sophisticated web application designed to transform complex datasets into meaningful, interactive visual representations. It allows users to explore, analyze, and gain insights from large amounts of data through an intuitive and customizable interface. This dashboard is particularly useful in fields such as finance, healthcare, environmental science, and social media analytics, where understanding trends, patterns, and anomalies in data is crucial.
## Features

- Real-time data visualization with interactive charts and graphs
- User-driven exploration with advanced filtering and drill-down capabilities
- Customizable dashboard layouts with drag-and-drop functionality
- Support for various data types and sources (CSV, JSON, APIs, etc.)
- Real-time updates using WebSocket connections
- Data transformation and aggregation tools
- Basic statistical analysis features
- Annotation and collaboration tools
- Responsive design for various screen sizes
- Accessibility features for inclusive use


## Tech Stack

**Client:** React, Redux, CSS, React Query, ReCharts, Web Sockets, Formik/Yup

**Server:** Node, Express, GraphQL, Wen Socket Server

**Databases:** MongoDB or PostgreSQL

**Testing:** Jest & React Testing Library (for frontend testing), Cypress (for end-to-end testing)

**DevOps:** Docker, Jenkins or GitHub Actions, Prometheus and Grafana
##  Getting Started
### Prerequisites
1. **Node.js**
2. **npm or yarn**
3. **Docker (for containerization)**
4. **PostgreSQL or MongoDB (for database)**

### Frontend and Backend
1. **Clone the repository:**

```bash
  git clone https://github.com/yourusername/IDVD.git
```
2. **Install dependencies:**

```bash
  cd IDVD/frontend
  npm install 
```

3. **Set up environment variables:**
Create a .env file in the root directory and add necessary variables (e.g., API keys, database URLs).
```bash
    REACT_APP_API_URL=http://localhost:5000/api
    NODE_ENV=development
```

4. **Start the development server:**
```bash
  npm run dev
```

5. Open your browser and navigate to http://localhost:yourPortNumber

### Build Docker
1. **Build and run container:**
```bash
    docker-compose up --build
```

## Project Structure

The project follows a modular structure:
```bash
  /src
    /components
        /charts
        /controls
        /layout
    /hooks
    /pages
    /services
    /store
    /styles
    /utils
  /public
  /tests
```
## Usage/Examples
1. ***Upload and manage datasets via the Dataset Management Page.***
2. ***Create and customize dashboards using the Dashboard Page.***
3. ***Apply filters and explore data interactively.***
4. ***Analyze data trends with built-in tools and real-time updates.***


## Author

- [@kyzolia](https://www.github.com/kyzolia)
