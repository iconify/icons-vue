<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2m0zibzk"/><path class="ra3nu2bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oscilloscope" /></template>
<style>
.p2m0zibzk {
  d: path("M3 3.5h18v15H3Z");
}

.ra3nu2bqt {
  d: path("M6 11c1.5-4 3.5-4 5 0s3.5 4 5 0M8 21h.01M12 21h.01M16 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
