<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j8tg4ubhf"/><circle class="cql1pwtbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tower-pc-sharp" /></template>
<style>
.cql1pwtbp {
  cx: 12px;
  cy: 16px;
  r: 2px;
}

.j8tg4ubhf {
  d: path("M6.25 2.75h11.5v18.5H6.25zm3 3.5h5.5m-5.5 3h5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
