<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v994gabbg"/><path class="xrkaywbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ssd" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v994gabbg {
  d: path("M5.5 5h13v14h-13Z");
}

.xrkaywbyx {
  d: path("M9 9.5h6v5H9Zm-6.5-1h3m-3 3.5h3m-3 3.5h3m13-7h3m-3 3.5h3m-3 3.5h3");
}

</style>
