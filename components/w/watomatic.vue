<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xvvtoob8v"/><circle class="re1fihb5w"/><circle class="i9awgxbqy"/><path class="oxwmpuydr"/><circle class="rhj6jyb9q"/><circle class="ltsfiackk"/><path class="v3-e-6vjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:watomatic" /></template>
<style>
.i9awgxbqy {
  cx: 16.3px;
  cy: 21.43px;
  r: 3.81px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ltsfiackk {
  cx: 33.41px;
  cy: 21.43px;
  r: 3.81px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oxwmpuydr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.31 12.9l1.75-2.65");
}

.re1fihb5w {
  cx: 12.26px;
  cy: 8.07px;
  r: 2.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rhj6jyb9q {
  cx: 37.44px;
  cy: 8.07px;
  r: 2.57px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v3-e-6vjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.85 10.65c-10 0-18.17 6.88-18.17 15.36a14.21 14.21 0 0 0 5.24 10.79a10.3 10.3 0 0 1-1.56 3.3a11.4 11.4 0 0 1-2.93 2.4a15.44 15.44 0 0 0 9.24-2.79a20.8 20.8 0 0 0 8.18 1.66C34.89 41.37 43 34.49 43 26s-8.11-15.35-18.15-15.35");
}

.xvvtoob8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.4 12.9l-1.76-2.65");
}

</style>
