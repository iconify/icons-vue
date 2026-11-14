<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p302tubho"/><path class="knemzt0hn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-releases" /></template>
<style>
.knemzt0hn {
  d: path("M14 14h4.25L22 17.75L17.75 22L14 18.25Zm3.25 2.5a.75.75 0 1 1-1.5 0a.75.75 0 1 1 1.5 0");
}

.p302tubho {
  d: path("m3 8.5l2.5-5h11l2.5 5M11.2 19H3V8.5h16v2.7m-8-7.7v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
