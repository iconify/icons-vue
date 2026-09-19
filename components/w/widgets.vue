<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ay90-s2sm"/><circle class="igcljmu7i"/><path class="olipdqi-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:widgets" /></template>
<style>
.ay90-s2sm {
  d: path("M11.636 32.08h-.061a8.075 8.075 0 0 1-.095-16.15m25.053-.01a8.075 8.075 0 0 1 7.967 8.074h0c0 4.385-3.5 7.969-7.883 8.073M11.419 15.933h25m-24.917 16.14h25");
}

.igcljmu7i {
  cx: 13.148px;
  cy: 24.093px;
  r: 4.901px;
}

.olipdqi-l {
  d: path("m11.96 22.067l3.593 2.11l-3.623 2.091v-4.214m11.782-.134h15.652m-15.658 4.908h10.965");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
