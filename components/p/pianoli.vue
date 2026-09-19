<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="xnph78ctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pianoli" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xnph78ctu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.004 19.353l.823-.145l2.87 16.275l-.784.138m1.391-17.026l3.64-.642l2.87 16.275l-3.64.642zm4.689 15.954l1.443 8.179m2.805-25.708l4.99 28.301m.306-29.236l3.64-.641l2.87 16.275l-3.64.641zm7.117-1.255l3.64-.641l2.87 16.275l-3.64.641zm7.117-1.255l3.64-.641l2.87 16.275l-3.64.641zm-2.427 17.209l2.022 11.467m5.095-12.721l1.189 6.746m-15.423-4.237l2.29 12.984m13.62-32.57l-38.31 6.755");
}

</style>
