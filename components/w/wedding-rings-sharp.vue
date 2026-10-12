<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="zhj4drbyr"/><circle class="t14991bsq"/><path class="sbflohbdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wedding-rings-sharp" /></template>
<style>
.sbflohbdf {
  d: path("M13.65 4h3.6l.26.31l.73.88l.26.31l-.29.27l-2.67 2.46l-.29.27l-.29-.27l-2.67-2.46L12 5.5l.26-.31l.73-.88l.26-.31z");
}

.t14991bsq {
  cx: 15.25px;
  cy: 14.75px;
  r: 5.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhj4drbyr {
  cx: 8.75px;
  cy: 14.75px;
  r: 5.5px;
}

</style>
