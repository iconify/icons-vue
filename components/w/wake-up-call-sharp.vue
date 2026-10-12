<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="owcfk0-vx"/><path class="aiuf2ebyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wake-up-call-sharp" /></template>
<style>
.aiuf2ebyl {
  d: path("m6.75 19.5l-1.5 1.75m12-1.75l1.5 1.75M3.5 6.5l3.25-2.75M20.5 6.5l-3.25-2.75M12 16.25V9.5M9.5 12L12 9.5l2.5 2.5");
}

.owcfk0-vx {
  cx: 12px;
  cy: 12.75px;
  r: 7.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
