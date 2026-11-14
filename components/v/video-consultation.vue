<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aczfj1b3d"/><path class="b_21y31ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-consultation" /></template>
<style>
.aczfj1b3d {
  d: path("M11.9 14H2.5V4.5h12v6.9m1.597.058L14.5 10.5V8l5-3v6.469m-4.75 2.781V16c0 1.5 1 2.5 2.25 2.5s2.25-1 2.25-2.5v-1.75M17 18.5v1c0 1.25.75 2 2 2c1 0 1.75-.75 1.75-1.75");
}

.b_21y31ym {
  fill: currentColor;
  d: path("M19.75 18.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
