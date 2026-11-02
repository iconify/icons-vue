<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx-xs2vof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:planet" /></template>
<style>
.dx-xs2vof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 13a7.071 7.071 0 1 1 14-2a7.071 7.071 0 0 1-14 2m0 0c-3.261 2.977-2.339 4.823 2 4c3.87-.734 9.091-3.344 12-6c3.261-2.977 2.339-4.823-2-4");
}

</style>
