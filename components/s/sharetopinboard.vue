<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pzi7bmiwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sharetopinboard" /></template>
<style>
.pzi7bmiwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.826 4.5A1.15 1.15 0 0 0 15.8 5.525V6.55a1.08 1.08 0 0 0 1.025.883h3.17c.075 8.413-.59 13.854-4.015 14.072a4.007 4.007 0 0 0-4.004 4.003h10.021v15.99L24 43.5l2.002-2.002v-15.99h10.02a4.007 4.007 0 0 0-4.002-4.003c-3.943-.136-4.333-5.442-4.016-14.073h3.171a1.08 1.08 0 0 0 1.024-.882V5.525A1.15 1.15 0 0 0 31.175 4.5Zm5.172 21.008h4.004");
}

</style>
