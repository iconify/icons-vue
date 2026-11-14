<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v76ehstsa"/><path class="qxo0bqb2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mercury-barometer" /></template>
<style>
.qxo0bqb2r {
  d: path("M8 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM13.75 6.5h2.5m-2.5 3.5h1.75m-1.75 3.5h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v76ehstsa {
  d: path("M5 2.5h14v19H5Zm5 3v9.25");
}

</style>
