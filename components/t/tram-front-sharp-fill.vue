<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="hi1bm9b0y"/><path class="sxeocm3lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hi1bm9b0y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 5L20 5C20.5523 5 21 5.4477 21 6L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 6C3 5.4477 3.4477 5 4 5ZM5 7L5 11L19 11L19 7L5 7ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16ZM17 16C17 15.4477 16.5523 15 16 15C15.4477 15 15 15.4477 15 16C15 16.5523 15.4477 17 16 17C16.5523 17 17 16.5523 17 16Z");
  stroke: none;
}

.sxeocm3lm {
  d: path("M7 2L17 2M10 6L12 2L14 6M8 20L6.7236 22.5528M16 20L17.2764 22.5528");
}

</style>
