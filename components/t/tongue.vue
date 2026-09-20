<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m14tufb9h"/><path class="jey2fb36j"/><path class="y432_sb4l"/><radialGradient id="SVG2GKBgbrx" cx="66.964" cy="27.812" r="74.751" gradientTransform="matrix(1 0 0 1.0804 0 -2.003)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="kzd64ip1m"/><stop offset="1" class="rajwb9bru"/></radialGradient><path fill="url(#SVG2GKBgbrx)" class="n55tkuaav"/><linearGradient id="SVGmo9Bhb7k" x1="64.885" x2="64.885" y1="39.355" y2="88.951" gradientUnits="userSpaceOnUse"><stop offset="0" class="ku_ss9lpm"/><stop offset="1" class="qjku8hbid"/></linearGradient><path fill="url(#SVGmo9Bhb7k)" class="b0v9zjzwz"/><radialGradient id="SVGotCQEcGn" cx="65.072" cy="72.22" r="73.436" gradientTransform="matrix(.9546 0 0 .5017 2.917 34.337)" gradientUnits="userSpaceOnUse"><stop offset=".672" class="zc2mkd3sw"/><stop offset="1" class="p73o08b5o"/></radialGradient><path fill="url(#SVGotCQEcGn)" class="g6tr4hu_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:tongue" /></template>
<style>
.b0v9zjzwz {
  d: path("M64 33.3c-3.04 0-22.45-1.12-16.55.31c6.95 1.69 9.34 5.7 11.88 11.55C64 55.9 62.77 83.2 64.63 83.39c1.86.2 3.59-14.65 3.98-32.63c.3-13.83 9.26-17.19 14.81-17.41c.01.01-16.38-.05-19.42-.05");
}

.g6tr4hu_l {
  d: path("M22.26 78.08c0-15.55 6.61 7.48 42.6 7.48s42.12-21.76 42.12-6.22s-19.57 29.39-42.12 29.39s-42.6-15.11-42.6-30.65");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.jey2fb36j {
  fill: var(--svg-color--424242, #424242);
  d: path("M120.77 11.74c-7.7 2.94-31.25 9.63-56.77 9.65c-25.52-.02-49.07-6.71-56.77-9.65c-1.42-.54-2.87.84-2.75 2.35C11.14 31.72 35.28 50.73 64 50.77c28.72-.04 52.86-19.06 59.52-36.68c.12-1.51-1.33-2.89-2.75-2.35");
}

.ku_ss9lpm {
  stop-color: var(--svg-color--c41b59, #c41b59);
}

.kzd64ip1m {
  stop-color: var(--svg-color--e92c6c, #e92c6c);
}

.m14tufb9h {
  fill: none;
  d: path("M86.12 154.77v-.28");
}

.n55tkuaav {
  d: path("M110.89 76.66c-3.05-30.02-8.19-37.72-13.47-40.53c-6.7-3.56-12.97-3.02-16.37-2.32c-9.28 1.93-10.92 3.58-15.72 3.58s-7.33-1.64-16.6-3.57c-3.4-.71-9.67-1.25-16.37 2.32c-5.28 2.81-10.42 10.51-13.47 40.53c-2.04 20.05 11.73 40.53 45.97 40.53h.06c34.24-.01 48-20.49 45.97-40.54");
}

.p73o08b5o {
  stop-color: var(--svg-color--ff9cbd, #ff9cbd);
}

.qjku8hbid {
  stop-color: var(--svg-color--c41b59, #c41b59);
  stop-opacity: 0;
}

.rajwb9bru {
  stop-color: var(--svg-color--f06a97, #f06a97);
}

.y432_sb4l {
  fill: var(--svg-color--c41b59, #c41b59);
  d: path("M100.04 31.58c-2.73-1.56-8.23-2.65-13.18-2.91c-11.24-.61-14.91 3.16-22.86 3.18c-7.95-.02-11.62-3.79-22.86-3.18c-4.95.27-10.45 1.36-13.18 2.91c-5.26 3-4.34 6.61-.53 8.88c9.93 5.91 22.68 12.15 35.68 12.17c.3 0 .59-.01.89-.02c.3 0 .59.02.89.02c13-.02 25.75-6.26 35.68-12.17c3.81-2.27 4.72-5.88-.53-8.88");
}

.zc2mkd3sw {
  stop-color: var(--svg-color--ff9cbd, #ff9cbd);
  stop-opacity: 0;
}

</style>
