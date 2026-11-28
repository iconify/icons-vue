<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="op4ug9rud"/><path class="o0ubd-spe"/><path class="vtb1sfk9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-braces-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0ubd-spe {
  d: path("M3 3H21V21H3V3Z");
}

.op4ug9rud {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2H21C21.552 2 22 2.448 22 3V21C22 21.552 21.552 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2Z");
  stroke: none;
}

.vtb1sfk9d {
  d: path("M11 7H9V11L8 12L9 13V17H11M13 7H15V11L16 12L15 13V17H13");
}

</style>
