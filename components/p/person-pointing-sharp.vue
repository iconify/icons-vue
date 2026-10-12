<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v-2iygbgq"/><path class="si1-9ewop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-pointing-sharp" /></template>
<style>
.si1-9ewop {
  d: path("M7 9.5v6.25m-2 5.5l2-5.5l2 5.5m-2-10l-2.5 3m2.5-3h10.75m-2-2l2 2l-2 2");
}

.v-2iygbgq {
  cx: 7px;
  cy: 4.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
