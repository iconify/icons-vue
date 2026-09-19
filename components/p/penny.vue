<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vid6subrd"/><path class="dcxcqtwoj"/><circle class="w700fh2-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:penny" /></template>
<style>
.dcxcqtwoj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.841 16.69h2.785a3.575 3.575 0 1 1-.835 7.101h-2.785z");
}

.vid6subrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.234 8.336h15.594c6.46.538 11.26 6.211 10.722 12.67c-.539 6.46-6.211 11.26-12.67 10.722h-5.988l-1.67 7.936H4.5z");
}

.w700fh2-l {
  cx: 37.931px;
  cy: 34.095px;
  r: 5.569px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
