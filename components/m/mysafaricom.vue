<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gnmdoepjm"/><path class="nx7c7bbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mysafaricom" /></template>
<style>
.gnmdoepjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.146 30.94c.735.956 1.656 1.313 2.938 1.313h1.774a2.99 2.99 0 0 0 2.99-2.992v-.013a2.99 2.99 0 0 0-2.99-2.991h-1.957a2.994 2.994 0 0 1-2.992-2.995a3 3 0 0 1 2.999-3.002h1.765c1.282 0 2.203.357 2.938 1.314");
}

.nx7c7bbqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.179 21.84c8.99-6.66 8.12-16.303-14.621-3.644c-22.74 12.658-22.791 24.623.131 13.189");
}

</style>
