<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_4qxf69v"/><circle class="cdpnrbctu"/><circle class="f5wwnvb2i"/><circle class="dpaws1mxl"/><circle class="qq4gsseeq"/><circle class="a4sbaq0gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:namma-metro" /></template>
<style>
.a4sbaq0gd {
  cx: 14.601px;
  cy: 37.115px;
  r: 0.75px;
  fill: currentColor;
}

.cdpnrbctu {
  cx: 33.107px;
  cy: 30.497px;
  r: 0.75px;
  fill: currentColor;
}

.dpaws1mxl {
  cx: 13.366px;
  cy: 17.599px;
  r: 0.75px;
  fill: currentColor;
}

.f5wwnvb2i {
  cx: 31.928px;
  cy: 9.88px;
  r: 0.75px;
  fill: currentColor;
}

.qq4gsseeq {
  cx: 23.444px;
  cy: 24.216px;
  r: 0.75px;
  fill: currentColor;
}

.w_4qxf69v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.322 26.814c.173 6.639-3.251 17.889-7.907 16.584c-3.281-.92-4.013-5.148 2.483-10.852c5.74-5.039 14.514-6.75 19.219-5.486c4.357 1.21 6.47 4.562 3.908 7.332c-3.568 3.857-11.017-2.667-11.384-11.216c-.292-6.797.716-10.318 2.577-14.375c2.2-4.794 6.253-5.579 7.391-2.374c1.347 3.792-3.387 8.718-6.277 10.717c-10.23 7.076-22.049 5.453-21.444-.133c.458-4.225 5.07-5.728 8.366-1.2c3.177 4.364 2.965 7.052 3.068 11.003");
}

</style>
