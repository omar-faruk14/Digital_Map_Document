# Digital Map Project for Bird Survey

This project focuses on environmental surveys, specifically tracking bird movements, using a digital mapping solution. The system is built with Next.js for the frontend and Node.js with Express for the backend. The application provides real-time location tracking and visualization, allowing users to observe and analyze bird movements on a map of Japan.

## Key Features

1. **Real-time Location Tracking**
   - **Bird Movement Visualization**: The application displays real-time locations of birds, tracking their movements across a GIS map of Japan. This feature helps in monitoring bird migration patterns and behaviors.

2. **Interactive Map Interface**
   - **Leaflet Integration**: Utilizes Leaflet, a powerful JavaScript library for interactive maps, to provide a smooth and responsive map experience.
   - **Spline and Line Drawer**: Includes tools for drawing splines and lines on the map to represent bird flight paths. These tools are equipped with directional arrows, indicating the movement direction of the birds.

3. **Shapefile Generation**
   - **Drawing Export**: Users can draw areas or paths on the map, which can then be exported as shapefiles. This functionality is crucial for further analysis and record-keeping in GIS applications.
   - **Backend Processing**: The Node.js backend, built with Express and other supporting libraries, handles the conversion of drawn map data into shapefiles, ensuring seamless data management and export capabilities.

## Applications and Use Cases

- **Environmental Surveys**: The primary use case is for bird surveys, allowing researchers and environmentalists to study bird migration patterns and habitat use.
- **Data Analysis and Research**: The exported shapefiles can be used in various GIS tools for detailed analysis, supporting environmental research and conservation efforts.
