<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2de_abao"/><path class="rsv5dtbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proton-authenticator" /></template>
<style>
.j2de_abao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.058 22.203a3.058 3.058 0 1 0-6.116 0a3.05 3.05 0 0 0 1.747 2.753v2.759a1.31 1.31 0 0 0 2.622 0v-2.759a3.05 3.05 0 0 0 1.747-2.753");
}

.rsv5dtbsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.348a4.5 4.5 0 1 1 0 9c-5.33 0-9.652 4.321-9.652 9.652S18.67 33.652 24 33.652S33.652 29.33 33.652 24a4.5 4.5 0 1 1 9 0c0 10.301-8.35 18.652-18.652 18.652S5.348 34.302 5.348 24S13.698 5.348 24 5.348");
}

</style>
