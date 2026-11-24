<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb5nz8f_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-round" /></template>
<style>
.wb5nz8f_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M5 21V7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v14m-9 0v-2a2 2 0 1 1 4 0v2M12 6h1.5A1.5 1.5 0 0 1 15 7.5v1.125c0 2.063-1.312 3.375-3 4.125c-1.687-.75-3-2.062-3-4.125V7.5A1.5 1.5 0 0 1 10.5 6z");
}

</style>
