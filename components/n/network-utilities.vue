<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ox6op560v"/><path class="jxye8cbfu"/><ellipse class="c0-grlblp"/><path class="se4t2bckf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:network-utilities" /></template>
<style>
.c0-grlblp {
  cx: 20.663px;
  cy: 20.439px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.433px;
  ry: 15.021px;
}

.jxye8cbfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.109 15.292h29.107M6.109 25.585h29.107");
}

.ox6op560v {
  cx: 20.663px;
  cy: 20.439px;
  r: 15.439px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.se4t2bckf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.398 31.818a4.669 4.669 0 0 1-6.561 5.918l-4.099 4.75A1.757 1.757 0 0 1 29.254 40l4.75-4.098a4.669 4.669 0 0 1 5.917-6.561l-3.068 3.06l.416 2.069l2.068.416Z");
}

</style>
