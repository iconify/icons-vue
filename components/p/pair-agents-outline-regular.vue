<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i2rmxab-a"/><path class="zsn-g1ufa"/><path class="cw_gsq1ee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pair-agents-outline-regular" /></template>
<style>
.cw_gsq1ee {
  d: path("m11 11 2 2");
}

.i2rmxab-a {
  d: path("M8.69 7.37a4 4 0 1 1 -3.38 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zsn-g1ufa {
  d: path("M18.69 9.37a4 4 0 1 1 -3.38 0");
}

</style>
