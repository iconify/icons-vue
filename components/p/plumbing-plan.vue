<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="npj4b5vzi"/><path class="s6glism7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plumbing-plan" /></template>
<style>
.npj4b5vzi {
  d: path("M12.5 21H3V3h18v10.4M12 3v6m0 4v8m-9-9h5");
}

.s6glism7w {
  d: path("M18 14.25S15 17.5 15 19a3 3 0 0 0 6 0c0-1.5-3-4.75-3-4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
