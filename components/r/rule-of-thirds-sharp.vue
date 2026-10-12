<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="al-4xrb9u"/><circle class="zmwlfxb5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rule-of-thirds-sharp" /></template>
<style>
.al-4xrb9u {
  d: path("M3 4h18v16H3zm6 0v2.5M15 20v-2.5M3 9.33h2.5M21 14.67h-2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmwlfxb5f {
  cx: 15px;
  cy: 9.33px;
  r: 1.25px;
}

</style>
