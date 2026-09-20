<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="pe22n5bqi"/><path class="dlw_ibbre"/><path class="k4t3b3bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shappky" /></template>
<style>
.dlw_ibbre {
  d: path("m31.404 17.769l-13.11 7.446l12.668 7.657c.242.146.42.464.179.841c-2.82 4.41-7.446 6.925-12.68 6.925c-8.515 0-15.418-6.903-15.418-15.418S9.946 9.803 18.461 9.803c5.167 0 9.942 2.617 12.84 6.884c.254.373.257.995.103 1.082");
}

.fmn8yub-d {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k4t3b3bap {
  d: path("M17.165 16.742a1.72 1.72 0 0 1-1.718 1.718a1.72 1.72 0 0 1-1.718-1.718a1.72 1.72 0 0 1 1.718-1.718a1.72 1.72 0 0 1 1.718 1.718m-6.782-9.38l2.13 3.484m13.275-3.482l-2.05 3.343");
}

.pe22n5bqi {
  d: path("M27.114 22.991h2.121c.648 0 1.17.521 1.17 1.169v2.12c0 .648-.522 1.17-1.17 1.17h-2.12a1.166 1.166 0 0 1-1.17-1.17v-2.12c0-.648.522-1.169 1.17-1.169m14.552 0h2.12c.649 0 1.17.521 1.17 1.169v2.12c0 .648-.521 1.17-1.17 1.17h-2.12a1.166 1.166 0 0 1-1.169-1.17v-2.12c0-.648.522-1.169 1.17-1.169m-7.278 0h2.121c.648 0 1.17.521 1.17 1.169v2.12c0 .648-.522 1.17-1.17 1.17h-2.12a1.166 1.166 0 0 1-1.17-1.17v-2.12c0-.648.522-1.169 1.17-1.169");
}

</style>
