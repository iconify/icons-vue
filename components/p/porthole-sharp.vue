<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="z7cipe4vz"/><path class="u9jz2fb9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:porthole-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.u9jz2fb9j {
  d: path("M9 12V9h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7cipe4vz {
  d: path("M12 6a6 6 0 1 0 0 12a6 6 0 1 0 0-12Zm7.07 8.93h.01m-4.15 4.14h.01m-5.87 0h.01m-4.15-4.14h.01m-.01-5.86h.01m4.13-4.14h.01m5.85 0h.01m4.13 4.14h.01");
}

</style>
