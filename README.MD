# CSS HTML Project COde

## FONTS FAMILY
Regole font face 
```css
@font-face {
    font-family: 'Commuters Sans Semi';
    src: url('../fonts/CommutersSans-SemiBold.woff2') format('woff2');
    font-weight: 600;
    font-style: normal;
    font-display: swap;
}


@font-face {
    font-family: 'HK Grotesk';
    src: url('../fonts/HKGrotesk-Bold.woff2') format('woff2');
    font-weight: bold;
    font-style: normal;
    font-display: swap;
}

@font-face {
    font-family: 'HK Grotesk';
    src: url('../fonts/HKGrotesk-Regular.woff2') format('woff2');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}

@font-face {
    font-family: 'HK Grotesk';
    src: url('../fonts/HKGrotesk-SemiBold.woff2') format('woff2');
    font-weight: 600;
    font-style: normal;
    font-display: swap;
}

@font-face {
    font-family: 'MADE Outer Sans';
    src: url('../fonts/MADEOuterSans-Medium.woff2') format('woff2');
    font-weight: 500;
    font-style: normal;
    font-display: swap;
}

@font-face {
    font-family: 'MADE Outer Sans';
    src: url('../fonts/MADEOuterSans.woff2') format('woff2');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}


@font-face {
    font-family: 'MADE Outer Sans Outline';
    src: url('../fonts/MADEOuterSansOutline.woff2') format('woff2');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}


@font-face {
    font-family: 'Ogg Roman';
    src: url('../fonts/Ogg-Roman.woff2') format('woff2');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}

@font-face {
    font-family: 'Ogg';
    src: url('../fonts/Ogg-Medium.woff2') format('woff2');
    font-weight: 500;
    font-style: normal;
    font-display: swap;
}

@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.4/font/bootstrap-icons.css");
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300;400;700&family=Roboto+Slab:wght@300;400;700&display=swap');
```

Settare custom props
```css
:root {

    /* breakpoint */
    /*
    --brk-sm: 576px;
    --brk-md: 768px;
    --brk-lg: 992px;
    --brk-xl: 1200px;
    --brk-xxl: 1400px;
    */

    /* colors */
    --clr-black: hsl(0, 100%, 0%);
    --clr-white: hsl(0, 100%, 100%);
    --clr-giallino: #F5FE6C;
    --clr-azzurrino: #D6E3FE;
    --clr-azzurro: #487AFF;
    --clr-vaniglia: #FAF4E8;
    --clr-rossovaniglia: #FFD2C3;

    /*  fonts colors */
    --clr-font: #000000;
    --clr-head: #487AFF;
    --clr-link: #487aff;


    /* font-sizes */
    --fs-h1: 4.375rem;  /*70px*/
    --fs-h2: 3.25rem;   /*px*/
    --fs-h3: 2.4375rem; /*39px*/
    --fs-h4: 1rem;      /*16px*/
    --fs-h5: 0.875rem;  /*14px*/
    --fs-h6: 0.75rem;   /*12px*/
    --fs-p: 1rem;       /*16px*/

    /* font-weight */
    --fw-text:400;   /* testo normale  */
    --fw-header:700; /* header */

    /* font-families */
    --ff-header: 'MADE Outer Sans', Helvetica, sans-serif;
    --ff-text: 'HK Grotesk', Helvetica, sans-serif;
  
  
    /* Input, textarea, select */
    --input-radius: 4px; /* raggio del bordo delle input*/
    --input-padding: 8px 16px; /* padding input e textarea */
    --input-clr-border:hsl(0, 0%, 87%); /* colors */

}
```


# SASS Command
```bash
#win
sass --watch -–embed-source-map .\assets\scss\main.scss .\assets\css\main.css

#mac
sass --watch ./assets/scss/main.scss ./assets/css/main.css
```