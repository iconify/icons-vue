<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-n6il1vd"/><ellipse class="ygw9j1bgu"/><path class="amagwlz_u"/><path class="dhbvngb2r"/><circle class="sd58tcc2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vouille79" /></template>
<style>
.amagwlz_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.826 20.522c.283.357.715.603 1.43.603h.12c.939 0 1.7-.734 1.7-1.64v-1.67");
}

.dhbvngb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.551 23.071a4.2 4.2 0 0 0 .842-2.526a4.18 4.18 0 0 0-3.143-4.06a3.4 3.4 0 0 0 .892-2.29c0-1.865-1.5-3.376-3.35-3.376c-.866 0-1.7.339-2.324.945a7.2 7.2 0 0 0-3.168-.737a7.2 7.2 0 0 0-4.37 1.484a2.14 2.14 0 0 0-1.963-1.29a2.15 2.15 0 0 0-2.14 2.161c0 1.06.761 1.963 1.799 2.133a7.3 7.3 0 0 0-.557 2.802q-.002.21.01.421a5 5 0 0 0-.413-.018c-2.59 0-4.688 2.117-4.687 4.726c0 1.63.821 3.074 2.076 3.924");
}

.l-n6il1vd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.986 28.9l-2.743 8.281l-2.743-8.28m21.978 1.732v6.548m8.12-9.883v8.648c0 .682.546 1.235 1.22 1.235h.366m-6.446-9.883v8.648c0 .682.546 1.235 1.22 1.235h.365m11.857-1.247a2.43 2.43 0 0 1-2.12 1.247c-1.347 0-2.439-1.106-2.439-2.47v-1.607c0-1.364 1.092-2.47 2.44-2.47s2.439 1.106 2.439 2.47v.803h-4.879m1.813-5.146l1.707-.618m-30.629 4.961c0-1.364 1.092-2.47 2.44-2.47s2.439 1.106 2.439 2.47v1.606c0 1.365-1.092 2.471-2.44 2.471s-2.44-1.106-2.44-2.47zm7.053-2.47v4.076c0 1.365 1.092 2.471 2.44 2.471s2.439-1.106 2.439-2.47v-4.077m-.001 4.077v2.47m2.475-16.056l2.552-4.936h-3.145");
}

.sd58tcc2x {
  cx: 26.478px;
  cy: 27.526px;
  r: 0.75px;
  fill: currentColor;
}

.ygw9j1bgu {
  cx: 31.376px;
  cy: 17.817px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.7px;
  ry: 1.639px;
}

</style>
