<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0e73ccqi"/><path class="hy77yab7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prey" /></template>
<style>
.hy77yab7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.08 14.07L24 10.63l5.92 3.44l4.5-2.6L24 5.46l-10.42 6.01zm17.3 7.34v9.16L24 37.14l-11.38-6.57v-9.16l-4.68-2.66v14.53L24 42.54l16.06-9.26V18.75z");
}

.n0e73ccqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 32.86l7.16-4.46l-3.94-2.37l14.12-8v-4.6l2.16-1.24V6.22l-17.46 10.1L24 15.14l-2.04 1.18L4.5 6.22v5.97l2.16 1.24v4.6l14.12 8l-3.94 2.37z");
}

</style>
