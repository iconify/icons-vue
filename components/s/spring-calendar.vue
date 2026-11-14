<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="twiy9obyn"/><path class="qavx7u_3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spring-calendar" /></template>
<style>
.qavx7u_3d {
  d: path("M13.25 13.25a1.4 1.4 0 0 1 1 2.5a1.4 1.4 0 0 1-2.25 1.5a1.4 1.4 0 0 1-2.25-1.5a1.4 1.4 0 0 1 1-2.5a1.4 1.4 0 0 1 2.5 0ZM12 15h.01");
}

.twiy9obyn {
  d: path("M3 4h18v17H3Zm5-1.5V6m8-3.5V6M3 9h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
