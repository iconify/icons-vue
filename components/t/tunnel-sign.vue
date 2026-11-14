<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a98uvfvvo"/><path class="lb0to798a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tunnel-sign" /></template>
<style>
.a98uvfvvo {
  d: path("M2.5 21v-9a9.5 9.5 0 0 1 19 0v9M2 21h20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lb0to798a {
  d: path("M7 21v-6.5a5 5 0 0 1 10 0V21");
}

</style>
