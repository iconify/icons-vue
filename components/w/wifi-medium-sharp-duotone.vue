<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mc8rtl3wh"/><path class="b8uh54bhe"/><path class="chh9m8bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wifi-medium-sharp-duotone" /></template>
<style>
.b8uh54bhe {
  stroke-opacity: 0.4;
  d: path("M3.6667 9.3538L4 9.0557C6.2001 7.0879 9.0483 6 12 6C14.9517 6 17.7999 7.0879 20 9.0557L20.3333 9.3538");
}

.chh9m8bfh {
  fill: currentColor;
  d: path("M13 18C13 18.5523 12.5523 19 12 19C11.4477 19 11 18.5523 11 18C11 17.4477 11.4477 17 12 17C12.5523 17 13 17.4477 13 18Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mc8rtl3wh {
  d: path("M6.3334 12.3353L6.6667 12.0372C8.1334 10.7253 10.0322 10 12 10C13.9678 10 15.8666 10.7253 17.3333 12.0372L17.6666 12.3353M8.588 15.6853L9.3333 15.0186C10.0667 14.3626 11.0161 14 12 14C12.9839 14 13.9333 14.3626 14.6667 15.0186L15.412 15.6853");
}

</style>
