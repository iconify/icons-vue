<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5cjz1qmx"/><path class="rw1m9r3on"/><path class="en-5jcbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:okta-verify" /></template>
<style>
.en-5jcbva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.336 10.024L24 26.36l-4.72-4.72");
}

.rw1m9r3on {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.699 19.775a11.513 11.513 0 1 1-1.473-2.641");
}

.x5cjz1qmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.013 12.257a21.53 21.53 0 1 1-1.676-2.234");
}

</style>
