# React Dashboard App

## Introduction

App made with React using:

- dark/light mode
- theme color tokens
- dashboard with different Data
- three data table Pages (Team, Contacts, Invoices)
- Profile Form Page
- Calendar integration
- FAQ
- four different Charts

## Links

Here are source links and libraries used in the project:

- [tutorial](https://www.youtube.com/watch?v=wYpCWwD1oz0)
- [sourcecode](https://github.com/ed-roh/react-admin-dashboard)
- [mockData](https://github.com/ed-roh/react-admin-dashboard/tree/master/src/data)

##

- create-react-app: [link](https://create-react-app.dev/)
- material ui: [link](https://mui.com/material-ui/getting-started/installation/)
- nivo charts: [link](https://nivo.rocks/components)
- full calendar: [link](https://fullcalendar.io/docs)
- formik: [link](https://formik.org/docs/overview#installation)
- yup validation: [link](https://github.com/jquense/yup)
- react pro sidebar: [link](https://github.com/azouaoui-med/react-pro-sidebar)
- google fonts: [link](https://fonts.google.com/)

## Description

- at first install react app,
- then delete unnecessary files (setupTests.js, reportWebVitals.js, logo.svg, App.test.js
- copy data mock files into data folder
- arrange features, components, scenes in particular way to keep balance between nesting and flat structure
- adjust theme color design tokens
- expand colors with Tailwind Shades extention (VSCode), using shortcut (cmd+k+g)
- build dark and light setup and color palette with ternary operation
- setup typography
- build Topbar
- place data, tables and charts imports to App.js as Routes
- comment it out until component is built and function
- create Sidebar with React Pro Sidebar
- import icons from mui/icons-material
- build Tables with MUI Data Grid
- place toolbar container (GridToolbar) for filtering informations from the table
- build profile form page with Formik and Yup validation and required fields
- build Calendar (FullCalendar) with add events to Calendar
- create FAQ element with MUI Accordion
- build Nivo Charts (Bar, Pie, Line, Geography)
- Geography Chart needs mockGeoData to dipslay a world map
- before build dashboard, create ProgressCircle and StatBox to visual Data
- in the end we build Dashboard with Grid, put elements inside with individual design
