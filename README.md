# LoggerBridge

**Debug your applications without leaving your IDE!**

LoggerBridge is a powerful development tool that displays console logs directly in the sidebar of **IntelliJ IDE** or **WebStorm**, enabling seamless debugging without switching between your browser and editor.

## 🎯 What is LoggerBridge?

LoggerBridge bridges the gap between your browser console and your IDE. As you write and execute code in your application, all console logs are captured and displayed in real-time within your IDE's sidebar. This means you can debug efficiently while keeping your full development environment in one place.

### Key Benefits

- ✨ **Real-time Logging**: View console logs instantly in your IDE sidebar
- 🚀 **Stay Focused**: No need to switch between browser dev tools and your editor
- 🔍 **Easy Debugging**: Quickly identify and fix issues without losing context
- 💻 **IDE Integration**: Seamlessly integrates with IntelliJ IDE and WebStorm

## 📦 Supported Frameworks

LoggerBridge currently supports the following build tools and frameworks:

- **Vite** - Lightning-fast development server and build tool
- **Next.js** - The React framework for production

## 🚀 Getting Started

### Installation

```bash
npm install loggerbridge
```

### Configuration

After installation, configure LoggerBridge in your project based on your framework:

#### For Vite

Add LoggerBridge to your `vite.config.js`:

```javascript
import { defineConfig } from 'vite'
import loggerBridge from 'loggerbridge/vite'

export default defineConfig({
  plugins: [loggerBridge()]
})
```

#### For Next.js

Add LoggerBridge to your `next.config.js`:

```javascript
const withLoggerBridge = require('loggerbridge/next')

module.exports = withLoggerBridge({
  // your Next.js config
})
```

## 💡 How It Works

1. **Log Capture**: LoggerBridge intercepts console logs from your application
2. **Real-time Sync**: Logs are sent to your IDE in real-time
3. **Sidebar Display**: View formatted logs directly in your IntelliJ/WebStorm sidebar

No additional setup required! Once installed and configured, simply start your development server and watch your logs appear in the IDE sidebar.

## 🛠️ IDE Setup

### IntelliJ IDE & WebStorm

LoggerBridge works with both IntelliJ IDEA and JetBrains WebStorm. A companion plugin is available to view logs in the IDE sidebar.

## 📝 Usage Example

```javascript
// Your application code
console.log('Application started')
console.warn('Warning: This is a warning')
console.error('Error: Something went wrong')
```

All these logs will appear in your IDE's LoggerBridge sidebar panel automatically!

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues and pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](./LISCENSE.md) file for details.

## 📞 Support

For questions, issues, or suggestions, please open an issue on our GitHub repository.

---

**Happy Debugging!** 🎉
