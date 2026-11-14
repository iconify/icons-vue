<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e54gn_b6e"/><path class="sye78vbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-private" /></template>
<style>
.e54gn_b6e {
  d: path("m3 8.5l2.5-5h11l2.5 5M12.2 19H3V8.5h16v3.1m-8-8.1v5m4 8.5h6v4.5h-6Z");
}

.sye78vbzq {
  d: path("M16.25 17v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
