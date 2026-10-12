<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k6z_f_pgj"/><path class="ssjiujxrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-barrel-sharp" /></template>
<style>
.k6z_f_pgj {
  d: path("M5.5 2.75H19v2h-1v14.5h1v2H5v-2h1V4.75H5v-2zM6 9h12M6 15h12");
}

.ssjiujxrh {
  d: path("m12 10.9l1 1.133v.367a1 1 0 0 1-2 0v-.367z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
