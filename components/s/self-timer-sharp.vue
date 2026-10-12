<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mi9ranbji"/><path class="aidy_acxp"/><circle class="d4da7x21x"/><path class="exv899b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:self-timer-sharp" /></template>
<style>
.aidy_acxp {
  d: path("M12.75 10.25a2.75 2.75 0 1 1-5.5 0a2.75 2.75 0 1 1 5.5 0");
}

.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.exv899b0n {
  d: path("M16.75 14.75v2l1.25 1");
}

.mi9ranbji {
  d: path("M2.75 4.75h15v11h-15z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
