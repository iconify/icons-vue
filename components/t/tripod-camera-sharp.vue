<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sylvd6bbm"/><path class="o6a500beq"/><path class="mhy96tb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tripod-camera-sharp" /></template>
<style>
.mhy96tb9g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v3m0 0l-6.5 9m6.5-9l6.5 9m-6.5-9v9");
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.sylvd6bbm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h10.5v6.5H6.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
