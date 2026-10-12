<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="utiyf1bym"/><path class="kcirip0ot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-size-sharp" /></template>
<style>
.kcirip0ot {
  d: path("m8.75 17.75l5-5m-5 1.5v3.5h3.5m1.5-1.5v-3.5h-3.5");
}

.utiyf1bym {
  d: path("M14.25 2.75h-9v18.5h13.5v-14zm0 0v4.5h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
