<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zlq76n2je"/><path class="i9clfwm2k"/><path class="brn-t3buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trt-izle" /></template>
<style>
.brn-t3buv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.83 26.6v8h4m-14.12-8v8m2.46-8h5.2l-5.2 8h5.2m8.92-4h2.6m1.4 4h-4v-8h4");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.zlq76n2je {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.49 13.4h5.2m8.62 0h5.2m-11.787 8v-8h2.6c1.5 0 2.7 1.2 2.7 2.7s-1.2 2.7-2.7 2.7h-2.6m2.698-.002l2.502 2.502m-9.833.1v-8m13.82 8v-8");
}

</style>
