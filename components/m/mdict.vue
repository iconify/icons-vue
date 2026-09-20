<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pr8yosb6z"/><path class="i9clfwm2k"/><path class="yfxz8z4ib"/><path class="cqrrf2btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mdict" /></template>
<style>
.cqrrf2btc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.55 13.266c2.58 5.491 4.866 8.723 10.805 11.982M17.738 30.47l-6.214 6.088");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.pr8yosb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.289 13.72c0 1.1-.9 2-2 2s-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2m0 3.299v-5.3m-5.208 5.301l-2.6-8l-2.026 6.002m.226-.703h3.5");
}

.yfxz8z4ib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.207 5.5c4.98 1.724 8.393 4.31 10.344 7.766a10 10 0 0 0-8.955 9.925c0 5.523 4.477 10 10 10a10 10 0 0 0 9.76-7.943c3.64 2.062 5.978 5.6 8.144 9.28C38.284 20.757 31.083 9.19 13.207 5.5");
}

</style>
