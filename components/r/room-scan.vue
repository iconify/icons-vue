<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="ig5rxfb8s"/><path class="h_wb1wqlm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:room-scan" /></template>
<style>
.h_wb1wqlm {
  d: path("M14 21v-5.5");
}

.ig5rxfb8s {
  fill: currentColor;
  d: path("m3 3l7.75 3.25a8.4 8.4 0 0 1-4.5 4.5Z");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
