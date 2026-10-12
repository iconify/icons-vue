<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="on9eecb6j"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:octagon" /></template>
<style>
.on9eecb6j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 17.06L17.06 20q-1.23 1.24-2.98 1.24H9.92q-1.75 0-2.98-1.24L4 17.06q-1.24-1.23-1.24-2.98V9.92q0-1.75 1.24-2.98L6.94 4q1.23-1.24 2.98-1.24h4.16q1.75 0 2.98 1.24L20 6.94q1.24 1.23 1.24 2.98v4.16q0 1.75-1.24 2.98");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
