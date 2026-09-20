<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="chwcdpb7z"/><path class="x2pn2ibqs"/><path class="qduzx8b4n"/><path class="z025ooclp"/><circle class="kt-nbubjg"/><path class="u0y0c9bug"/><path class="kws5xyble"/><path class="chv9occxj"/><path class="c5o9fk52a"/><radialGradient id="SVGK2wVedXu" cx="69.52" cy="-97.496" r="128.802" gradientTransform="rotate(180.193 -.274 -.81)scale(-1 .5531)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="jorbl_bqv"/><stop offset="1" class="mzb4smbia"/></radialGradient><path fill="url(#SVGK2wVedXu)" class="oapk5ac_y"/><path class="csqscub7v"/><path class="asn4gdb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:purse" /></template>
<style>
.asn4gdb8x {
  fill: var(--svg-color--fff, #fff);
  d: path("m46.959 30.922l-19.982.4c-1.166 0-1.928-.39-2.086-1.32c-.182-1.067.843-1.589 2.009-1.589h20.376c1.166 0 2.39.227 2.39 1.307c0 1.032-1.541 1.202-2.707 1.202");
}

.c5o9fk52a {
  fill: var(--svg-color--a0a0a0, #a0a0a0);
  d: path("M12.959 52.578s.75 1.37 4.1.38s4.9-6.92 4.9-6.92l-.42 28.708h-8.58zm102.082-.95s-2.102 1.886-4.51.922c-2.331-.933-2.5-3.403-2.5-5.503s-.046-3.494-.046-7.038s-2.527-5.26-5.04-5.453c-5.312-.41-15.461.73-15.461.73l19.027 36.78h8.53z");
}

.chv9occxj {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M101.461 26.407H26.54c-10.61 0-13.57 7.41-13.57 13.79v25.891h102.08v-25.89c-.01-6.38-2.98-13.79-13.59-13.79");
}

.chwcdpb7z {
  cx: 72.11px;
  cy: 16.227px;
  r: 8.56px;
  fill: var(--svg-color--b7b7b7, #b7b7b7);
}

.csqscub7v {
  fill: var(--svg-color--d6336b, #d6336b);
  d: path("M56.93 35.057s-18.68 16.04-12.86 19.961c6 4.04 12.86-19.96 12.86-19.96m7.27 30c8.14 0-.42-30.19-.42-30.19s-7.72 30.19.42 30.19m7.25-30.191s5.93 24.551 12.28 20.321s-12.28-20.32-12.28-20.32");
}

.jorbl_bqv {
  stop-color: var(--svg-color--ff689b, #ff689b);
}

.kt-nbubjg {
  cx: 55.89px;
  cy: 16.227px;
  r: 8.56px;
  fill: var(--svg-color--ccc, #ccc);
}

.kws5xyble {
  fill: var(--svg-color--969696, #969696);
  d: path("M62.77 21.307c.3-.41.73-1.09.9-1.53c.05-.12-.34.03-.69.36c-.76.73-2.25 2.23-5.1 3.09c-3.71 1.12-6.32-.24-6.7-.12c-.39.13.98.81 1.18.9c.71.32 1.47.55 2.24.67l.51 1.72h7.67l-1.15-3.82c.4-.36.79-.79 1.14-1.27");
}

.mzb4smbia {
  stop-color: var(--svg-color--d6336b, #d6336b);
}

.oapk5ac_y {
  d: path("M112.281 64.998c-4.48-7.53-5.55-15.09-6.19-22.01c-.42-4.54-1.72-8.05-6.17-8.05H28.079c-4.45 0-5.75 3.52-6.17 8.05c-.64 6.91-1.71 14.48-6.19 22.01c-6.9 11.6-12.62 21.95-11.6 29.211C6.068 108.11 18.508 124 28.408 124H99.59c9.91 0 22.34-15.89 24.29-29.79c1.02-7.261-4.7-17.611-11.6-29.212");
}

.qduzx8b4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M74.272 10.41c.49.45.67 1.29.23 1.78c-.27.3-.79.52-1.44.47c-1.31-.09-2.29.23-3 .51c-1.63.64-2.47.27-2.54-.39s.12-1.87 2.63-2.65c2.51-.77 3.78-.03 4.12.28");
}

.u0y0c9bug {
  fill: var(--svg-color--fff, #fff);
  d: path("M57.232 11.14c.44.89 0 1.81-2.02 3.03c-2.09 1.26-2.38 2.41-3.24 3.31c-.7.73-2.07.46-2.23-.52c-.38-2.3.73-4.11 1.78-5.2c1.6-1.67 4.77-2.5 5.71-.62");
}

.x2pn2ibqs {
  fill: var(--svg-color--969696, #969696);
  d: path("M65.19 21.247c-.48-.62-.92-1.28-1.31-1.97c-.04-.07-.08-.14-.09-.21c-.02-.12.02-.24.05-.36c.24-.82.32-1.68.25-2.52c-.06-.65-.21-1.29-.21-1.94c0-.43.23-1.91.79-1.54c.48.32.83 1.41 1.02 1.93c.49 1.36.61 2.86.34 4.28c-.15.81-.43 1.6-.84 2.33");
}

.z025ooclp {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M64.45 30.867s.91-3.49 1.53-5.55c.84-2.81 1.49-8 5.61-7.37c1.8.28 3.35 2.08 3.09 3.9l-2.57 9.01h-7.66z");
}

</style>
