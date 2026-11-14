<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fl7t-9b1e"/><path class="we7xd_b3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stock-shares" /></template>
<style>
.fl7t-9b1e {
  d: path("M19 11a8 8 0 1 0-8 8v-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.we7xd_b3v {
  d: path("M21.75 13.75a8 8 0 0 1-8 8v-8Z");
}

</style>
