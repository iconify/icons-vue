<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o6ord-b7v"/><path class="sd3z3ub6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:veterinary-farm-sharp" /></template>
<style>
.o6ord-b7v {
  d: path("M2.75 20.45V9.5l.65-.46l7.95-5.58L12 3l.65.46l7.95 5.58l.65.46v11.75H2.75z");
}

.sd3z3ub6g {
  d: path("M10.75 10.5h2.5v3h3V16h-3v3h-2.5v-3h-3v-2.5h3Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
