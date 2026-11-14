<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aci5dk8-f"/><path class="tkf29dbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-bottle" /></template>
<style>
.aci5dk8-f {
  d: path("M10.25 2.5h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 8.5 4.75v-.5a1.75 1.75 0 0 1 1.75-1.75m.125 4h1.25A4.375 4.375 0 0 1 16 10.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-1.25A4.375 4.375 0 0 1 6 17.125v-6.25A4.375 4.375 0 0 1 10.375 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tkf29dbxd {
  d: path("M10.5 10h1a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 10.5 10m-1.75 4.5h4.5m3.25-10h.01m2.99-1.75A3.5 3.5 0 0 1 19 7");
}

</style>
