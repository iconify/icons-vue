<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="zwb_hob4q"/><path class="jx-dnfdjc"/><circle class="n1yo2g4qm"/><path class="gczibjbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:playdate-sharp" /></template>
<style>
.gczibjbob {
  d: path("M15 21.25v-5.5a3 3 0 0 1 6 0v5.5ZM9 15.5l3 2.5l3-2.5");
}

.jx-dnfdjc {
  d: path("M3 21.25v-5.5a3 3 0 0 1 6 0v5.5Z");
}

.n1yo2g4qm {
  cx: 18px;
  cy: 7.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwb_hob4q {
  cx: 6px;
  cy: 7.75px;
  r: 2px;
}

</style>
