<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yd5ep8bhk"/><path class="dapq2mbda"/><path class="m7h4hcbnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scan-and-go" /></template>
<style>
.dapq2mbda {
  fill: currentColor;
  d: path("M15 17.25h6l.75 4.5h-7.5Z");
}

.m7h4hcbnu {
  d: path("M16.25 17.25v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yd5ep8bhk {
  d: path("M11.5 21.5H4v-19h12.5v9.4M7 7v6m2.5-6v6M12 7v4m1.5-4v2.5");
}

</style>
