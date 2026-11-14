<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ly8yqsb5e"/><path class="vk1p0w-pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:router-5g" /></template>
<style>
.ly8yqsb5e {
  d: path("M12.7 17H2.5V8h19v5.4M6.5 8V3m11 5V3m-2 17.5h.01m-.01-3.75a3.75 3.75 0 0 1 3.75 3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk1p0w-pu {
  d: path("M15.5 14a6.5 6.5 0 0 1 6.5 6.5");
}

</style>
