<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i24gwqugx"/><rect class="amg-3hanv"/><path class="bovrh_b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-chat" /></template>
<style>
.amg-3hanv {
  width: 6.5px;
  height: 5px;
  x: 8.75px;
  y: 9.75px;
  rx: 1.25px;
}

.bovrh_b-g {
  d: path("M10.25 9.75v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i24gwqugx {
  d: path("M4.75 3.75h14.5a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2H10l-4.5 3.5v-3.5h-.75a2 2 0 0 1-2-2v-9.5a2 2 0 0 1 2-2");
}

</style>
