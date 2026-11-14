<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x-xvdcc7d"/><path class="k_cro8zpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piston-cylinder" /></template>
<style>
.k_cro8zpl {
  d: path("M5 11h14v3H5Zm3.5-8.5h7m-3.5 0V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-xvdcc7d {
  d: path("M5 5v14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V5");
}

</style>
