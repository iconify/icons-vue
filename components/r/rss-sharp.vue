<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lcrgqjboq"/><path class="f227tzxrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rss-sharp" /></template>
<style>
.f227tzxrz {
  fill: currentColor;
  d: path("M5 20.5C5 21.3284 4.3284 22 3.5 22C2.6716 22 2 21.3284 2 20.5C2 19.6716 2.6716 19 3.5 19C4.3284 19 5 19.6716 5 20.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lcrgqjboq {
  d: path("M2 3L3 3C12.9411 3 21 11.0589 21 21L21 22M2 9L3 9C9.6274 9 15 14.3726 15 21L15 22M2 15L3 15C6.3137 15 9 17.6863 9 21L9 22");
}

</style>
