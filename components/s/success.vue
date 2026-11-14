<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rl70ebcsa"/><path class="w61kkhbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:success" /></template>
<style>
.rl70ebcsa {
  d: path("M21.356 10.35a9.5 9.5 0 1 1-7.706-7.706");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w61kkhbdl {
  d: path("m7.5 11.5l4 4l9-9.5");
}

</style>
