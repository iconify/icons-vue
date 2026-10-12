<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="naj80kbas"/><path class="razwvsbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:streaming-text" /></template>
<style>
.naj80kbas {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5h7m3.5 0h8m-18.5 6h4m3.25 0h11.25m-18.5 6h5.5");
}

.razwvsbuw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 17.5h.01m3.74 0h.01m3.74 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
