<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="le0fy-b5p"/><ellipse transform="rotate(-76.639 20.488 29.348)" class="g0dbw0ble"/><ellipse transform="rotate(-56.648 14.43 25.511)" class="bj_qctboa"/><ellipse transform="rotate(-72.324 27.434 29.672)" class="anq-w4r3y"/><path class="m8maisbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:peridot" /></template>
<style>
.anq-w4r3y {
  cx: 27.433px;
  cy: 29.672px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.842px;
  ry: 0.996px;
}

.bj_qctboa {
  cx: 14.429px;
  cy: 25.511px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.763px;
  ry: 1.096px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g0dbw0ble {
  cx: 20.488px;
  cy: 29.348px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.548px;
  ry: 10.126px;
}

.le0fy-b5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.479 4.26c2.652 3.985 3.32 8.615 3.458 13.418c4.767-.093 6.82.716 9.922 2.96c3.26-4.382 7.978-7.214 12.666-9.093M9.21 8.396c.02 3.453.596 6.786 1.971 9.945c-1.876-1.386-3.88-2.643-6.918-2.868m-.847 2.319c1.186 4.74 3.71 4.802 5.887 6.073c-3.7 5.65.987 12.022.041 15.866m34.843-23.13c-2.85 3.89-6.056 7.394-10.312 9.76c3.693-.333 8.47 1.819 8.15 2.719c-1.598 4.42-6.678 3.32-9.763 2.762l-.575 3.447c-.494 1.456.036 2.318.641 3.138l3.285 3.667");
}

.m8maisbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.406 11.969c1.193-.543 2.643-.474 3.438-2.469S27.568 5.055 24 7.313c-.687-1.052-1.509-3.279-2.844-.907s.93 3.943 2.25 5.563");
}

</style>
