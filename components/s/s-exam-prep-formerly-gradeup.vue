<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9a6-ywiw"/><path class="bhx_05ybt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:s-exam-prep-formerly-gradeup" /></template>
<style>
.bhx_05ybt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.446 33.592l2.792-2.998l6.43 3.082l2.418 5.814l-2.816 3.01l-2.817-6.092zM29.597 15.52c1.57 0 2.84 1.246 2.84 2.78c0 1.524-1.27 2.769-2.84 2.769c-1.56 0-2.829-1.245-2.829-2.768c0-1.535 1.27-2.78 2.829-2.78");
}

.k9a6-ywiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.183 26.75l8.908-9.005l4.207 1.958L31.349 7.579l8.824 8.92l-11.955 12.137l1.608 4.327l-8.655 8.679l-4.702-10.166zM37.151 6.48l5.403-.98l-1.04 5.512z");
}

</style>
