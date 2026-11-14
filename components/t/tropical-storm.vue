<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bnjnom5xi"/><path class="nirtgyl_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tropical-storm" /></template>
<style>
.bnjnom5xi {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.nirtgyl_p {
  d: path("M9 12c0-5.5 5-8 9.5-8M15 12c0 5.5-5 8-9.5 8M5 3S3 5.5 3 6.75a2 2 0 0 0 4 0C7 5.5 5 3 5 3Zm14 12.25s-2 2.5-2 3.75a2 2 0 0 0 4 0c0-1.25-2-3.75-2-3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
