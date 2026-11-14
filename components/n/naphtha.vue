<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wc6ci4b2q"/><path class="mu074sp7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:naphtha" /></template>
<style>
.mu074sp7y {
  d: path("M5.5 14.5q3.25-2.5 6.5 0t6.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc6ci4b2q {
  d: path("M12 2.5s-6.5 7-6.5 12a6.5 6.5 0 0 0 13 0c0-5-6.5-12-6.5-12Z");
}

</style>
