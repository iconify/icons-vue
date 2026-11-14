<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qjst479lq"/><path class="l5yjw_ein"/><path class="ylxs07s0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sql-query" /></template>
<style>
.l5yjw_ein {
  d: path("M3.5 5.5V16c0 1.4 2.9 2.5 6.5 2.5c.903 0 1.762-.069 2.542-.195m3.958-5.778V5.5");
}

.qjst479lq {
  d: path("M3.5 5.5a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylxs07s0d {
  d: path("M3.5 11c0 1.4 2.9 2.5 6.5 2.5s6.5-1.1 6.5-2.5m-1.25 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
