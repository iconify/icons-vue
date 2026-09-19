<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="f-xxyzb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ruleofthree" /></template>
<style>
.f-xxyzb5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.56 20.91V11.5h3.08a3.16 3.16 0 0 1 0 6.32h-3.08m3.08 0l3.07 3.08m5.99-6.67l1.06-1.97l1.06 1.97m-4 5.5h5.88m-5.88-3.53h5.88m8.74 1a2.35 2.35 0 0 0-2.35-2.35h0a2.35 2.35 0 0 0-2.35 2.35h0v1.53a2.35 2.35 0 0 0 2.35 2.35h0a2.35 2.35 0 0 0 2.35-2.35m0 2.35v-9.4m0 18.59l-4.7 6.23m4.7 0l-4.7-6.23m-18.95-1.94v7a1.18 1.18 0 0 0 1.19 1.17h.37m-2.79-6.23h2.47m9.67-.62l1.06-1.97l1.06 1.97m-4 5.5h5.88m-5.88-3.53h5.88");
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
