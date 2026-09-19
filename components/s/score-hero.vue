<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hcors1b7b"/><circle class="t6gxx1bvh"/><path class="xog9f5kji"/><path class="w43a217-d"/><path class="lavsoqb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:score-hero" /></template>
<style>
.hcors1b7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.935 19.831c.492.64 1.109.879 1.967.879h1.188a2 2 0 0 0 2-2.001V18.7a2 2 0 0 0-2-2h-1.31a2.003 2.003 0 0 1-2.004-2.004h0c0-1.109.9-2.008 2.008-2.008h1.181c.858 0 1.475.239 1.967.88m6.025 6.132a2 2 0 0 1-1.741 1.01h0a2.005 2.005 0 0 1-2.006-2.006v-1.303c0-1.108.898-2.006 2.006-2.006h0c.744 0 1.393.405 1.739 1.007m4.123 4.308a2.005 2.005 0 0 1-2.005-2.005v-1.303c0-1.108.898-2.006 2.005-2.006h0c1.108 0 2.006.898 2.006 2.005v1.304a2.005 2.005 0 0 1-2.006 2.005m4.503-3.313c0-1.108.898-2.006 2.006-2.006m-2.006 0v5.314m7.579-1.158a2 2 0 0 1-1.742 1.012h0a2.005 2.005 0 0 1-2.005-2.005V17.25c0-1.107.898-2.005 2.005-2.005h0c1.108 0 2.006.898 2.006 2.005v.652h-4.011M9.776 27.708v8.022m5.315-8.022v8.022m-5.315-4.026h5.315");
}

.lavsoqb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.145 35.73v-8.022h2.626c1.485 0 2.689 1.206 2.689 2.694s-1.204 2.694-2.689 2.694h-2.626m2.627.001l2.627 2.631");
}

.t6gxx1bvh {
  cx: 39.497px;
  cy: 20.414px;
  r: 0.75px;
  fill: currentColor;
}

.w43a217-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.873 8.458h28.486c2.018 0 3.405 1.828 3.098 4.084l-3.12 22.916c-.307 2.256-2.192 4.084-4.21 4.084H7.641c-2.018 0-3.406-1.828-3.098-4.084l3.12-22.916c.307-2.256 2.192-4.084 4.21-4.084M6.103 24h35.794");
}

.xog9f5kji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.497 12.844v5.598m-5.375 17.292a2.657 2.657 0 0 1-2.657-2.657v-2.708a2.657 2.657 0 0 1 2.657-2.657h0a2.657 2.657 0 0 1 2.657 2.657v2.708a2.657 2.657 0 0 1-2.657 2.657m-16.514-4.015h2.615m1.395 4.011h-4.01v-8.022h4.01");
}

</style>
