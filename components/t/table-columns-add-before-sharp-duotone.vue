<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jbp-1m4ig"/><path class="hruxdcckb"/><path class="jxmxjmbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-add-before-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hruxdcckb {
  fill: currentColor;
  d: path("M12 22L12 2L22 2C22.5523 2 23 2.4477 23 3L23 21C23 21.5523 22.5523 22 22 22L12 22Z");
  stroke: none;
}

.jbp-1m4ig {
  stroke-opacity: 0.4;
  d: path("M4 18L4 21L13 21M13 3L4 3L4 6");
}

.jxmxjmbes {
  d: path("M5 8L5 16M1 12L9 12");
}

</style>
