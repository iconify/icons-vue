<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="umern85ks"/><path class="nrt-tdl2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-dashed-quarter-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrt-tdl2l {
  fill: currentColor;
  d: path("M12 6L15.5 6C16.8807 6 18 7.1193 18 8.5L18 12C18 12.5523 17.5523 13 17 13L12 13C11.4477 13 11 12.5523 11 12L11 7C11 6.4477 11.4477 6 12 6Z");
  stroke: none;
}

.umern85ks {
  stroke-opacity: 0.4;
  d: path("M3 6C3 4.3431 4.3431 3 6 3M10.5 3L13.5 3M18 3C19.6569 3 21 4.3431 21 6M21 10.5L21 13.5M21 18C21 19.6569 19.6569 21 18 21M13.5 21L10.5 21M6 21C4.3431 21 3 19.6569 3 18M3 13.5L3 10.5");
}

</style>
