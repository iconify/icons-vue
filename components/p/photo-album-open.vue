<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wp7oc8b9j"/><path class="dhz9ng17b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-album-open" /></template>
<style>
.dhz9ng17b {
  d: path("M5.5 7.75h3.75v5.5H5.5Zm9.25 0h3.75v5.5h-3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp7oc8b9j {
  d: path("M2.5 4.5h6A3.5 3.5 0 0 1 12 8v12.5A2.5 2.5 0 0 0 9.5 18h-7Zm19 0h-6A3.5 3.5 0 0 0 12 8v12.5a2.5 2.5 0 0 1 2.5-2.5h7Z");
}

</style>
