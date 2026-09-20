<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xghzoeu6w"/><path class="a085ddcqe"/><linearGradient id="SVGDJoPBdir" x1="77.472" x2="89.207" y1="63.264" y2="63.264" gradientUnits="userSpaceOnUse"><stop offset=".038" class="j_fno4aum"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGDJoPBdir)" class="l4c8stblk"/><path class="h64oq8d8g"/><radialGradient id="SVGkna36bJo" cx="43.638" cy="105.54" r="9.026" gradientTransform="rotate(-28.43 -181.03 158.727)scale(.978 2.0688)" gradientUnits="userSpaceOnUse"><stop offset=".59" class="laf-bkbil"/><stop offset=".834" class="zewr1kbff"/></radialGradient><path fill="url(#SVGkna36bJo)" class="pha5fhe2m"/><path class="c8af54bmt"/><path class="sayvc9nli"/><path class="blfvl5bvu"/><ellipse class="re_2ptn2y"/><ellipse class="n3dnsmbvd"/><linearGradient id="SVGGG7dScUa" x1="39.281" x2="60.864" y1="38.468" y2="38.468" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVGGG7dScUa)" class="jkjptrbxe"/><linearGradient id="SVGDA528yIt" x1="39.224" x2="60.864" y1="46.932" y2="46.932" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVGDA528yIt)" class="d9is746cy"/><linearGradient id="SVGkydtMeyU" x1="39.167" x2="60.864" y1="55.395" y2="55.395" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVGkydtMeyU)" class="vz8h8ccru"/><linearGradient id="SVG7nnStdzj" x1="39.11" x2="60.864" y1="63.859" y2="63.859" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVG7nnStdzj)" class="gylkswz1y"/><linearGradient id="SVGnDvVVbIX" x1="39.053" x2="60.864" y1="72.323" y2="72.323" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVGnDvVVbIX)" class="y180rtb1m"/><linearGradient id="SVGFSSrY8aT" x1="38.997" x2="60.864" y1="80.787" y2="80.787" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVGFSSrY8aT)" class="rhf__zbcg"/><linearGradient id="SVGLJlsIcNP" x1="38.94" x2="60.888" y1="89.251" y2="89.251" gradientUnits="userSpaceOnUse"><stop offset=".019" class="kacmtwbzx"/><stop offset=".49" class="w5ad4rbkj"/><stop offset=".994" class="kacmtwbzx"/></linearGradient><path fill="url(#SVGLJlsIcNP)" class="dkk9cljph"/><linearGradient id="SVG7we11b5k" x1="68.194" x2="89.2" y1="38.434" y2="38.434" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVG7we11b5k)" class="j9ejzivji"/><linearGradient id="SVGbut4tduO" x1="68.384" x2="89.106" y1="46.905" y2="46.905" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGbut4tduO)" class="wnnim9b1v"/><linearGradient id="SVGlPX1RdhQ" x1="68.573" x2="89.011" y1="55.379" y2="55.379" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGlPX1RdhQ)" class="onbmtpbmz"/><linearGradient id="SVGXl6bZdVn" x1="68.762" x2="88.917" y1="63.854" y2="63.854" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGXl6bZdVn)" class="ks7g09boq"/><linearGradient id="SVGY7MiFMdF" x1="68.951" x2="88.823" y1="72.331" y2="72.331" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGY7MiFMdF)" class="mk-uwibow"/><linearGradient id="SVGyN3AzekI" x1="69.141" x2="88.728" y1="80.808" y2="80.808" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGyN3AzekI)" class="ii-l91-mz"/><linearGradient id="SVGIffbqBwB" x1="69.33" x2="88.634" y1="89.285" y2="89.285" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhqexyg7v"/><stop offset="1" class="eimpsdbhq"/></linearGradient><path fill="url(#SVGIffbqBwB)" class="nhiq-o37m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:thread" /></template>
<style>
.a085ddcqe {
  fill: var(--svg-color--f7cf92, #f7cf92);
  d: path("M28.83 103.12c0-1.61 10.11-9.97 10.11-9.97c6.36-3.13 44.25-2.35 50.12 0c0 0 10.11 8.06 10.11 9.97c0 3.21-15.86 7.26-35.28 7.26s-35.06-4.04-35.06-7.26");
}

.blfvl5bvu {
  fill: var(--svg-color--e6a467, #e6a467);
  d: path("M28.86 21.83c-2.82-2.33-1.3-10.02.51-11.01c5.75-3.15 58.88-4.13 68.75-.45c3.44 1.29 3.05 8.66 1.08 11.46c-2.55 3.61-15.74 5.82-35.17 5.82s-30.85-2.25-35.17-5.82");
}

.c8af54bmt {
  fill: var(--svg-color--0091ea, #0091ea);
  d: path("M73.81 125c-7.7 0-14.74-1.01-20.87-3.03c-10.43-3.43-17.65-9.61-20.32-17.4C28.34 92.09 37.71 69 42.75 56.6c1.29-3.17 2.3-5.67 2.71-7.04a1.464 1.464 0 1 1 2.81.83c-.45 1.51-1.49 4.07-2.8 7.31c-4.89 12.05-13.99 34.47-10.06 45.92c4.35 12.68 24.29 23.74 58.69 16.81c.79-.15 1.8-.15 2.14.58c.38.81-.35 1.57-1.15 1.73c-7.49 1.51-14.63 2.26-21.28 2.26");
}

.d9is746cy {
  d: path("m39.28 46.34l-.05-3.51c4.34 2.87 10.03 4.88 21.64 4.94l-.26 3.18c-10.85.52-17.7-1.48-21.33-4.61");
}

.dkk9cljph {
  d: path("m39.26 89.05l-.32-4c3.39 2.74 9.8 4.93 21.92 5l.02 3.18c-11.9 1.13-18.58-2.45-21.62-4.18");
}

.eimpsdbhq {
  stop-color: var(--svg-color--01579b, #01579b);
}

.gylkswz1y {
  d: path("m39.27 63.43l-.16-3.71c3.96 2.82 9.94 4.9 21.75 4.96l-.15 3.18c-11.27.77-18.04-1.86-21.44-4.43");
}

.h64oq8d8g {
  fill: var(--svg-color--0d47a1, #0d47a1);
  d: path("M38.94 31.02v-2.09l50.12 2.09c0 3.46-11.22 6.27-25.06 6.27s-25.06-2.81-25.06-6.27");
}

.ii-l91-mz {
  d: path("m88.97 80.45l.09-3.81c-4.19 2.45-9.69 4.88-21.71 4.95l.31 3.18c10.35.99 18.03-1.97 21.31-4.32");
}

.j_fno4aum {
  stop-color: var(--svg-color--0091ea, #0091ea);
}

.j9ejzivji {
  d: path("M89.06 37.44v-3.08c-4.53 2.9-10.2 4.9-21.71 4.95l.32 3.18c11.19.2 17.46-1.14 21.39-5.05");
}

.jkjptrbxe {
  d: path("M39.28 37.8v-3.41c4.53 2.9 10.08 4.87 21.58 4.92l-.32 3.18c-10.63.4-17.51-1.28-21.26-4.69");
}

.kacmtwbzx {
  stop-color: var(--svg-color--40c4ff, #40c4ff);
  stop-opacity: 0;
}

.ks7g09boq {
  d: path("m89.01 63.24l.05-3.52c-4.32 2.63-9.89 4.89-21.71 4.95l.31 3.18c10.69.68 17.8-1.63 21.35-4.61");
}

.l4c8stblk {
  d: path("M38.94 29.23v62.23c0 1.15.67 2.2 1.73 2.67c2.75 1.23 9.32 3.17 23.33 3.17s20.58-1.94 23.33-3.17a2.93 2.93 0 0 0 1.73-2.67V29.23z");
}

.laf-bkbil {
  stop-color: var(--svg-color--784d30, #784d30);
  stop-opacity: 0;
}

.mk-uwibow {
  d: path("m88.99 71.85l.07-3.66c-4.25 2.54-9.79 4.88-21.71 4.95l.31 3.18c10.52.83 17.91-1.81 21.33-4.47");
}

.n3dnsmbvd {
  cx: 64px;
  cy: 10.78px;
  fill: var(--svg-color--784d30, #784d30);
  rx: 8.14px;
  ry: 2.47px;
}

.nhiq-o37m {
  d: path("m88.96 89.05l.1-3.95c-4.12 2.36-9.59 4.88-21.71 4.95l.31 3.18c10.18 1.15 18.14-2.14 21.3-4.18");
}

.nhqexyg7v {
  stop-color: var(--svg-color--01579b, #01579b);
  stop-opacity: 0;
}

.onbmtpbmz {
  d: path("m89.03 54.64l.03-3.37c-4.39 2.72-10 4.89-21.71 4.95l.31 3.18c10.86.52 17.69-1.47 21.37-4.76");
}

.pha5fhe2m {
  d: path("M38.75 93.31c-1.8 4.76-.62 9.68 1.99 14.05s6.48 7.82 10.36 11.13c-2.55.14-5.04-.87-7.22-2.2c-6.36-3.91-10.38-10.42-11.06-17.85");
  opacity: var(--svg-opacity--0-32, 0.32);
}

.re_2ptn2y {
  cx: 64px;
  cy: 12.02px;
  fill: var(--svg-color--f7cf92, #f7cf92);
  rx: 35.17px;
  ry: 7.02px;
}

.rhf__zbcg {
  d: path("m39.26 80.51l-.26-3.9c3.58 2.77 9.85 4.92 21.87 4.99l-.03 3.18c-11.71 1-18.42-2.26-21.58-4.27");
}

.sayvc9nli {
  fill: var(--svg-color--c87d5e, #c87d5e);
  d: path("M38.94 29.23s-5.82-3-10.08-7.4l69.41.92c-2.68 3.97-9.22 8.11-9.22 8.11s-4.55 2.25-25.49 2.25s-24.62-3.88-24.62-3.88");
}

.vz8h8ccru {
  d: path("m39.27 54.88l-.11-3.61c4.15 2.85 9.98 4.89 21.7 4.95l-.2 3.18c-11.06.65-17.87-1.66-21.39-4.52");
}

.w5ad4rbkj {
  stop-color: var(--svg-color--40c4ff, #40c4ff);
}

.wnnim9b1v {
  d: path("m89.04 46.04l.02-3.23c-4.46 2.81-10.1 4.89-21.71 4.95l.32 3.18c11.02.36 17.57-1.3 21.37-4.9");
}

.xghzoeu6w {
  fill: var(--svg-color--e6a467, #e6a467);
  d: path("M28.93 111.74s-2.91-4.72 0-8.61l68.72-1.75s5.43 3.11 1.62 10.36c-2.28 4.32-15.74 7.38-35.17 7.38s-33.34-4.09-35.17-7.38");
}

.y180rtb1m {
  d: path("m39.27 71.97l-.21-3.8c3.77 2.79 9.89 4.91 21.81 4.98l-.09 3.18c-11.49.88-18.23-2.07-21.51-4.36");
}

.zewr1kbff {
  stop-color: var(--svg-color--784d30, #784d30);
}

</style>
