<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="orjh_bbem"/><circle class="irf-rnz5c"/><path class="jwzz1xbwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:patent-sharp" /></template>
<style>
.irf-rnz5c {
  cx: 16px;
  cy: 16.5px;
  r: 3px;
}

.jwzz1xbwf {
  d: path("m14.5 19.1l-.75 2.15m3.75-2.15l.75 2.15");
}

.orjh_bbem {
  d: path("M4 3h16v13H4zm3 3.5h10m-10 3h6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
