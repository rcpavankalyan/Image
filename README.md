# Image
// Import the copy function import { copyImageToClipboard } from 'copy-image-clipboard' // Pass the image src attribute here copyImageToClipboard('assets/image.png') .then(() => { console.log('Image Copied') }) .catch((e) => { console.log('Error: ', e.message) }) // Can be an URL too, but be careful because this may cause CORS errors copyImageToClipboard( 'https://images-na.ssl-images-amazon.com/images/I/81BES%2BtsVvL.png', ) .then(() => { console.log('Image Copied') }) .catch((e) => { console.log('Error: ', e.message) })
