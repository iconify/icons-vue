<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o_vcm4blu"/><path class="d_ephhhcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timer-reset-sharp" /></template>
<style>
.d_ephhhcf {
  d: path("M11.5 13.5V9.25h4.25v4.25Zm4.5 5a2.5 2.5 0 1 0 2.5-2.5m1.25-1.25L18.5 16l1.25 1.25");
}

.o_vcm4blu {
  d: path("M12.93 20.86a7.5 7.5 0 1 1 5.81-9.3M9.25 2.75h4.5m-2.25 0V6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
