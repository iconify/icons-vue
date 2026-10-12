<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ial4aybya"/><path class="qyijb1p8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:substation-sharp" /></template>
<style>
.ial4aybya {
  d: path("M2.75 8.75h18.5v12.5H2.75zm4.25 0v-5.5m5 5.5v-5.5m5 5.5v-5.5m-11.5 2h3m2 0h3m2 0h3");
}

.qyijb1p8k {
  d: path("M13 11.75L10.75 15h3l-2.25 3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
