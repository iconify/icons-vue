<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ari-4_6-q"/><path class="q4e77fbka"/><circle class="xni5rpbnr"/><path class="rpe6s6bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nu-client" /></template>
<style>
.ari-4_6-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.04 22.376v-8l5.3 8v-8m2.791 0v5.35a2.65 2.65 0 1 0 5.3 0v-5.35M12.7 4.5h-2.3c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h2.3");
}

.q4e77fbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.7 4.5v39h24.9c1.1 0 2-.9 2-2v-35c0-1.1-.9-2-2-2z");
}

.rpe6s6bou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.033 27.073v4.621m-2.834-6.975v6.103c0 .482.39.872.872.872h.262m14.417-6.06v5.188c0 .482.39.872.872.872h.262m-2.049-4.621h1.831m-17.992 3.742a1.743 1.743 0 0 1-3.258-.866v-1.133a1.744 1.744 0 0 1 3.256-.869m14.991 3.747v-2.877a1.744 1.744 0 1 0-3.487 0m-.001 2.877v-4.621m-2.055 3.74a1.743 1.743 0 0 1-3.26-.864v-1.133a1.744 1.744 0 1 1 3.488 0v.567H24.86");
}

.xni5rpbnr {
  cx: 23.033px;
  cy: 24.936px;
  r: 0.75px;
  fill: currentColor;
}

</style>
