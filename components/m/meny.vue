<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1ve4t1vr"/><path class="w4i5-qinh"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meny" /></template>
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

.m1ve4t1vr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.365 29.509V11.5L24 27.02l11.635-15.485v18M13.722 36.5l-1.357-4.325q1.82 1.096 3.439 2.35a37 37 0 0 1 2.015-3.63l.72 4.473m6.681-.415l.162-4.535a36 36 0 0 1 3.513 4.864l.647-4.492m6.093 1.385a36 36 0 0 0-2.588 1.623a37 37 0 0 0-1.487-2.663m.927 4.861l.56-2.199m-12.775-.945a37 37 0 0 1 1.93-.146");
}

.w4i5-qinh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.281 34.939q-1.391.029-2.778.17l-.462-4.514a39 39 0 0 1 3.145-.194");
}

</style>
