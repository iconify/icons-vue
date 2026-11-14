<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5ibgokwp"/><path class="ejkj6th1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ratings-share" /></template>
<style>
.ejkj6th1k {
  d: path("M16.25 15.5h4.25v4.25");
}

.s5ibgokwp {
  d: path("M13.6 18.5H2.5V5h19v7.7M9 2.5L12 5l3-2.5m-9 13V12m3 3.5V8m3 7.5v-5M15 21l5.25-5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
