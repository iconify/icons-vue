<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="y434a_rgu"/><circle class="mhp88xbvt"/><circle class="rcdjtibgl"/><path class="zomn2g99y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meteor-shower-sharp" /></template>
<style>
.mhp88xbvt {
  cx: 15.25px;
  cy: 17.25px;
  r: 1.5px;
}

.rcdjtibgl {
  cx: 10.75px;
  cy: 8.75px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y434a_rgu {
  cx: 5.75px;
  cy: 18.25px;
  r: 2.5px;
}

.zomn2g99y {
  d: path("m8.5 15.5l6-6m2.25 6.25l4.5-4.5m-9-4l4.5-4.5");
}

</style>
