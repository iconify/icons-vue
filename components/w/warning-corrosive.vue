<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehs209b4w"/><path class="g-0ap6bdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:warning-corrosive" /></template>
<style>
.ehs209b4w {
  d: path("m12 3l9.5 17.5h-19Z");
}

.g-0ap6bdq {
  d: path("M12 9s-1.75 2.5-1.75 3.5a1.75 1.75 0 0 0 3.5 0C13.75 11.5 12 9 12 9Zm-4 8.25h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
