# 2D Game Editor - Roblox Studio Clone

A full-featured 2D game editor that closely replicates the look and functionality of Roblox Studio, optimized for 2D game development with mobile and desktop support.

## 🚀 Quick Start

1. **Open in Browser**: Navigate to `http://localhost:8000` (server is running)
2. **Start Creating**: Use the toolbar or Explorer panel to add objects
3. **Edit Properties**: Select objects and modify them in the Properties panel
4. **Save Your Work**: Use the Save button to export your scene

## 🎮 Features

### **Toolbar (Top)**
- **Move Tool** 📐 - Select and drag objects around
- **Rotate Tool** 🔄 - Rotate selected objects  
- **Scale Tool** ⤡ - Resize objects
- **Delete Tool** 🗑️ - Click objects to delete them
- **Snap Toggle** ⊞ - Enable/disable grid snapping (20px grid)
- **Add Part** ➕ - Dropdown: Square, Circle, Image
- **Save/Load** 💾📁 - Export/import scene files

### **Canvas (Center)**
- **Visual Grid** - 20px grid background
- **Object Selection** - Click to select, blue outline shows selection
- **Drag & Drop** - Move objects by dragging
- **Touch Support** - Full mobile/tablet support

### **Explorer Panel (Top Right)**
- **Object Tree** - Hierarchical list of all scene objects
- **Quick Add Buttons** - ⬜ Square, ⭕ Circle, 🖼️ Image, 📝 Script
- **Color-Coded Icons** - Different colors for each object type
- **Click to Select** - Select objects from the list

### **Properties Panel (Bottom Right)**
- **Name** - Edit object names
- **Position** - X, Y coordinates
- **Size** - Width, Height dimensions  
- **Rotation** - Angle in degrees
- **Color** - Color picker for shapes
- **Texture Upload** - For image objects

### **Output Panel (Bottom)**
- **Timestamped Logs** - All editor actions logged
- **Color Coding**:
  - 🟢 Green = Info messages
  - 🟡 Yellow = Warnings  
  - 🔴 Red = Errors

### **Script Editor**
- **Modal Window** - Opens when adding scripts
- **Syntax Highlighting** - Lua-style placeholder
- **Available Functions**:
  ```javascript
  getPart(name)           // Get object by name
  movePart(part, x, y)    // Move object to position
  rotatePart(part, angle) // Rotate object
  scalePart(part, w, h)   // Scale object size
  log(message)            // Print to output
  ```

## 📱 Mobile Support

### **Touch Controls**
- **Tap** - Select objects
- **Drag** - Move objects around
- **Touch & Hold** - Context actions
- **Responsive Layout** - Adapts to mobile screens

### **Mobile Layout**
- Toolbar remains at top
- Canvas takes center stage
- Panels stack vertically
- Script editor resizes to 90% width

## 💾 Save & Load

### **Scene Files**
- Saves as JSON format
- Includes all object properties
- Embeds images as base64 data
- Preserves object hierarchy

### **Image Support**
- **Upload** - Click "Add Part > Image" or use Properties panel
- **High Quality** - Maintains original image quality
- **Formats** - Supports all browser-compatible image formats
- **Embedded** - Images saved within scene files

## 🛠️ Technical Details

### **Built With**
- **HTML5 Canvas** - 2D rendering engine
- **Vanilla JavaScript** - No external dependencies  
- **CSS Grid/Flexbox** - Responsive layout
- **File API** - Image and scene file handling
- **Touch Events** - Mobile gesture support

### **Performance**
- **Efficient Rendering** - Only redraws when needed
- **Memory Management** - Proper cleanup of resources
- **Cross-browser** - Works in all modern browsers
- **Lightweight** - Single HTML file, no external dependencies

## 🎯 How to Use

### **Creating Objects**
1. Click "Add Part" dropdown in toolbar
2. Select Square, Circle, or Image
3. Object appears on canvas and in Explorer
4. Edit properties in Properties panel

### **Moving Objects**
1. Select Move tool (default)
2. Click object to select
3. Drag to new position
4. Enable grid snapping for precise placement

### **Editing Properties**
1. Select an object
2. Properties panel shows editable fields
3. Change Name, Position, Size, Rotation, Color
4. Changes apply immediately

### **Working with Images**
1. Click "Add Part > Image" or use Explorer button
2. Select image file from device
3. Image maintains quality and aspect ratio
4. Resize using Properties panel or Scale tool

### **Scripting**
1. Add script from Explorer panel
2. Script editor opens in modal window
3. Write code using available functions
4. Scripts can manipulate scene objects

### **Saving Your Work**
1. Click Save button in toolbar
2. Downloads scene.json file
3. To load: Click Load button, select saved file
4. Scene restores with all objects and images

## 🔧 Customization

The editor is highly customizable. Key areas for modification:

- **Grid Size** - Change `gridSize` property (default: 20px)
- **Colors** - Modify CSS color variables
- **Tools** - Add new tools to toolbar
- **Object Types** - Create new shape types
- **Scripting** - Extend available script functions

## 🌟 Tips & Tricks

- **Grid Snapping** - Enable for precise alignment
- **Explorer Selection** - Click items in Explorer to select on canvas
- **Property Editing** - Use number inputs for exact positioning
- **Mobile Gestures** - Pinch and rotate gestures coming in future updates
- **Keyboard Shortcuts** - Delete key removes selected objects
- **Image Quality** - Upload high-resolution images for best results

## 🐛 Troubleshooting

**Objects not appearing?**
- Check they're not off-screen
- Look in Explorer panel for all objects

**Images not loading?**
- Ensure image format is supported
- Check browser console for errors

**Mobile touch not working?**
- Ensure you're using a modern mobile browser
- Try refreshing the page

**Save/Load issues?**
- Check browser allows file downloads
- Ensure JSON file is valid

---

**Enjoy creating amazing 2D games with your Roblox Studio-inspired editor!** 🎮
