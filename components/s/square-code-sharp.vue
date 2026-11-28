<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="vykqzprfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-code-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vykqzprfo {
  d: path("M10.2993 8.1508L7 12L10.2993 15.8492M13.7007 8.1508L17 12L13.7007 15.8492");
}

.x-_5ilohg {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

</style>
