<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ryb7okb7p"/><path class="tmoc49buu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-add-after-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ryb7okb7p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3L11 21L2 21L2 3L11 3Z");
  stroke: none;
}

.tmoc49buu {
  d: path("M20 6L20 3L2 3L2 21L20 21L20 18M11 3L11 21M19 8L19 16M15 12L23 12");
}

</style>
