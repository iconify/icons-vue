<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b9pu7bb3q"/><circle class="pf8xrvdha"/><circle class="kp330nbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scholarship-sharp" /></template>
<style>
.b9pu7bb3q {
  d: path("m11.4 3.69l5.95 2.87l.9.44l-.9.44l-5.95 2.87l-.9.44l-.9-.44l-5.95-2.87l-.9-.44l.9-.44L9.6 3.69l.9-.44zM6.25 9v3.5l1.5 1.5h2.75");
}

.kp330nbbl {
  cx: 16.75px;
  cy: 16.5px;
  r: 2px;
}

.pf8xrvdha {
  cx: 16.75px;
  cy: 16.5px;
  r: 4.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
