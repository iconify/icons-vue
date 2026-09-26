<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dsifhwy8h"/><path class="e97nbxzic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-off-sharp-fill" /></template>
<style>
.dsifhwy8h {
  fill: currentColor;
  d: path("M2.2929 2.2929C2.1054 2.4804 2 2.7348 2 3L2 9L9 9ZM5.6569 2L21 2C21.5523 2 22 2.4477 22 3L22 10L13.6569 10Z");
  stroke: none;
}

.e97nbxzic {
  d: path("M21 21L3 21L3 3M3 9L9 9M3 15L15 15M12 12L12 21M7.6569 3L21 3L21 16.3431M13.6569 9L21 9M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
