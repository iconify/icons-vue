<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ar9w39b5c"/><path class="rq866kbao"/><path class="f0go6fb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volleyball-rotation" /></template>
<style>
.ar9w39b5c {
  d: path("M7.25 20.25a9.5 9.5 0 1 1 9.5 0m2.75.5l-2.75-.5l1-2.5");
}

.f0go6fb1t {
  d: path("M12 12q-2 2.75 0 5.5m0-5.5q-1.75-3.25-5.25-1.75M12 12q3.25 0 5-2.25");
}

.rq866kbao {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
