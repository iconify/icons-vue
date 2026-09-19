<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="co8y1yzeu"/><circle class="em7zrn3nd"/><circle class="jf4zmxzfz"/><circle class="i-3s9sb4q"/><circle class="e349qccyu"/><path class="gx1hbpcey"/><circle class="gnr75wzum"/><path class="mvmfbvwty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mycelium" /></template>
<style>
.co8y1yzeu {
  cx: 32.945px;
  cy: 24px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e349qccyu {
  cx: 23.942px;
  cy: 8.508px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.em7zrn3nd {
  cx: 23.942px;
  cy: 39.492px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gnr75wzum {
  cx: 6.052px;
  cy: 39.492px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gx1hbpcey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.34 24.776L24 29.199l7.617-4.396m-.032-1.551l-7.643-4.414l-7.602 4.387M24 37.94v-8.741m-9.003-3.647v9.256l7.6 3.911m2.714.053l7.634-4.405v-8.815m0 8.815l7.632 4.407M23.942 18.838V10.06");
}

.i-3s9sb4q {
  cx: 41.948px;
  cy: 39.492px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jf4zmxzfz {
  cx: 14.997px;
  cy: 24px;
  r: 1.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mvmfbvwty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.391 38.719l7.606-4.389");
}

</style>
