<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8qu_6jje"/><circle class="gqvjro-mh"/><circle class="ssg25x02h"/><circle class="kqcf4sfol"/><path class="qbgh9eb9b"/><circle class="rkfy_ubol"/><path class="ydqthzbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mewe" /></template>
<style>
.gqvjro-mh {
  cx: 29.937px;
  cy: 18.812px;
  r: 0.75px;
  fill: currentColor;
}

.kqcf4sfol {
  cx: 34.366px;
  cy: 18.812px;
  r: 0.75px;
  fill: currentColor;
}

.p8qu_6jje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.06 28.974c-.32.641-1.07 1.07-1.818 1.07a2.146 2.146 0 0 1-2.14-2.14v-1.39c0-1.177.964-2.14 2.14-2.14s2.14.963 2.14 2.14v.748h-4.28m20.078 1.712c-.322.641-1.07 1.07-1.82 1.07a2.146 2.146 0 0 1-2.139-2.14v-1.39c0-1.177.963-2.14 2.14-2.14s2.139.963 2.139 2.14v.748h-4.279m-1.006-5.776l-2.139 8.558l-2.139-8.558l-2.14 8.558l-2.139-8.558");
}

.qbgh9eb9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 30.043v-8.557l4.279 8.557l4.278-8.557v8.557");
}

.rkfy_ubol {
  cx: 12.779px;
  cy: 18.812px;
  r: 0.75px;
  fill: currentColor;
}

.ssg25x02h {
  cx: 25.508px;
  cy: 18.812px;
  r: 0.75px;
  fill: currentColor;
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
