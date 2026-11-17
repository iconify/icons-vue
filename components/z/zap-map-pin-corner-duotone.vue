<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="va39t9byk"/><path class="zq0y0coca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-map-pin-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.va39t9byk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.75 10H17a6 6 0 0 0-5.886 4.834l-.676 3.416l-1.565 1.967A.35.35 0 0 1 8.25 20v-5a1 1 0 0 0-1-1H4a.481.481 0 0 1-.377-.783l7.504-9.434A.35.35 0 0 1 11.75 4v5a1 1 0 0 0 1 1M17 21c-1.574-1.051-2.999-3.053-3-5a3 3 0 1 1 6 0c-.001 1.947-1.426 3.949-3 5");
}

.zq0y0coca {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 10h-4.25a1 1 0 0 1-1-1V4a.35.35 0 0 0-.623-.217l-7.504 9.434A.482.482 0 0 0 4 14h3.25a1 1 0 0 1 1 1v5c0 .33.417.476.623.217l1.565-1.967M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

</style>
