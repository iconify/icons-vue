<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e_h7owgjl"/><path class="ryr12639v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mooring-bollard-sharp" /></template>
<style>
.e_h7owgjl {
  d: path("M5.5 8.25a6.5 4.5 0 0 1 13 0Zm3.25 0h6.5V18.5h-6.5zM5.5 18.5h13v2.75h-13z");
}

.ryr12639v {
  d: path("M2.75 15.5c2.75 0 3.75-3 9.25-3s6.5 3 9.25 3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
