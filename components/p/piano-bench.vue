<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojrcwccqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piano-bench" /></template>
<style>
.ojrcwccqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v5h-19Zm3 5v10.5M15.5 9v6.5m-.5 4.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm4.5 0V14m0 0l2 1.5");
}

</style>
