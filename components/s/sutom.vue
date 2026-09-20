<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s053csbfe"/><circle class="fivd59buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sutom" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fivd59buv {
  cx: 29.334px;
  cy: 23.125px;
  r: 3.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s053csbfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.389 25.599l-1.348-6.93l4.818 6.263l2.123-7.601l1.346 6.927m-22.851-2.655l4.406-.876m-.911 7.241l-1.292-6.804m-9.082 1.69l.874 4.552c.239 1.246 1.43 2.06 2.66 1.817s2.032-1.448 1.793-2.693l-.874-4.553M6.642 30.202c.5.45 1.039.547 1.735.41l.964-.19a1.68 1.68 0 0 0 1.31-1.97l-.002-.008a1.657 1.657 0 0 0-1.94-1.328l-1.064.21a1.66 1.66 0 0 1-1.942-1.33a1.684 1.684 0 0 1 1.313-1.976l.959-.19c.696-.137 1.235-.04 1.735.41");
}

</style>
