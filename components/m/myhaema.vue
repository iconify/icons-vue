<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="togc5hbbg"/><path class="bujd_rb5r"/><circle class="nloec6w8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myhaema" /></template>
<style>
.bujd_rb5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.253 22.7a1.752 1.752 0 0 1 3.504 0v2.804m-3.504-4.555v4.555m3.504-2.804a1.752 1.752 0 0 1 3.504 0v2.804m-8.971-.884a1.752 1.752 0 0 1-3.274-.868v-1.139a1.752 1.752 0 0 1 3.504 0v.57h-3.504m-1.669.569a1.752 1.752 0 0 1-3.504 0v-1.139a1.752 1.752 0 0 1 3.504 0m0 2.891v-4.643m19.185 2.891a1.752 1.752 0 0 1-3.504 0v-1.139a1.752 1.752 0 0 1 3.504 0m0 2.891v-4.643m-12.279 6.861c.526 2.53 3.296 3.317 7.181 3.322c3.237.005 6.432-.4 7.182-3.764");
}

.nloec6w8r {
  cx: 39.616px;
  cy: 25.136px;
  r: 0.75px;
  fill: currentColor;
}

.togc5hbbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M8.531 18.496v7.008m4.643-7.008v7.008m-4.643-3.517h4.643");
}

</style>
