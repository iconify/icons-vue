<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d4ss5kb_g"/><path class="z_cim1mez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trophy-sharp" /></template>
<style>
.d4ss5kb_g {
  d: path("M6.75 3.25h10.5v5.5a5.25 5.25 0 0 1-10.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_cim1mez {
  d: path("M6.75 5.25h-3.5v2c0 2.25 1.75 3.75 4.25 4m9.75-6h3.5v2c0 2.25-1.75 3.75-4.25 4M12 14v4m-4.75 0h9.5v3.25h-9.5z");
}

</style>
