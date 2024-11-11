



Make project => npm init @motion-canvas@latest

install libraries like this =>  

npm install @motion-canvas/core
npm install @motion-canvas/2d
npm install @motion-canvas/ffmpeg

Run => npm run serve

sudo apt install ffmpeg

To Convert Video => ffmpeg -framerate 30 -i output/project/%06d.png -c:v libx264 -r 30 -pix_fmt yuv420p output.mp4