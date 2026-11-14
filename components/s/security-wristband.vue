<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tyz9vfbsp"/><path class="zvrbwjb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-wristband" /></template>
<style>
.tyz9vfbsp {
  d: path("M6.5 16.5a9.5 3.5 0 0 1-4-2.75v-4a9.5 3.5 0 0 1 19 0v4a9.5 3.5 0 0 1-4 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvrbwjb_p {
  d: path("M2.5 9.75a9.5 3.5 0 0 0 4 2.75m11 0a9.5 3.5 0 0 0 4-2.75m-15 1h11v6.75h-11Z");
}

</style>
