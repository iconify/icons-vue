<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="flgrwlbus"/><path class="ah4s37bgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tubes-sharp-fill" /></template>
<style>
.ah4s37bgk {
  d: path("M1 2L11 2M13 2L23 2");
}

.flgrwlbus {
  fill: currentColor;
  d: path("M3 1L9 1C9.5523 1 10 1.4477 10 2L10 19C10 21.2091 8.2091 23 6 23C3.7909 23 2 21.2091 2 19L2 2C2 1.4477 2.4477 1 3 1ZM4 3L4 12L8 12L8 3L4 3ZM15 1L21 1C21.5523 1 22 1.4477 22 2L22 19C22 21.2091 20.2091 23 18 23C15.7909 23 14 21.2091 14 19L14 2C14 1.4477 14.4477 1 15 1ZM16 3L16 15L20 15L20 3L16 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
