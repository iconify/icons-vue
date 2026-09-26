<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kjzly26zd"/><path class="ep3aj1k1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-off-sharp-duotone" /></template>
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

.kjzly26zd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.5 5L21.5 5C22.3284 5 23 5.6716 23 6.5L23 17.5C23 18.3284 22.3284 19 21.5 19L2.5 19C1.6716 19 1 18.3284 1 17.5L1 6.5C1 5.6716 1.6716 5 2.5 5Z");
  stroke: none;
}

</style>
