<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vn_ttstcs"/><path class="oyntskb9k"/><path clip-rule="evenodd" class="nxtzw_78l"/><path class="aq552ibfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:microwave-duotone" /></template>
<style>
.aq552ibfv {
  d: path("M6 19L6 21M18 19L18 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nxtzw_78l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 9C19 9.5523 18.5523 10 18 10C17.4477 10 17 9.5523 17 9C17 8.4477 17.4477 8 18 8C18.5523 8 19 8.4477 19 9ZM19 13C19 13.5523 18.5523 14 18 14C17.4477 14 17 13.5523 17 13C17 12.4477 17.4477 12 18 12C18.5523 12 19 12.4477 19 13Z");
  stroke: none;
}

.oyntskb9k {
  fill: currentColor;
  d: path("M8 6L12 6C13.6569 6 15 7.3431 15 9L15 13C15 14.6569 13.6569 16 12 16L8 16C6.3431 16 5 14.6569 5 13L5 9C5 7.3431 6.3431 6 8 6Z");
  stroke: none;
}

.vn_ttstcs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L19 2C21.2092 2 23 3.7908 23 6L23 16C23 18.2092 21.2092 20 19 20L5 20C2.7908 20 1 18.2092 1 16L1 6C1 3.7908 2.7908 2 5 2Z");
  stroke: none;
}

</style>
