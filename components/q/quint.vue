<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ly5fqmb4z"/><path class="ui8fbq5in"/><path fill="url(#SVGqniLze6F)" class="cf6mocmbu"/><path fill="url(#SVG8AHPRbHy)" class="mzc2hsz-i"/><path fill="url(#SVGVt1jHeNs)" class="g6me8zbkm"/><path fill="url(#SVGVSWagddA)" class="kaf4gnb9l"/><defs><linearGradient id="SVGqniLze6F" x1="8.497" x2="6.322" y1="15.419" y2="7.557" gradientUnits="userSpaceOnUse"><stop class="exqs714dq"/><stop offset="1" class="y3w5-4w-n"/></linearGradient><linearGradient id="SVG8AHPRbHy" x1="8.524" x2="8.524" y1="-1.501" y2="6.959" gradientUnits="userSpaceOnUse"><stop class="exqs714dq"/><stop offset="1" class="y3w5-4w-n"/></linearGradient><linearGradient id="SVGVt1jHeNs" x1="23.88" x2="6.96" y1="8.669" y2="8.669" gradientUnits="userSpaceOnUse"><stop class="exqs714dq"/><stop offset="1" class="y3w5-4w-n"/></linearGradient><linearGradient id="SVGVSWagddA" x1="4.967" x2="9.185" y1="9.75" y2="9.75" gradientUnits="userSpaceOnUse"><stop class="exqs714dq"/><stop offset="1" class="y3w5-4w-n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:quint" /></template>
<style>
.cf6mocmbu {
  d: path("m6 14.4l-.6.6h7.8l-.6-.6z");
}

.exqs714dq {
  stop-color: var(--svg-color--068f82, #068f82);
}

.ft5dv1b6b {
  fill: none;
}

.g6me8zbkm {
  d: path("m15 5.4l-.6.6v14.4l.6.6z");
}

.kaf4gnb9l {
  d: path("M9 8.1L5.4 5.4V15L9 12.3z");
}

.ly5fqmb4z {
  fill: var(--svg-color--12e3bc, #12e3bc);
  d: path("M17.4 18v.6H21l-.528-.6z");
}

.mzc2hsz-i {
  d: path("m6 6l-.6-.6H15l-.6.6z");
}

.ui8fbq5in {
  fill: var(--svg-color--14f4c8, #14f4c8);
  d: path("M13.2 17.4V15H5.4V5.4H15V21h6v-2.4h-3.6V3H3v14.4z");
}

.y3w5-4w-n {
  stop-color: var(--svg-color--12e3bc, #12e3bc);
}

</style>
