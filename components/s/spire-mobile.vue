<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c42loy4wl"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spire-mobile" /></template>
<style>
.c42loy4wl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.504 19.328l-3.708-3.707m3.708 0l-3.708 3.707m6.214-1.853h-8.72m4.36-6.237v9.829m6.367 5.109l2.6 2.7m-5.3 0v-8h2.6c1.5 0 2.7 1.2 2.7 2.7s-1.2 2.7-2.7 2.7h-2.6m-12.634 2.6v-8h2.6c1.5 0 2.7 1.2 2.7 2.7s-1.2 2.7-2.7 2.7h-2.6m20.4-5.4v8m0-4h2.6m-2.6-4h4m-4 8h4m-32.066-.9c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2s-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2s.9-2 2-2h1.2c.9 0 1.5.2 2 .9m11.533-.9v8m-1.2-8h2.4m-2.4 8h2.4");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
