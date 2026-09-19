<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="foos7m7zt"/><path class="dfp5nhnbq"/><path class="qk8a5pbqy"/><path class="vh7uasb-e"/><path class="mpjl0bb7j"/><path class="m-o4ffbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reigns-got" /></template>
<style>
.dfp5nhnbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.535 43.5l-11.289-4.894l-2.509-25.372l5.55-7.138L21.535 4.5m-4.704 17.276v5.702m9.408-5.702v5.702");
}

.foos7m7zt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.535 9.917l-9.54 4.314l-1.141 14.149l1.597 7.299l9.084 5.008");
}

.m-o4ffbwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.535 32.553h2.281l2.594 2.68l.466 2.51");
}

.mpjl0bb7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.535 43.5l11.29-4.894l2.509-25.372l-5.55-7.138L21.535 4.5");
}

.qk8a5pbqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.535 32.553h-2.28l-2.595 2.68l-.465 2.51");
}

.vh7uasb-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.535 9.917l9.541 4.314l1.141 14.149l-1.597 7.299l-9.085 5.008");
}

</style>
