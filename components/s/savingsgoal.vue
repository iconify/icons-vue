<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qs1nx_bra"/><path class="dyq-8opuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:savingsgoal" /></template>
<style>
.dyq-8opuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.01 32.19c.786 1.022 1.771 1.403 3.141 1.403h1.897a3.2 3.2 0 0 0 3.195-3.202a3.2 3.2 0 0 0-3.195-3.202h-2.096a3.2 3.2 0 0 1-3.195-3.203a3.2 3.2 0 0 1 3.195-3.202h1.897c1.37 0 2.355.381 3.14 1.404M24 20.784v-1.601m0 16.011v-1.601");
}

.qs1nx_bra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.578 11.877c8.13 15.312 14.453 30.623 0 30.623H16.422c-14.453 0-8.13-15.311 0-30.623m11.543-5.42c1.41-.325 3.13-.8 5.018-.953c1.013-.081 1.712.996 1.202 1.876l-2.607 4.497H16.422L13.815 7.38c-.51-.88.189-1.957 1.203-1.876c1.888.153 3.572.888 5.018.953c.919.042 2.285-.236 3.508-.15c1.42.1 2.74.539 4.42.15Z");
}

</style>
