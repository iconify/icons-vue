<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="cm25e9ila"/><path class="vwrim_bbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:terraforming-sharp" /></template>
<style>
.cm25e9ila {
  cx: 12px;
  cy: 14.5px;
  r: 6.75px;
}

.vwrim_bbv {
  d: path("M5.5 13.25c2-1 4 .5 6.5-.25s4-1.25 6.5-.25m-11 4.75l2.857 1.071L13 17.25m-1-9.5v-2.5m0 0c0-1.75 1.75-2.5 4.25-2.5C16.25 5 14.5 6.5 12 5.25Zm0 0C12 4 10.75 3.5 9 3.5C9 5 10.25 6 12 5.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
