<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bqraaiblx"/><circle class="w80lorbjd"/><path class="d8ek2qo9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nafath" /></template>
<style>
.bqraaiblx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 17.175a.796.796 0 0 1-1.592 0a.796.796 0 0 1 1.592 0m-12.55.367a.796.796 0 1 1-1.592 0a.796.796 0 0 1 1.592 0m-13.4.158v10.854a3.055 3.055 0 0 0 3.048 3.062h6.81c1.714 0 5.779.355 6.407-4.95c.357-3.014-2.256-4.199-3.632-4.199s-3.99 1.185-3.633 4.199c.629 5.305 4.693 4.95 6.358 4.95h6.747a3.055 3.055 0 0 0 3.062-3.048v-5.601");
}

.d8ek2qo9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 31.581h4.206c6.108 0 2.885-7.702.017-8.696");
}

.w80lorbjd {
  cx: 9.278px;
  cy: 17.104px;
  r: 0.692px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
