<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psdn28zbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-sands" /></template>
<style>
.psdn28zbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.43 17H2.5C4.5 9.5 8 4.5 12 4.5c2.335 0 4.499 1.703 6.294 4.613M9 9.5h6m-8 4h6.5M18 13c1.5 1.75 3 3.5 3 5.5a3 3 0 0 1-6 0c0-2 1.5-3.75 3-5.5Z");
}

</style>
