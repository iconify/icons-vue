<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ioppq8b0v"/><path class="v4px5cd2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-3g" /></template>
<style>
.ioppq8b0v {
  fill: currentColor;
  d: path("M3.5 14H7v6.5H3.5ZM10 9.25h3.5V20.5H10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4px5cd2k {
  d: path("M16.5 3.5H20v17h-3.5Z");
}

</style>
