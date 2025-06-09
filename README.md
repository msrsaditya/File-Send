# File Share

A secure, peer-to-peer file sharing application that allows direct file transfers between browsers without any servers or cloud storage.

## Features

- **Direct P2P Transfer**: Files are sent directly between browsers using WebRTC
- **No Server Required**: Your files never touch a server - complete privacy
- **Multiple File Support**: Share individual files or entire folders
- **Real-time Progress**: Live transfer statistics, speed, and progress tracking
- **Cross-platform**: Works on desktop and mobile browsers
- **Modern Interface**: Clean, responsive design with dark theme

## How to Use

### Sending Files

1. Open the application and click **"Send"**
2. Choose **"Select File"** for individual files or **"Select Folder"** for entire directories
3. Share the generated 6-character code with the recipient
4. Wait for the recipient to connect and the transfer will begin automatically

### Receiving Files

1. Open the application and click **"Receive"**
2. Enter the 6-character code provided by the sender
3. Click **"Connect"** and files will download automatically once the transfer starts

## Technical Details

- **WebRTC**: Uses peer-to-peer connections for direct browser communication
- **File Chunking**: Large files are split into 128KB chunks for reliable transfer
- **Folder Compression**: Directories are automatically zipped before transfer
- **No Dependencies**: Single HTML file with all resources included

## Browser Support

Works in all modern browsers that support WebRTC:
- Chrome 23+
- Firefox 22+
- Safari 11+
- Edge 79+

## Privacy & Security

- **Zero Server Storage**: Files are never uploaded to any server
- **Direct Transfer**: Data flows directly between browsers
- **Temporary Connections**: All connections are closed after transfer
- **Local Processing**: File compression and processing happens entirely in your browser

## Setup

No installation required! Simply:

1. Download or save the HTML file
2. Open it in any modern web browser
3. Start sharing files immediately

## Limitations

- Both users must be online simultaneously
- Transfer speed depends on internet connection quality
- Maximum file size limited by browser memory (typically 1-2GB)
- Requires modern browser with WebRTC support

## Use Cases

Perfect for:
- Sharing large files without email size limits
- Sending sensitive documents without cloud storage
- Quick file transfers between devices
- Sharing files when traditional methods aren't available

---

**Note**: This application requires an active internet connection to establish the initial peer connection, but all file data is transferred directly between browsers.
