<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zpusgabfl"/><path class="j6bzvl3dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-check-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j6bzvl3dj {
  d: path("M14.7071 17.7071L17 20L21.2929 15.7071");
}

.zpusgabfl {
  stroke-opacity: 0.4;
  d: path("M20.7987 12.9196C20.3521 11.7628 19.24 11 18 11L17 11L17 7L13 7L13 6C13 4.3431 11.6569 3 10 3C8.3431 3 7 4.3431 7 6L7 7L3 7L3 11L4 11C5.6569 11 7 12.3431 7 14C7 15.6569 5.6569 17 4 17L3 17L3 21L13.3431 21");
}

</style>
