<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cyf4ocbij"/><circle class="labqe46de"/><path class="s20tw_b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swindon-bus" /></template>
<style>
.cyf4ocbij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5A21.5 21.5 0 0 1 45.5 24M16.903 3.699v40.602M12.38 5.907v36.186");
}

.labqe46de {
  cx: 24.923px;
  cy: 15.71px;
  r: 0.75px;
  fill: currentColor;
}

.s20tw_b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.923 18.73v11.478m12.355 0V23.06a4.33 4.33 0 0 0-4.33-4.331h0a4.33 4.33 0 0 0-4.332 4.331v7.147");
}

</style>
