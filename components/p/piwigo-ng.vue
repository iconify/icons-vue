<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wo_dwabos"/><path class="g4qs4xbap"/><g class="y9tr6bcfx"><circle class="qzs24p5ez"/><circle class="svlekqb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:piwigo-ng" /></template>
<style>
.g4qs4xbap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.122 3.203a6.5 6.5 0 0 0-3.399.853C30.921 5.086 28.832 5.5 26.757 5.5H14.059A8.56 8.56 0 0 0 5.5 14.06v19.88a8.56 8.56 0 0 0 8.56 8.56h19.88a8.56 8.56 0 0 0 8.56-8.56V9.98c0-3.59-2.79-6.686-6.378-6.776");
}

.qzs24p5ez {
  cx: 24px;
  cy: 24px;
  r: 6.5px;
}

.svlekqb2n {
  cx: 24px;
  cy: 24px;
  r: 10.5px;
}

.wo_dwabos {
  cx: 35.955px;
  cy: 9.746px;
  r: 1.945px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
