<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ey4-gz5xo"/><path class="lm4xs-50k"/><path class="ebe58q8lz"/><path class="azfczubsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:workd-mfa" /></template>
<style>
.azfczubsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.752 23.683a1.702 1.702 0 0 1-3.403 0a1.702 1.702 0 1 1 3.403 0m10.25 0a1.702 1.702 0 0 1-3.403 0a1.702 1.702 0 1 1 3.403 0m-5.125 0a1.702 1.702 0 0 1-3.403 0a1.702 1.702 0 1 1 3.403 0");
}

.ebe58q8lz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.247 34.612v-2.847h-4.62c-4.038 0-8.297-2.854-8.297-9.25s4.259-9.251 8.296-9.251h2.082");
}

.ey4-gz5xo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.832 42.085h17.325c8.103 0 16.97-5.594 16.97-16.722S36.26 8.64 28.158 8.64c-4.284 0-5.404 1.059-5.404 3.034v4.56h4.621c4.037 0 8.296 2.855 8.296 9.251s-4.259 9.251-8.296 9.251h-7.202c-5.619 0-9.34 2.172-9.34 7.35Z");
}

.lm4xs-50k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.918 10.23c.809-1.105 1.25-2.532 1.25-4.315H19.843c-8.103 0-16.97 5.594-16.97 16.722c0 7.562 4.093 12.568 9.26 15");
}

</style>
