<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-hk6kbxb"/><path class="qx6uwbv5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sumo-wrestler" /></template>
<style>
.qx6uwbv5n {
  d: path("M9 16.5L5 18l-.5 3.5m10.5-5l4 1.5l.5 3.5");
}

.r-hk6kbxb {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.25 9a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM3 8.5l5.25 3m7.5 0l5.25-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
