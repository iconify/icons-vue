<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="b5n5-jbxp"/><circle class="d4cuz1s8g"/><path class="pqmfx-b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:satisfyer" /></template>
<style>
.b5n5-jbxp {
  cx: 19.733px;
  cy: 14.231px;
  r: 3.646px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d4cuz1s8g {
  cx: 39.165px;
  cy: 26.259px;
  r: 3.646px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pqmfx-b-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.56 12.95l11.985 11.99c1.332 1.332.122 12.956-6.995 12.956c-8.32-.001-10.05-2.673-10.05-2.673l5.237-5.24c2.873 2.874 6.148-.84 4.655-2.333c-.96-.807-6.514-6.516-6.514-6.516Zm31.794-2.845h-7.963a5.74 5.74 0 0 0-5.033 4.546l-6.1 22.772h7.713l4.489-16.756s.65-3.16 3.158-3.16H43.5Z");
}

</style>
