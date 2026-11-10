<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="orj9476kt"/><path class="wk6zx7bdg"/><circle class="p0g9vvb4q"/><circle class="peaxzgyzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:puffer" /></template>
<style>
.orj9476kt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.338 10.406L24 3.037l.662 7.368q.988.044 1.962.221l1.215-2.353l.075 2.646q.955.263 1.866.65l2.56-3.799l-1.373 4.371q.872.473 1.673 1.058l2.116-1.595l-1.08 2.415q.745.651 1.396 1.396l6.17-4.077l-5.35 5.113q.585.8 1.058 1.672l2.589-.513l-2.018 1.701q.387.911.65 1.866l4.575-.367l-4.281 1.657q.176.973.221 1.962l2.561.662l-2.561.662q-.045.988-.221 1.961L45.5 30l-7.329-.995q-.263.956-.65 1.866l2.018 1.702l-2.59-.514q-.472.872-1.057 1.673l3.138 3.348l-3.958-2.312q-.651.745-1.396 1.395l1.08 2.416l-2.116-1.595a15 15 0 0 1-1.673 1.057l2.601 6.922l-3.788-6.35q-.911.387-1.866.65l-.075 2.646l-1.215-2.353q-.973.177-1.962.222L24 44.318l-.662-4.54a15 15 0 0 1-1.962-.222l-1.215 2.353l-.075-2.646a15 15 0 0 1-1.866-.65l-3.788 6.35l2.6-6.922q-.871-.472-1.672-1.058l-2.116 1.596l1.08-2.416q-.745-.65-1.396-1.396L8.97 37.08l3.138-3.348a15 15 0 0 1-1.057-1.673l-2.59.514l2.018-1.702a15 15 0 0 1-.65-1.866L2.5 30l7.036-2.285a15 15 0 0 1-.222-1.961l-2.561-.662l2.561-.662q.045-.989.222-1.962l-4.282-1.657l4.575.367q.263-.956.65-1.866l-2.018-1.701l2.59.513c.314-.58.668-1.14 1.057-1.672l-5.35-5.113l6.17 4.077q.652-.745 1.396-1.396l-1.08-2.415L15.36 13.2a15 15 0 0 1 1.673-1.058l-1.374-4.37l2.561 3.799q.911-.389 1.866-.65l.075-2.647l1.215 2.353a15 15 0 0 1 1.962-.222");
}

.p0g9vvb4q {
  cx: 24px;
  cy: 25.091px;
  r: 3.393px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.peaxzgyzi {
  cx: 24px;
  cy: 25.091px;
  r: 0.75px;
  fill: currentColor;
}

.wk6zx7bdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.698 19.72c2.953-5.147 9.52-6.925 14.666-3.972c5.147 2.954 6.925 9.52 3.971 14.667a11 11 0 0 1-1.107 1.581m-4.552 3.19a10.744 10.744 0 0 1-12.978-4.723m16.213-2.855a7.355 7.355 0 0 1-13.822-5.033");
}

</style>
