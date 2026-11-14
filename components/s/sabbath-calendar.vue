<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vei1ezbvx"/><path class="hd_hnobcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sabbath-calendar" /></template>
<style>
.hd_hnobcl {
  d: path("M20.25 15a3.75 3.75 0 1 0 .75 5.25a3 3 0 0 1-.75-5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vei1ezbvx {
  d: path("M11.8 20H2.5V4.5h16v7M7 3v3m7-3v3M2.5 9h16M7 13.5h.01m3.99 0h.01");
}

</style>
