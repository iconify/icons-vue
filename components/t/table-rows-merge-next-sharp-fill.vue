<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j87__hkea"/><path class="a4bzgtbjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-merge-next-sharp-fill" /></template>
<style>
.a4bzgtbjt {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM3 7L21 7M3 16L6 16M21 16L18 16M12 10L12 17M8.7071 13.7071L12 17L15.2929 13.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j87__hkea {
  fill: currentColor;
  d: path("M3 7L3 3L21 3L21 7L3 7Z");
  stroke: none;
}

</style>
