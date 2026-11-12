<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqhdvabpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-round" /></template>
<style>
.uqhdvabpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm13.5 5v2.156a1 1 0 0 1-.557.897l-3.5 1.728a1 1 0 0 1-.886 0l-3.5-1.728a1 1 0 0 1-.557-.897V9.844a1 1 0 0 1 .557-.897l3.5-1.728a1 1 0 0 1 .886 0l3.5 1.728a1 1 0 0 1 .557.897zM7.66 9.301L12 11.444l4.34-2.143M12 11.444v5.44");
}

</style>
