<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gp1dg2rhp"/><path class="ti4y4sbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mint-launcher" /></template>
<style>
.gp1dg2rhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 19.696L24 5.5L5.5 19.696V42.5h37z");
}

.ti4y4sbzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 42.5L24 25.64L5.5 42.5M24 5.5v20.14");
}

</style>
