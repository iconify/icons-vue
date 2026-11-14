<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a98uvfvvo"/><path class="lb0to798a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tunnel-sign" /></template>
<style>
.a98uvfvvo {
  d: path("M2.5 21v-9a9.5 9.5 0 0 1 19 0v9M2 21h20");
}

.lb0to798a {
  d: path("M7 21v-6.5a5 5 0 0 1 10 0V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
