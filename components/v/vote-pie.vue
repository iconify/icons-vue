<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ye3_gfbdr"/><path class="jq0kgrbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vote-pie" /></template>
<style>
.jq0kgrbmn {
  d: path("M13 3.25a8 8 0 0 1 7 12l-7-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ye3_gfbdr {
  d: path("M10.5 4.75a8 8 0 1 0 7 12l-7-4Z");
}

</style>
