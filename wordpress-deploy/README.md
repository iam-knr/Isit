# wordpress-deploy

This folder is ready for WordPress deployment.

## Structure
```
wordpress-deploy/
├── index.html          ← Main page (all HTML + links to assets)
├── assets/
│   ├── styles-CRpUriXv.css   ← All CSS (copy from isittest.lovable.app/assets/)
│   ├── index-DgulxPxT.js     ← Main JS (copy from isittest.lovable.app/assets/)
│   └── index-CjFPfepD.js     ← Secondary JS (copy from isittest.lovable.app/assets/)
└── images/             ← Place all images here with these filenames:
    ├── hero-bg.jpg           (photo-1604328698692)
    ├── cafe-lounge.jpg       (photo-1567521464027)
    ├── office-pods.jpg       (photo-1497366216548)
    ├── sofa-seating.jpg      (photo-1555041469)
    ├── work-from-home.jpg    (photo-1519219788971)
    ├── training-conference.jpg (photo-1431540015161)
    ├── workstations.jpg      (photo-1497366811353)
    ├── at-work.jpg           (photo-1521737711867)
    ├── decor-1.jpg           (photo-1519710164239)
    ├── decor-2.jpg           (photo-1567538096630)
    ├── decor-3.jpg           (photo-1505691938895)
    ├── decor-4.jpg           (photo-1493663284031)
    ├── prod-1.jpg            (photo-1551298370)
    ├── prod-2.jpg            (photo-1506439773649)
    ├── prod-3.jpg            (photo-1538688525198)
    ├── prod-4.jpg            (photo-1503602642458)
    ├── prod-5.jpg            (photo-1505842465776)
    ├── prod-6.jpg            (photo-1524758631624)
    └── prod-7.jpg            (photo-1517705008128)

## WordPress Deployment Steps
1. Copy the `assets/` files from `isittest.lovable.app/assets/` into `wordpress-deploy/assets/`
2. Download all Unsplash images from `images.unsplash.com/` folder and rename as listed above
3. Upload the entire `wordpress-deploy/` folder to your WordPress server via FTP or File Manager
4. Use a plugin like **WP Full Page** or **WP HTML Page** to serve `index.html` as a page
