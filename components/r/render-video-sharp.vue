<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e0by60b9x"/><path class="slw_hebtl"/><path class="goe36db5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:render-video-sharp" /></template>
<style>
.e0by60b9x {
  d: path("M2.75 2.75h18.5v13H2.75z");
}

.goe36db5d {
  d: path("M2.75 18h10.5v3.25H2.75z");
}

.slw_hebtl {
  d: path("m10.65 6.88l3.45 1.99l.65.38l-.65.38l-3.45 1.99L10 12V6.5zM2.75 18h18.5v3.25H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
