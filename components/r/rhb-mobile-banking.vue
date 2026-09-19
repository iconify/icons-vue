<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3cd3fbja"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rhb-mobile-banking" /></template>
<style>
.j3cd3fbja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.84 20.34L38.5 24l-3.66 3.66L31.178 24zM9.5 27.821l1.348-7.642h2.502c1.414 0 2.358 1.149 2.108 2.567s-1.599 2.566-3.014 2.566H9.942m2.502 0l2.06 2.507m3.255-7.64l-1.348 7.642m6.411-7.642l-1.348 7.642m-4.386-3.835h5.063m5.18.014c1.055 0 1.76.855 1.574 1.91s-1.192 1.911-2.248 1.911h-3.152l1.348-7.642h3.152c1.055 0 1.76.855 1.574 1.91S28.386 24 27.33 24m.001 0h-3.152");
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
