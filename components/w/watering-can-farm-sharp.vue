<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ojktosbww"/><path class="yxfbobc_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watering-can-farm-sharp" /></template>
<style>
.ojktosbww {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h11v12.25H3zm0 3.5h11M5.5 9V5.25h6V9m2.5 8l4.5-4.5m-.25-.55l-.75-1.65l-.25-.55l.54.27l2.92 1.46l.54.27l-.58.16l-1.59.43l-.58.16z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yxfbobc_y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14.75h.01m-1.51 3h.01");
}

</style>
