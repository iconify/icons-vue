<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cpro7i31k"/><path class="b4xrkw-at"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nanotechnology" /></template>
<style>
.b4xrkw-at {
  d: path("M6.25 6.25h4v4h-4Z");
}

.cpro7i31k {
  d: path("M3.25 3.25h10v10h-10Zm5 10v4.5h6.5m0 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
