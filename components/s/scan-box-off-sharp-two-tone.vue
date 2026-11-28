<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nijyy3-gm"/><path class="vyytujbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nijyy3-gm {
  stroke-opacity: 0.4;
  d: path("M3 9L3 3M21 21L15 21M9 21L3 21L3 15M15 3L21 3L21 9M12.3751 7.1818L17 9.4239L17 12.3431");
}

.vyytujbap {
  d: path("M7 9.4239L12 12M12 12L12 17L7 14.5761L7 9.4239L8.6327 8.6327M1.7071 1.7071L22.2929 22.2929");
}

</style>
