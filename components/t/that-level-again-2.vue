<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="owsvojb6k"/><path class="mi6_t7e_i"/><circle class="m8rl1l5kh"/><path class="twwbiyboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:that-level-again-2" /></template>
<style>
.m8rl1l5kh {
  cx: 36.675px;
  cy: 35.909px;
  r: 6.825px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mi6_t7e_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.714 22.017c.09 1.378-.158 2.523-.784 3.134c-1.235 1.207-2.468 2.23-4.967 2.201c-2.578-.03-5.752-1.903-5.752-5.335c0-2.855 1.87-5.17 5.752-5.17c3.978 0 5.54 1.9 5.751 5.17m16.488.349c.012 1.25-.076 2.262-.817 2.89c-1.31 1.11-3.777 1.72-5.556 1.697c-2.774 0-4.069-1.834-4.069-4.719c0-2.363.391-3.423 1.767-4.145c.784-.41 1.935-.907 3.266-.903c2.87.01 5.379 2.114 5.409 5.18");
}

.owsvojb6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.96 36.884a27.2 27.2 0 0 1-8.559 1.394c-9.427 0-16.901-5.301-16.901-16.26c0-9.11 6.104-16.45 17.922-16.747c7.719-.193 17.034 4.636 17.999 15.46v.001c.37 4.173.051 7.064-.7 9.074");
}

.twwbiyboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.091 34.593a2.586 2.586 0 0 1 3.097-2.534c1.083.208 1.949 1.145 2.056 2.243c.08.817-.178 1.623-.742 2.118c-1.045.917-4.41 3.39-4.41 3.39h5.167");
}

</style>
