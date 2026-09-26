<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u-th1gbxa"/><path class="ep3aj1k1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-off-sharp" /></template>
<style>
.ep3aj1k1d {
  d: path("M6.5 10L9.5 10C9.7761 10 10 10.2239 10 10.5L10 13.5C10 13.7761 9.7761 14 9.5 14L6.5 14C6.2239 14 6 13.7761 6 13.5L6 10.5C6 10.2239 6.2239 10 6.5 10Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u-th1gbxa {
  d: path("M2.5 6L21.5 6C21.7761 6 22 6.2239 22 6.5L22 17.5C22 17.7761 21.7761 18 21.5 18L2.5 18C2.2239 18 2 17.7761 2 17.5L2 6.5C2 6.2239 2.2239 6 2.5 6Z");
}

</style>
