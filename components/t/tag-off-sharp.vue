<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lb_q9xb4s"/><circle class="ygzhjxbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag-off-sharp" /></template>
<style>
.lb_q9xb4s {
  d: path("M3.75 5.75v-2h7.4l.827.003l.583.587l7.6 7.6l1.402 1.41l-1.402 1.41l-5.43 5.43l-1.41 1.402l-1.41-1.402l-7.6-7.6l-.569-.59l.009-.82Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygzhjxbkl {
  cx: 8px;
  cy: 8px;
  r: 1.25px;
}

</style>
