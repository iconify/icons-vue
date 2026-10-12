<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="adco1qhux"/><path class="lqht54k1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parking-garage-sharp" /></template>
<style>
.adco1qhux {
  d: path("M2.75 11.25h18.5v10H2.75zm0 3.5h18.5m-18.5 3.5h18.5m-7.5-15h7.5v8h-7.5z");
}

.lqht54k1u {
  d: path("M16.25 9V5.5H19V8h-2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
