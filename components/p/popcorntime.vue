<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvhy2imbc"/><path class="op775dbcb"/><path class="fo4tb8bxy"/><circle class="n3gn-lbkw"/><circle class="offbthbwp"/><circle class="zz_uz-bwm"/><circle class="so8pdtloj"/><path class="k90u18r6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:popcorntime" /></template>
<style>
.bvhy2imbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.45 22.47l8.21 3.49l18.85-1.85l-1.48 16.98l-16.71 2.41l-6.7-4.55zm8.21 3.49l.66 17.54");
}

.fo4tb8bxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.1 23.08c3.39 0 3-4.13 2.33-4.28a11.5 11.5 0 0 0-2.33 0a11.4 11.4 0 0 0-2.32 0c-.66.2-1.06 4.28 2.32 4.28");
}

.k90u18r6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.75 24.48l-1.08 17.1m-3.48-16.65l-.44 17.21m-4.92-16.68l.27 17.35m-8.2-18.02L17 41.93m-3.99-18.37l1.61 16.75");
}

.n3gn-lbkw {
  cx: 17.75px;
  cy: 16.95px;
  r: 2.13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.offbthbwp {
  cx: 31.01px;
  cy: 16.95px;
  r: 2.13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.op775dbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.89 24.12c.33-.43-.17-1.42-.73-1.46c0 0 2.77-.75 2.44-3s-3.3-3-3.3-3S40.71 4.5 29 4.5c-9.71 0-10.82 6.83-10.82 6.83s-3.36-4.92-7-1.53c-4 3.78 1 6.3 1 6.3s-2.89 1.17-2.89 3c0 2.26 2.32 3.85 2.32 3.85");
}

.so8pdtloj {
  cx: 18.24px;
  cy: 16.54px;
  r: 0.75px;
  fill: currentColor;
}

.zz_uz-bwm {
  cx: 31.42px;
  cy: 16.54px;
  r: 0.75px;
  fill: currentColor;
}

</style>
