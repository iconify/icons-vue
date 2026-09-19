<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlwzy6bgj"/><path class="qfjr6cc_h"/><path class="qw_4l8bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qcc" /></template>
<style>
.nlwzy6bgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.122 33.123c-5.037 5.038-13.206 5.038-18.243 0s-5.037-13.206 0-18.243c5.038-5.038 13.206-5.038 18.243 0");
}

.qfjr6cc_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.041 27.042a4.3 4.3 0 1 1 0-6.081");
}

.qw_4l8bha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.763 43.764l-4.56-4.561c-8.139 8.138-21.243 8.424-29.729.649C.99 32.076.132 18.997 7.53 10.18S27.957-.063 37.088 6.944s11.125 19.96 4.523 29.389");
}

</style>
