to download image in React use;
install file saver  presumably with npm i file-saver or something similar
import { saveAs } from 'file-saver';


const Index = () => {
  const downloadImage = () => {
    saveAs('http/address or image from your progect', 'pics.jpg') // Put your image url here.
  }

  return <i class="fa fa-download" onClick={downloadImage} >  Download</i>
}
to use image as an image you need to at first import it 
import img from './pics/myimg.jpg', 
then yo can use img in your code <img src={img}>
