<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iq0egqbir"/><path class="tssdqrzjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iq0egqbir {
  d: path("M18.9999 15L21.9999 12L18.9999 9M21.9999 12L14.9999 12M4.99994 9L1.99994 12L4.99994 15M1.99994 12L8.99994 12");
}

.tssdqrzjz {
  d: path("M9.00025 5L12.0002 2L15.0002 5M12.0002 2L12.0002 9M15.0002 19L12.0002 22L9.00025 19M12.0002 22L12.0002 15");
}

</style>
