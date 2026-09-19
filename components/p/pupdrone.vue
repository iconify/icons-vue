<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_7qtebtq"/><path class="e6o5j0bpm"/><path class="qj2vt4s7i"/><path class="ewaksibqq"/><path class="nrfodsbph"/><circle class="hj3rx83ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pupdrone" /></template>
<style>
.e_7qtebtq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.011c-6.016 0-10.893 4.779-10.893 10.795m6.679 17.013c-1.535-.611-3.041-1.768-3.83-2.73l-.738-5.313c.767 1.482 1.837 2.76 3.115 3.895l2.08-.368s1.002-.46 3.587-.46m-2.753 4.976h-1.461");
}

.e6o5j0bpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.426 29.513L6.667 6.861l1.191-.68l5.249 18.625l1.408 1.475l.703 7.495z");
}

.ewaksibqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.574 29.513l3.759-22.652l-1.191-.68l-5.249 18.625l-1.408 1.475l-.703 7.495z");
}

.hj3rx83ce {
  cx: 24px;
  cy: 25.552px;
  r: 4.352px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nrfodsbph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.893 24.547c.653-12.033 1.171-15.44-2.285-16.592c-2.72-.906-5.303 4.063-6.26 5.892m1.238 23.456l-.833 4.516H24m8.043-2.73L42.5 20.997l-.294-3.136l-3.661 5.797");
}

.qj2vt4s7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.107 24.547c-.653-12.033-1.171-15.44 2.285-16.592c2.72-.906 5.303 4.063 6.26 5.892m-1.238 23.456l.833 4.516H24m-8.043-2.73L5.5 20.997l.294-3.136l3.661 5.797M24 14.011c6.017 0 10.893 4.779 10.893 10.795m-6.679 17.013c1.535-.611 3.041-1.768 3.83-2.73l.738-5.313c-.767 1.482-1.837 2.76-3.115 3.895l-2.08-.368s-1.002-.46-3.587-.46m2.753 4.976h1.461");
}

</style>
