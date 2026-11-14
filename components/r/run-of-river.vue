<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eclq2vbmh"/><path class="jue--d_rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:run-of-river" /></template>
<style>
.eclq2vbmh {
  d: path("M3.5 13.25a8.5 8.5 0 0 1 17 0M12 4.75v8.5");
}

.jue--d_rz {
  d: path("m6 7.25l6 6l6-6M2.5 17.75q2.375-2.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
