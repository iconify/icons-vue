<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="no8kblw0g"/><path class="bcl4mtb-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terminal-root" /></template>
<style>
.bcl4mtb-k {
  d: path("m6.5 7l3 3l-3 3m10 1v8m3-8v8M14 16.75h8m-8 2.75h8");
}

.no8kblw0g {
  d: path("M11.2 17.5H2.5v-15h17v8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
