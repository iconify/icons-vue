<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jc48t5x1r"/><radialGradient id="SVGw6biBd5g" cx="99.638" cy="45.85" r="23.419" gradientTransform="matrix(1 0 0 .4912 -21.055 59.629)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGw6biBd5g)" class="w3bjiqbbq"/><radialGradient id="SVGlzTJCerY" cx="76.573" cy="49.332" r="6.921" gradientTransform="rotate(154.924 84.432 60.42)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGlzTJCerY)" class="erztp3bup"/><radialGradient id="SVGCFZDAceM" cx="94.509" cy="68.91" r="30.399" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 33.494 157.622)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGCFZDAceM)" class="xk9q3hbtw"/><radialGradient id="SVGHbAPob6x" cx="44.31" cy="68.91" r="30.399" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 98.274 107.563)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGHbAPob6x)" class="pljcr_pki"/><radialGradient id="SVG7lPM1CZq" cx="49.439" cy="45.85" r="23.419" gradientTransform="matrix(-1 0 0 .4912 98.878 59.629)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG7lPM1CZq)" class="tmdmorb6l"/><radialGradient id="SVGVeCrwM2C" cx="26.374" cy="49.332" r="6.921" gradientTransform="rotate(205.076 4.678 51.766)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGVeCrwM2C)" class="aajsnwbfh"/><linearGradient id="SVGdNVwwe0k" x1="64" x2="64" y1="32.312" y2="4.301" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="ce2-qdwyj"/><stop offset=".225" class="ghh99pe3l"/><stop offset=".635" class="ha_czob6z"/><stop offset="1" class="k3lw9kb6h"/></linearGradient><path fill="url(#SVGdNVwwe0k)" class="p5bfb0blh"/><linearGradient id="SVGPzuSjc3t" x1="64" x2="64" y1="16.319" y2="34.552" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="sl8ua6bht"/><stop offset="1" class="b8rop1bve"/></linearGradient><path fill="url(#SVGPzuSjc3t)" class="ez_2t5bdi"/><path class="l1qxv3bfv"/><path class="a567dgbbi"/><path class="pugvin_nl"/><path class="qeehmsbaw"/><path class="f-3u8ydbc"/><path class="jmsafrbkt"/><g class="h3iawzbwl"><ellipse class="xm_cxnkcf"/><ellipse class="qi4mcqr9e"/></g><path class="e52a99bys"/><path class="n0fm6vbue"/><path class="j8wwvbbrl"/><radialGradient id="SVGh1MDAcRg" cx="82.019" cy="84.946" r="35.633" gradientTransform="matrix(.3076 .9515 .706 -.2282 -3.184 -15.605)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGh1MDAcRg)" class="z0wnxiz1y"/><radialGradient id="SVG90vmlh6A" cx="47.28" cy="123.8" r="9.343" gradientTransform="matrix(.8813 .4726 .5603 -1.045 -63.752 111.228)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVG90vmlh6A)" class="b36gj8bmp"/><radialGradient id="SVG3nW8UdVV" cx="159.055" cy="62.862" r="28.721" gradientTransform="matrix(-.9378 -.3944 -.2182 .5285 231.04 50.678)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG3nW8UdVV)" class="m1-eewucy"/><radialGradient id="SVGdpTcow2T" cx="43.529" cy="115.276" r="8.575" gradientTransform="matrix(1 0 0 -1.2233 0 153.742)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGdpTcow2T)" class="v16xqhb_x"/><radialGradient id="SVGwjOE4dEN" cx="42.349" cy="100.139" r="16.083" gradientTransform="matrix(-.9657 -.2598 -.2432 .9037 107.598 -51.632)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGwjOE4dEN)" class="gtqbt9beb"/><radialGradient id="SVGZDtaSSrv" cx="38.533" cy="84.609" r="16.886" gradientTransform="rotate(187.833 -2.584 78.504)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGZDtaSSrv)" class="o5ppj9ujw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:office-worker-medium-skin-tone" /></template>
<style>
.a567dgbbi {
  fill: var(--svg-color--1565c0, #1565c0);
  d: path("M64.58 111.61h-1.09c-1.19 0-2.22-.82-2.5-1.98l-.42-1.75c-.38-1.61 1.66-3.16 3.52-3.16s3.76 1.53 3.39 3.14l-.4 1.75c-.26 1.18-1.3 2-2.5 2");
}

.aajsnwbfh {
  d: path("M32.92 83.16c4.28-6.5-5.21-8.93-5.21-8.93l-.01.01c1.65 2.05 2.4 3.84 1.43 5.61c-1.21 2.21-4.81 2.53-4.81 2.53s4.91 4.36 8.6.78");
}

.b36gj8bmp {
  d: path("M56.95 7.39c-1.1.53-2.06 1.06-2.9 1.51c-.96.52-7.17 3.97-11.51 1.5c-2.67-1.52-2.67-5.58-2.67-5.72c-1.23 1.57-4.95 12.78 5.93 13.53c4.69.32 7.58-3.77 9.3-7.23c.62-1.26 1.59-3.1 1.85-3.59");
}

.b8rop1bve {
  stop-color: var(--svg-color--dadada, #dadada);
}

.ce2-qdwyj {
  stop-color: var(--svg-color--e3f2fd, #e3f2fd);
}

.e52a99bys {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M67.86 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.3-.71-.05-1.37-.69-1.63");
}

.erztp3bup {
  d: path("M95.1 83.16c-4.28-6.5 5.21-8.93 5.21-8.93l.01.01c-1.65 2.05-2.4 3.84-1.43 5.61c1.21 2.21 4.81 2.53 4.81 2.53s-4.91 4.36-8.6.78");
}

.ez_2t5bdi {
  d: path("M75.02 91.38H52.98l-6.59 7.12l9.48 14.69L64 103.15l8.13 10.04l9.48-14.69z");
}

.f-3u8ydbc {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M64 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S97.52 83.1 97.52 56.46c0-26.78-16.12-45.39-33.52-45.39");
}

.ghh99pe3l {
  stop-color: var(--svg-color--d6ecfc, #d6ecfc);
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.gtqbt9beb {
  d: path("m39.07 17.73l-4.81-.77c-.19 0-.83.06-1.18.11c-2.71.38-5.9 1.78-7.63 5.36c-1.86 3.86-1.81 7.17-1.3 9.38c.15.74.45 1.58.45 1.58s2.38-2.26 8.05-2.41z");
}

.h3iawzbwl {
  fill: var(--svg-color--49362e, #49362e);
}

.ha_czob6z {
  stop-color: var(--svg-color--b4dbfb, #b4dbfb);
}

.j8wwvbbrl {
  fill: var(--svg-color--543930, #543930);
  d: path("M104.07 25.11c-2.44-3.69-7.91-8.64-12.82-8.97c-.79-4.72-5.84-8.72-10.73-10.27c-13.23-4.19-21.84.51-26.46 3.03c-.96.52-7.17 3.97-11.51 1.5c-2.72-1.55-2.67-5.74-2.67-5.74s-8.52 3.25-5.61 12.3c-2.93.12-6.77 1.36-8.8 5.47c-2.42 4.9-1.56 8.99-.86 10.95c-2.52 2.14-5.69 6.69-3.52 12.6c1.64 4.45 8.17 6.5 8.17 6.5c-.46 8.01 1.03 12.94 1.82 14.93c.14.35.63.32.72-.04c.99-3.97 4.37-17.8 4.03-20.21c0 0 11.35-2.25 22.17-10.22c2.2-1.62 4.59-3 7.13-4.01c13.59-5.41 16.43 3.82 16.43 3.82s9.42-1.81 12.26 11.27c1.07 4.9 1.79 12.75 2.4 18.24c.04.39.57.47.72.11c.95-2.18 2.85-6.5 3.3-10.91c.16-1.55 4.34-3.6 6.14-10.26c2.41-8.88-.54-17.42-2.31-20.09");
}

.jc48t5x1r {
  fill: var(--svg-color--543930, #543930);
  d: path("M98.9 79.85c-1.25-2.27.34-4.58 3.06-7.44c4.31-4.54 9-15.07 4.64-25.76c.03-.06-.86-1.86-.83-1.92l-1.79-.09c-.57-.08-20.26-.12-39.97-.12s-39.4.04-39.97.12c0 0-2.65 1.95-2.63 2.01c-4.35 10.69.33 21.21 4.64 25.76c2.71 2.86 4.3 5.17 3.06 7.44c-1.21 2.21-4.81 2.53-4.81 2.53s.83 2.26 2.83 3.48c1.85 1.13 4.13 1.39 5.7 1.43c0 0 6.15 8.51 22.23 8.51h17.9c16.08 0 22.23-8.51 22.23-8.51c1.57-.04 3.85-.3 5.7-1.43c2-1.22 2.83-3.48 2.83-3.48s-3.61-.32-4.82-2.53");
}

.jmsafrbkt {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M54.8 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55m32.87 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55");
}

.k3lw9kb6h {
  stop-color: var(--svg-color--90caf9, #90caf9);
}

.l1qxv3bfv {
  fill: none;
  d: path("m115.36 123.94l.1-2.77c0-16.81-25.69-25.52-51.55-25.47c-25.62.05-51.38 7.67-51.38 25.47l-.1 2.77z");
}

.m1-eewucy {
  d: path("M79.16 5.47c7.32 1.98 10.89 5.71 12.08 10.68c.35 1.46.77 15.08-25.23-.4c-9.67-5.76-7.03-9.36-5.9-9.77c4.42-1.6 10.85-2.73 19.05-.51");
}

.n0fm6vbue {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.o5ppj9ujw {
  d: path("M24.37 33.58c-2.37 2.1-5.56 6.79-3.21 12.61c1.77 4.39 8.09 6.29 8.09 6.29c0 .02 1.26.4 1.91.4l1.48-21.9c-3.03 0-5.94.91-7.82 2.22c.03.03-.46.35-.45.38");
}

.p5bfb0blh {
  d: path("M64.14 96H64c-25.65.03-52 7.1-52 24.99v2.95h104v-2.95C116 104.12 89.9 96 64.14 96");
}

.pljcr_pki {
  d: path("M21.4 46.65c-4.24 10.35.23 21.01 4.41 25.5c.58.62 3.01 3.01 3.57 4.92c0 0 9.54-13.31 12.39-21.13c.58-1.58 1.1-3.2 1.17-4.88c.05-1.26-.14-2.76-.87-3.83c-.89-1.31-1.93-.96-3.44-.96c-2.88 0-15.49-.74-16.47-.74c.01.02-.76 1.12-.76 1.12");
}

.pugvin_nl {
  fill: var(--svg-color--1565c0, #1565c0);
  d: path("M52.14 113.13v-9.4c0-1.17 1.27-1.91 2.3-1.34l8.34 4.63c1.04.58 1.06 2.07.02 2.66l-8.34 4.78c-1.04.58-2.32-.15-2.32-1.33m23.38 0v-9.4c0-1.17-1.27-1.91-2.3-1.34l-8.34 4.63c-1.04.58-1.06 2.07-.02 2.66l8.34 4.78c1.03.58 2.32-.15 2.32-1.33");
}

.qeehmsbaw {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M64 84.33h-9.08v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98zm27.33-33.9H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.81-11.41-10.7-11.41");
}

.qi4mcqr9e {
  cx: 80.44px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.tmdmorb6l {
  d: path("M64.03 95.79v-9.44l-28.57-2.26l-2.6 3.2s6.15 8.51 22.23 8.51z");
}

.v16xqhb_x {
  d: path("M39.84 4.68c-.01.01-.03.01-.06.03h-.01c-.93.39-8.24 3.78-5.51 12.25l7.78 1.25c-6.89-6.98-2.17-13.55-2.17-13.55s-.02.01-.03.02");
}

.w3bjiqbbq {
  d: path("M63.99 95.79v-9.44l28.57-2.26l2.6 3.2s-6.15 8.51-22.23 8.51z");
}

.xk9q3hbtw {
  d: path("M106.62 46.65c4.25 10.35-.22 21.01-4.41 25.51c-.57.62-3.01 3.01-3.57 4.92c0 0-9.54-13.31-12.39-21.13c-.57-1.58-1.1-3.2-1.17-4.88c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.16-1.7 20.16-1.7c0 .01.51 1.11.51 1.11");
}

.xm_cxnkcf {
  cx: 47.56px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.z0wnxiz1y {
  d: path("M100.22 55.5c.16-1.55 4.34-3.6 6.14-10.26c.19-.71.35-1.43.5-2.15c1.46-8.09-1.16-15.52-2.79-17.98c-2.26-3.41-7.1-7.89-11.69-8.81c-.4-.05-.79-.1-1.16-.12c0 0 .33 2.15-.54 3.86c-1.12 2.22-3.41 2.75-3.41 2.75c11.97 11.98 11.12 22 12.95 32.71");
}

</style>
