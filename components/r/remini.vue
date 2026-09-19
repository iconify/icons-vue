<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="t-xwut1kt"/><circle class="lewfolbfc"/><path class="x5by77bjz"/><circle class="avjexgbtr"/><path class="uh-zvz5yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:remini" /></template>
<style>
.avjexgbtr {
  cx: 39.185px;
  cy: 20.693px;
  r: 0.75px;
  fill: currentColor;
}

.lewfolbfc {
  cx: 30.845px;
  cy: 20.693px;
  r: 0.75px;
  fill: currentColor;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.t-xwut1kt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.262 20.59v-5.112h4.257M15.32 29.994v1.533l2.07-.028m2.015-1.505l-.199 1.705l11.607 1.562l.34-2.557M20.598 20.59l.85-5.851l11.892 1.79l-.625 4.062M8 28.548v-8.162h2.65c1.529 0 2.752 1.224 2.752 2.754s-1.223 2.755-2.752 2.755H8m2.851-.009l2.558 2.659m7.399-3.261c0-1.122.917-2.04 2.038-2.04s2.039.918 2.039 2.04v3.265m-4.077-5.305v5.305m4.077-3.265c0-1.122.917-2.04 2.038-2.04s2.039.918 2.039 2.04v3.265");
}

.uh-zvz5yx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.185 23.142v5.407");
}

.x5by77bjz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.845 23.142v5.407m-12.22-1.022c-.305.612-1.019 1.02-1.732 1.02a2.046 2.046 0 0 1-2.039-2.04V25.18c0-1.122.917-2.04 2.039-2.04s2.038.918 2.038 2.04v.714h-4.077m22.169 2.656v-3.368c0-1.122-.918-2.04-2.039-2.04s-2.038.918-2.038 2.04v3.367m0-3.367v-2.04");
}

</style>
