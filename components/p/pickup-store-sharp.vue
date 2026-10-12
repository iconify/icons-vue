<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eyd_ny5wt"/><path class="j1e474bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pickup-store-sharp" /></template>
<style>
.eyd_ny5wt {
  d: path("M5.4 2.75h13.2l1.034.002l.366.968l1.25 2.03v2.5H2.75v-2.5L4 3.72l.366-.968zm3.85 0l-.5 5.5m6-5.5l.5 5.5m-10.5 2.5h14.5v10.5H4.75v-2Z");
}

.j1e474bsh {
  d: path("M9.75 13.75h4.5v4.5h-4.5zm2.25 0v1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
