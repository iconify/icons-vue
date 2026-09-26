<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wcvpuim8g"/><path class="voi8-8q_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-merge-next-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.voi8-8q_u {
  d: path("M3 3L3 21L21 21L21 3L3 3ZM7 3L7 21M16 3L16 6M16 21L16 18M10 12L17 12M13.7071 8.7071L17 12L13.7071 15.2929");
}

.wcvpuim8g {
  fill: currentColor;
  d: path("M7 3L3 3L3 21L7 21L7 3Z");
  stroke: none;
}

</style>
