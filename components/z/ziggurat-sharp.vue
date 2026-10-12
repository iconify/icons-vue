<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gc1u27bek"/><path class="uxxy73ggi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ziggurat-sharp" /></template>
<style>
.gc1u27bek {
  d: path("M2.75 20.75V17H5v-4.25h2.5V8.5h2.25v-4h4.5v4h2.25v4.25H19V17h2.25v4.25H2.75z");
}

.uxxy73ggi {
  d: path("M10.25 9.5h3.5v11.75h-3.5zm0 3.5h3.5m-3.5 3.75h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
