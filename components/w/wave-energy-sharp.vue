<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n6pky70hz"/><path class="l8jwf5bvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wave-energy-sharp" /></template>
<style>
.l8jwf5bvo {
  d: path("m12.75 5.5l-2 3h2.5l-2 3m-8.5 4.75l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2m-18.48 4l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2l1.54-2l1.54 2l1.54 2l1.54-2");
}

.n6pky70hz {
  d: path("M8.25 2.75h7.5v11h-7.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
