# Skydome Generator

A Three.js-based web application for converting panoramic images into hemisphere meshes with customizable ground plane projections. Perfect for creating sky domes for 3D environments, games, and virtual reality applications.

## Features

- 🌅 **Panoramic Image Support**: Load any equirectangular panoramic image
- 🎛️ **Real-time Controls**: Adjust hemisphere parameters with live preview
- 📦 **GLB Export**: Export the generated hemisphere as a standard GLB file

## Parameters

- **Ground Plane Height**: Controls the Y position where the ground plane is clamped
- **Boundary Rounding**: Smooths the transition between hemisphere and ground plane
- **Ground Plane Stretching**: Controls how much the ground plane is stretched in the XZ direction
- **Rotation**: Toggle turntable animation of the hemisphere

## Quick Start

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd skydome-generator
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser to `http://localhost:3000`

## Usage

1. **Load a Panorama**: Click "Upload Panorama" to load your own equirectangular image, or use the default landscape
2. **Adjust Parameters**: Use the GUI controls to modify the hemisphere shape:
   - Drag sliders to see real-time changes
   - Toggle rotation to see the hemisphere from different angles
3. **Export**: Click "Export as GLB" to download the hemisphere as a 3D model file


## File Formats

### Input
- **Panoramic Images**: JPG, PNG, WebP equirectangular format
- Common sources: 360° cameras, panoramic photography, AI-generated skyboxes

### Output
- **GLB Format**: Binary glTF file containing geometry and embedded textures
- Compatible with Blender, Unity, Unreal Engine, and other 3D software

## Built With
- **Three.js**: 3D graphics and WebGL rendering
- **Vite**: Fast build tool and development server
- **lil-gui**: Lightweight GUI controls