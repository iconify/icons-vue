<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ip5sj4lkj"/><path class="ove7tbb-c"/><path class="o_etmpmtn"/><path class="zstm81mgb"/><circle class="hcz1ribid"/><path class="c8g8jxb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocket-city-2" /></template>
<style>
.c8g8jxb9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.852 36.649c0-.75.703-1.36 1.499-1.219c.515.094.938.563.984 1.077c.047.376-.093.798-.375 1.032c-.515.422-2.108 1.639-2.108 1.639h2.483");
}

.hcz1ribid {
  cx: 37.099px;
  cy: 37.295px;
  r: 3.866px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ip5sj4lkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.601 39.185l-9.606 5.078L5.99 33.965l-.055-20.428l18.06-10.274l18.086 10.34l.089 21.054l-1.377.728");
}

.o_etmpmtn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.125 24.13l-15.25 7.717l-3.645-4.675l-4.5.518m8.145 4.157v10.894M14.643 8.583l.1 8.709m12.344 5.362v-8.242L15.827 7.91m11.26 6.5l8.488-4.528m.98.561l.04 8.43M10.148 32.117l1.898 1.096V30.61l-1.978-1.142zm3.459 1.9l1.9 1.097V32.51l-1.98-1.143zm-3.459-6.015l1.898 1.098v-2.605l-1.978-1.142z");
}

.ove7tbb-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.73 41.251V27.479l7.307-3.891l-13.073-7.323l-7.011 4.049m0-.002L18.73 27.69m7.306-4.104l5.697-2.93l6.398-2.344l3.99 4.866");
}

.zstm81mgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.607 29.903l1.9 1.098v-2.604l-1.98-1.142zm5.013-14.258l1.899 1.097v-2.605l-1.979-1.142zm3.46 1.901l1.899 1.097v-2.604l-1.98-1.142zm.073 20.782l1.899 1.097v-2.603l-1.979-1.143zm0-4.113l1.899 1.097v-2.604l-1.979-1.142z");
}

</style>
