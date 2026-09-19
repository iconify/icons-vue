<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6jd1615l"/><path class="qylq1wi-n"/><circle class="j_antjtnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:om-mantra" /></template>
<style>
.d6jd1615l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 29.79c.765 5.544 3.271 12.997 11.7 12.997c4.091 0 7.829-2.384 7.829-6.731s-2.629-7.042-12.066-7.042c0 0 11.09 1.175 11.09-5.9S13.66 17.26 9.624 20.92");
}

.j_antjtnk {
  cx: 28.917px;
  cy: 8.131px;
  r: 2.918px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qylq1wi-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.938 31.195c1.591-.197 3.4.306 5.496-.85s2.998-6.395 6.907-6.395c4.425 0 7.137 3.719 7.159 7.49c.03 5.053-6.916 11.562-12.684 4.944M22.147 9.691c.318 5.306 2.568 7.206 6.717 7.206s6.367-3.439 6.824-7.195");
}

</style>
