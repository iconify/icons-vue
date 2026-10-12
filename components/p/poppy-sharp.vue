<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vrtb139wf"/><circle class="unmjjutjp"/><path class="c93amcc6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:poppy-sharp" /></template>
<style>
.c93amcc6u {
  d: path("M12 15.25v3.375l2.25 2.625");
}

.unmjjutjp {
  cx: 12px;
  cy: 10px;
  r: 1.75px;
}

.vrtb139wf {
  d: path("M4.25 7.5c1.5-1 3.25-1 4.5 0l.8-2h4.9l.8 2c1.25-1 3-1 4.5 0c0 4.5-3.5 7.75-7.75 7.75S4.25 12 4.25 7.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
