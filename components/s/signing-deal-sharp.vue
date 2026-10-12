<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uln-1ubdi"/><path class="t85_1-bcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:signing-deal-sharp" /></template>
<style>
.t85_1-bcn {
  d: path("m20.6 9.4l1.029 1.05L20.6 11.5l-7 7l-2.85.75l.75-2.85l7-7l1.05-1.029z");
}

.uln-1ubdi {
  d: path("M3.75 2.75h12.5v18.5H3.75zM7 7h5.5M7 10.25h4m-4 7.5h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
