<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><path class="fhjoyp32r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:settlement-check-sharp" /></template>
<style>
.fhjoyp32r {
  d: path("m14.5 10.5l1.25 1.25l2.75-3M6 9h4.5M6 12h4.5M6 15.5h12");
}

.hmz588b6d {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
